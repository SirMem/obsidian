---
tags:
  - dataview
---
```dataview
table file.ctime as 创建时间 ,file.mtime as 截止编辑时间
from #mindmap 
sort file.ctime asc
```