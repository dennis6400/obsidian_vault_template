```dataviewjs
dv.taskList(dv.pages().where(p => !p.file.path.includes("04 - Templates")).file.tasks.where(t => !t.completed))
```