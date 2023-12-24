---
due: 2023-11-21
title: Anki_单向顺序链表
tags: Anki,链表,C语言
cards-deck: 2-输出::5问答笔记
---


#card


## 链表的抽象数据类型 #card 
1. **插入（Insert）**：在链表的特定位置或开头插入新的元素。
2. **删除（Delete）**：从链表中删除特定位置的元素。
3. **获取（Get）**：获取特定位置的元素值。
4. **搜索（Search）**：在链表中查找特定值的元素，并返回其位置或其他相关信息。
5. **遍历（Traverse）**：按顺序访问链表中的每个元素。

## 创建初始化单向顺序链表的方法 
### 头插法 #card
```c
// 定义链表节点结构
struct Node {
    int data;
    struct Node* next;
};
// 头插法初始化链表
struct Node* initializeList(int values[], int length) {
    struct Node* head = NULL; //创建当前指针(不停指向新的创建节点)

    for (int i = 0; i < length; i++) {
        struct Node* newNode = (struct Node*)malloc(sizeof(struct Node));
        if (newNode == NULL) {
            printf("Memory allocation failed\n");
            exit(EXIT_FAILURE);
        }

        newNode->data = values[i];
        newNode->next = head; // 将新节点的next指向当前头节点
        head = newNode;       // 更新头节点为新节点
    }
    return head; //此时当前指针已经是头指针了
}
int main() {
    int values[] = {1, 2, 3, 4, 5}; //将数组内容转化为单向顺序链表内容
    int length = sizeof(values) / sizeof(values[0]);
    // 使用头插法初始化链表
    struct Node* head = initializeList(values, length); //创建头指针，并初始化链表
    return 0;
}
//请注意，链表节点的顺序是逆序的，这是由头插法的特性所决定的
```


### 尾插法 #card

```c
// 定义链表节点结构
struct Node {
    int data;
    struct Node* next;
};
// 尾插法初始化链表并返回头尾指针
void initializeList(int values[], int length, struct Node** head, struct Node** tail) {
    *head = NULL;
    *tail = NULL;
    for (int i = 0; i < length; i++) {
        struct Node* newNode = (struct Node*)malloc(sizeof(struct Node));
        if (newNode == NULL) {
            printf("Memory allocation failed\n");
            exit(EXIT_FAILURE);
        }
        newNode->data = values[i];
        newNode->next = NULL;
        if (*head == NULL) {
            // 如果链表为空，则新节点既是头节点又是尾节点
            *head = newNode;
            *tail = newNode;
        } else {
            // 否则将新节点链接到当前尾节点的后面，并更新尾节点为新节点
            (*tail)->next = newNode;
            *tail = newNode;
        }
    } //天才
}
int main() {
    int values[] = {1, 2, 3, 4, 5};
    int length = sizeof(values) / sizeof(values[0]);
    struct Node* head = NULL; //函数作用域的指针，不会在初始化函数后被销毁
    struct Node* tail = NULL;
    // 使用尾插法初始化链表并返回头尾指针
    initializeList(values, length, &head, &tail); //输入数组，数组长度，头节点本身的地址，尾指针本身的地址
    return 0;
}//顺序链表，并且有了头指针和尾指针，可以更方便的调用，插入，删除节点
```


## 遍历单向顺序链表 #card
```c
void traverseList(struct Node*head){
	printf("Traversal using head insertion");
	struct Node* current = head;
	while(head != NULL){
		printf("%d->",current->data);
		current = current->next;
	}
	printf("NULL\n");
}
```
^1700529126689

## 插入节点
### 头部插入节点 #card
```c
void insertAthead(struct Node**head,int data){
	struct Node* NewNode =(struct Node*)malloc(sizeof(struct Node));
	if(new == NULL)
	{
		printf("Memory allcation failed\n");
	}
	NewNode->data = data;
	NewNode->next = *head;
	*head = NewNode;
}
```
^1700529126694

### 中间插入节点(在数据后插入节点) #card
```c
void insertAtnubmer(struct Node*head,int data,int arrval){
	struct Node* current = head;
	while(current->data != arr[arrval-1]){
		current =current->next;
	}
	struct Node*NewNode = (struct Node*)malloc(sizeof(struct Node));
	NewNode->data =data;
	NewNode->next = current->next;
	current->next = NewNode;
	if(current == NULL){
		printf("not Node found")
	}
}
```

## 删除节点(通过数据) #card
```c
void deleteNode(struct Node*head,int arrval){
	struct Node*current = head;
	struct Node*prev;
	while(current->data != arr[arrval-1]){
		prev = current;
		current = current->next;
	}
	if(current = NULL)
	{
		printf("data not found\n");
	}
	prev->next = current->next;
	free(current);
}
```
^1700529126707

## 销毁单向顺序链表 #card
```c
void destoryNode(struct Node*head){
	struct Node*current;
	while(head != NULL){
		current =head->next;
		free(head); //释放空间，并不会删除指针。
		head = current;
	}
}
```
^1700529126714
