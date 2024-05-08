```dataview
TABLE title, status, date
FROM "content/topics"
WHERE status = "active"
SORT date desc
```