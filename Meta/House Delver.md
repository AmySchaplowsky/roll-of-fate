---
tags: factions
aliases: 
origin: 
location: 
---

# House Delver

- 

## Members
```dataview
table location, status
from #pcs and #npcs and -"_templates"
where contains(faction, link("#delver"))
sort file.name
```
