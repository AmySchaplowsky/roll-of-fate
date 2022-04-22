---
tags: factions
aliases: 
origin: 
location: 
---

# {{title}}

- 

## Members
```dataview
table location, status
from #npcs and -"_templates"
where contains(faction, link("{{title}}"))
sort file.name
```
