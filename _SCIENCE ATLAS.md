
# Projects

**[[_RS MOC|Research]]**
_Notes from research projects_
```dataview
TABLE institution, start_date, last_updated, status
FROM "research/projects"
WHERE type = "Research Project"
WHERE file.name != "_LIT MOC"
SORT last_updated
LIMIT 10
```


# Major MOCs

## [[_LIT MOC|Literature]]
_Research literature_
```dataview
TABLE type, project, status
FROM "research"
WHERE file.name != "_LIT MOC"
SORT last_updated
LIMIT 10
```

## [[_CLIN MOC|Clinical]]
_Entirety of clinical knowledge accrued through study_
```dataview
TABLE authors, type, status
FROM "clinical"
WHERE file.name != "_CLIN MOC"
SORT last_updated
LIMIT 10
```

## [[_REF MOC|Reference]]
_Entirety of scientific knowledge accrued through study_
```dataview
TABLE status
FROM "ref"
WHERE file.name != "_REF MOC"
SORT last_updated
LIMIT 10
```
