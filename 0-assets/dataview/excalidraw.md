---
tags:
  - dataview
---
```dataview
table file.ctime as 创建时间 ,file.mtime as 截止编辑时间
from #excalidraw 
sort file.ctime asc
```