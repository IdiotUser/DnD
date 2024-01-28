
```leaflet 
id: leaflet-map 
image:
height: 500px 
lat: 50 
long: 50 
minZoom: 3
maxZoom: 5
defaultZoom: 1
unit: 1
meters scale: 1 
marker: default, 39.983334, -82.983330, [[Note]] 
darkMode: false marker: Obelisk,-44.66268985052517,295.8514110908333,,,,

```
# [[The Company]]
## Active
```dataview
LIST player
from "Sunset-Fortune"
where type = "character"
where active = "Active"
sort file.name asc
```
# [[Sunset-Fortune/Loops/Quests & Questions|Quests & Questions]]

# [[Sunset-Fortune/Loops/Agenda|Agenda]]

# Sessions
```dataview
table summary
from "Sunset-Fortune/Sessions"
where type = "session"
sort file.name asc
```
# Factions
```dataview
table description, rel, met, HQ
from "Sunset-Fortune/Compendium"
where type = "faction"
sort file.name asc
```
# NPCs
```dataview
table race, occupation, faction, sex, location, rel, met, status
from "Sunset-Fortune/Compendium"
where type = "npc"
sort file.name asc
```
# Info
```dataview
table description
from "Sunset-Fortune/Compendium"
where type = "info"
sort file.name asc
```
