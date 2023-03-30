---
alias: Research
---

_Notes from independent research_
```dataview
TABLE type, project, status
FROM "research"
WHERE file.name != "_RS MOC"
SORT last_updated
GROUP BY type
```
