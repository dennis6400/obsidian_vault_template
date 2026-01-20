---
creation date:
last modified date:
aliases: []
tags: [client]
status: todo
---

Primary Categories:
Secondary Categories: [[02 - Clients]]
Links:

---

# [[<% tp.file.title %>]]

## Projects & Engagements

```dataview
list FROM [[]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND !outgoing([[]]) AND (#project OR #engagement) SORT file.name asc
```

## Meetings

```dataview
list FROM [[]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND !outgoing([[]]) AND #meeting SORT file.name asc
```

## Misc

```dataview
list FROM [[]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND !outgoing([[]]) AND !(#meeting OR #project OR #engagement) SORT file.name asc
```

---
*Created Date: `=this["creation date"]`*
*Last Modified Date: `=this["last modified date"]`*