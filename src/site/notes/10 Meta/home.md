---
{"dg-publish":true,"permalink":"/10-meta/home/","tags":["gardenEntry"],"created":"2010-01-01","ctime":"2025-09-04T17:43:05.836+02:00","mtime":"2026-05-13T14:39:16.248+02:00","dg-note-properties":{"modified":"2026-05-13T14:04","created":"2025-09-04T17:43","published":"2010-01-01"}}
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

