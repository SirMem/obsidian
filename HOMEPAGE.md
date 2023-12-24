### ***OBSIDIAN ACTIVITY***
```dataviewjs

let ftMd = dv.pages("").file.sort(t => t.cday)[0]
let total = parseInt([new Date() - ftMd.ctime] / (60*60*24*1000))
let totalDays = "您已使用 *Obsidian* "+total+" 天，"
let nofold = '!"misc/templates"'
let allFile = dv.pages(nofold).file
let totalMd = "共创建 "+
	allFile.length+" 篇笔记"
let totalTag = allFile.etags.distinct().length+" 个标签"
let totalTask = allFile.tasks.length+"个待办。 "
dv.paragraph(
	totalDays+totalMd+"、"+totalTag+"、"+totalTask
)

```
````ad-flex
<div>

### 最近编辑
```dataview
table WITHOUT ID file.link AS "标题",file.mtime as "时间"
from !"模板" and !"kanban"
sort file.mtime desc
limit 5
```
</div>

<div>

### 三天内创建的笔记
```dataview
table file.ctime as 创建时间
from ""
where date(today) - file.ctime <=dur(3 days)
sort file.ctime desc
limit 5
```
</div>
````


````ad-hint
### 文件总览
<span>

```dataview
list
from "0-assets/dataview"
```
<div style=" width: 100%; height:220;overflow: hidden; "><iframe src="https://widget.pkmer.cn/free/ColorfulClock?user=fed26f9b-4d77-447a-8e88-da490c28505a&font-color=%234f46e5&ring-color-1=%23e13e78&ring-color-2=%23e79742&ring-color-3=%234483ec&ring-color-4=%238f30eb&lang=en" allow="fullscreen" style=" height: 100%; width: 100%;"></iframe></div>
</span>

<span>

### MOC
```dataview 
list
from "4-成果/MOC"
```

</span>
````



````ad-tldr
# 快速开始
<div>

```button
name 周笔记
type command
action Calendar: Open Weekly Note
templater true
```

</div>

<div>

```button
<div>
name 每日日记
type command
action 日记: 打开/创建今天的日记
templater true
```

</div>

<div>

```button
name 卡片笔记
type command
action QuickAdd: 笔记内容摘录
templater true
```

</div>

<div>

```button
name 重述笔记
type command
action QuickAdd: 重述笔记
templater true
```
</div>

<div>

```button
name 报告系统
type link
action obsidian://open?vault=LinYie&file=0-assets%2F%E5%B7%A5%E4%BD%9C%E5%8C%BA%2F%E6%8A%A5%E5%91%8A%E7%B3%BB%E7%BB%9F
templater true
```
^button-7yjb

</div>

<div>

```button
name 看板
type link
action obsidian://open?vault=LinYie&file=0-assets%2F%E5%B7%A5%E4%BD%9C%E5%8C%BA%2F%E5%B7%A5%E4%BD%9C%E5%8C%BA
```

</div>
````

```button
name 周笔记
type command
action Calendar: Open Weekly Note
templater true
```
```button
<div>
name 每日日记
type command
action 日记: 打开/创建今天的日记
templater true
```
```button
name 卡片笔记
type command
action QuickAdd: 笔记内容摘录
templater true
```
```button
name 重述笔记
type command
action QuickAdd: 重述笔记
templater true
```
```button
name 报告系统
type link
action obsidian://open?vault=LinYie&file=0-assets%2F%E5%B7%A5%E4%BD%9C%E5%8C%BA%2F%E6%8A%A5%E5%91%8A%E7%B3%BB%E7%BB%9F
templater true
```
```button
name 看板
type link
action obsidian://open?vault=LinYie&file=0-assets%2F%E5%B7%A5%E4%BD%9C%E5%8C%BA%2F%E5%B7%A5%E4%BD%9C%E5%8C%BA
```




