_Entirety of clinical knowledge accrued through study_
```dataview
TABLE authors, type, status
FROM "clinical"
WHERE file.name != "_CLIN MOC"
SORT last_updated
GROUP BY type
```
