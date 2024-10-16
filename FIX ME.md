```dataview
TABLE type, cost, rating, link
FROM "France 2025/entries"
WHERE !location OR number(type) != null OR !source
```
