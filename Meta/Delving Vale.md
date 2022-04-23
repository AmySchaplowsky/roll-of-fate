---
tags: locations
aliases: 
---

# Delving Vale
![[Delving Vale.jpg]]

## Establishments
```dataview
table owner, building-type
from #buildings  and -"_templates"
where contains(location, link("Delving Vale"))
sort file.name
```

## Factions
```dataview
table location 
from #factions and -"_templates"
where contains(location, link("Delving Vale"))
sort file.name
```

## People
```dataview
table status, faction, location, origin
from #npcs and -"_templates"
where contains(origin, link("Delving Vale")) or contains(location, link("Delving Vale"))
sort file.name
```
