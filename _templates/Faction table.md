## Factions
```dataview
table location 
from #factions and -"_templates"
where contains(location, link("{{title}}"))
sort file.name
```

