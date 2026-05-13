---
{"dg-publish":true,"permalink":"/10-meta/home/","tags":["gardenEntry"],"created":"04.09.2025  17:43","dg-note-properties":{"modified":"13.05.2026  13:37","created":"04.09.2025  17:43"}}
---



```base
filters:
  and:
    - note["dg-publish"] == true
    - note["dg-home"] != true
formulas:
  Untitled: ""
  Date: modified.slice(0, 10)
properties:
  file.name:
    displayName: Title
  note.modified:
    displayName: Date
  note.description:
    displayName: Description
  file.mtime:
    displayName: Date
views:
  - type: table
    name: Published Notes
    order:
      - formula.Date
      - file.name
      - description
    sort:
      - property: file.ctime
        direction: DESC
    columnSize:
      formula.Date: 135
      file.name: 428
    rowHeight: medium

```

