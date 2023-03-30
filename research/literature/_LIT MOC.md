---
alias: Literature
---
```dataview
TABLE last_author, institution, progress, doi
FROM "research/literature"
WHERE type = "Publication"
SORT type
```

