---
creation date:
last modified date:
aliases: []
tags: trip
status: todo
---

Primary Categories: [[01 - Organisation]]
Secondary Categories: [[02 - Reisen]]
Links:

---

# [[<% tp.file.title %>]]

## Flüge

```dataview
list FROM [[<% tp.file.title %>]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND #flight SORT file.name ASC
```

## Bahn

TODO

## Hotel

```dataview
list FROM [[<% tp.file.title %>]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND #hotel SORT file.name ASC
```

## Gemietete Mietwagen

```dataview
list FROM [[<% tp.file.title %>]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND #rental-car SORT file.name ASC
```

## Misc

```dataview
list FROM [[<% tp.file.title %>]] AND !("01 - Primary Categories" OR "02 - Secondary Categories" OR "04 - Templates") AND !(#rental-car OR #flight OR #hotel) SORT file.name ASC
```

---
*Created Date: `=this["creation date"]`*
*Last Modified Date: `=this["last modified date"]`*