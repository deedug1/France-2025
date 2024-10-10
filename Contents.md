# All entries
```dataview
TABLE type, cost, rating, page, link
FROM ""
WHERE file.folder = this.file.folder + "/entries"
SORT number(page) DESC
```

# Chosen places
```dataview
TABLE
FROM #visit 
```

