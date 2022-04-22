---
tags: locations
aliases: 
---

# {{title}}

- 

## Establishments
```dataview
table proprietor, shop-type
from #shops and -"_templates"
where contains(location, link("{{title}}"))
sort file.name
```

## Factions
```dataview
table location 
from #factions and -"_templates"
where contains(location, link("{{title}}"))
sort file.name
```

## People
```dataview
table status, faction, location, origin
from #npcs and -"_templates"
where contains(origin, link("{{title}}")) or contains(location, link("{{title}}"))
sort file.name
```
