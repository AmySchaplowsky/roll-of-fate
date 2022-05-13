---
tags: locations
aliases: 
---

# Redfern

- Town in the [[Riverlands]]

## Establishments
```dataview
table proprietor, building-type
from #buildings and -"_templates"
where contains(location, link("Redfern"))
sort file.name
```




## Factions
```dataview
table location 
from #factions and -"_templates"
where contains(location, link("Redfern"))
sort file.name
```

## People
```dataview
table status, faction, location, origin
from #npcs and -"_templates"
where contains(origin, link("Redfern")) or contains(location, link("Redfern"))
sort file.name
```
