```dataviewjs
dv.taskList(dv.pages().where(p => !p.file.path.includes("04 - Templates") && !p.file.folder.startsWith("05 - Personal")).file.tasks.where(t => !t.completed))
```