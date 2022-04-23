---
tags: locations
aliases: 
---

# Riverlands

- 

## Establishments
```dataview
table proprietor, shop-type
from #shops and -"_templates"
where contains(location, link("Riverlands"))
sort file.name
```

## Factions
```dataview
table location 
from #factions and -"_templates"
where contains(location, link("Riverlands"))
sort file.name
```

## People
```dataview
table status, faction, location, origin
from #npcs and -"_templates"
where contains(origin, link("Riverlands")) or contains(location, link("Riverlands"))
sort file.name
```
