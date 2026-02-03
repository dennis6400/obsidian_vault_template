---
creation date: 2025-10-03 15:25:51
last modified date: 2026-02-03 16:34:57
aliases: []
tags: [todos]
status:
---

# [[All Tasks]]

```dataviewjs
dv.taskList(dv.pages().where(p => !p.file.path.includes("04 - Templates")).file.tasks.where(t => !t.completed))
```