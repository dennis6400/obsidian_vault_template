---
creation date:
last modified date:
aliases: []
tags: [project]
status: todo
---

Primary Categories:
Secondary Categories: [[02 - Projects]]
Client:
Links:

---

# [[<% tp.file.title %>]]

## Kontakte

```dataview
list FROM [[]] AND #contact SORT file.name asc
```

## Wichtige Bereiche

- TODO

**Lokale Dateien:**

```
TODO
```

## Meetings & Logs

```dataview
list FROM [[]] AND (#meeting OR #log) AND !"04 - Templates" SORT file.name asc
```

## Aufgaben

### To Do

-  To Do (Teams)

### Planner

- Planner (Teams)
- Planner (office.com)

### Obsidian

```dataviewjs
dv.taskList(dv.pages('[[]] and !"04 - Templates"').file.tasks.where(t => !t.completed))
```

### Weitere Infos

Siehe auch OmniFocus.

## Misc

```dataview
list FROM [[]] AND !(#meeting OR #log OR #contact) AND !"04 - Templates" AND !"01 - Primary Categories" AND !"02 - Secondary Categories" SORT file.name asc
```