
# Lonely Planet France Entries
```dataview
TABLE type, cost, rating, page, link
FROM ""
WHERE file.folder = this.file.folder + "/entries" AND source = "Lonely Planet France 15th Edition"
SORT number(page) DESC
```
# Essential France Entries
```dataview
TABLE type, cost, rating, page, link
FROM ""
WHERE file.folder = this.file.folder + "/entries" AND source = "Fodor's Essential France"
SORT number(page) DESC
```

# Chosen places
```dataview
TABLE
FROM #visit 
```

