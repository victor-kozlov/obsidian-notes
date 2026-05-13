---
{"dg-publish":true,"permalink":"/10-meta/home/","tags":["gardenEntry"],"created":"2010-01-01","dg-note-properties":{"modified":"13.05.2026  14:04","created":"04.09.2025  17:43","published":"2010-01-01"}}
---



```base
filters:
  and:
    - note["dg-publish"] == true
    - note["dg-home"] != true
formulas:
  Untitled: ""
  Date: date(published).format("DD.MM.YYYY")
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
      - property: published
        direction: DESC
    columnSize:
      formula.Date: 135
      file.name: 428
    rowHeight: medium

```

