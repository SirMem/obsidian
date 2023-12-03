---
tags:
  - dataview
---
```dataview
table file.ctime as 创建时间 ,file.mtime as 截止编辑时间
from #math and #卡片
sort file.ctime asc
```