#sf
# Major Quests
```dataview
table contact, objective, reward, state, taken, completed
from "Sunset-Fortune/Compendium"
where type.t = "quest" & type.s = "major"
sort file.name asc
```
# All Quests
```dataview
table contact, objective, reward, state, taken, completed
from "Sunset-Fortune/Compendium"
where type.t = "quest"
```

# Personal
```dataview
TABLE contact, objective, reward, state, taken, completed
from "Sunset-Fortune/Compendium"
where type.t = "quest" & type.s = "personal"
sort file.name asc
```
# Research