
```leaflet 
id: leaflet-map 
image: [[World Map.JPG]]
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
# [['Herbologists']]
```dataview
LIST
from "Moonlight-Mishap"
where type = "character"
sort file.name asc
```
# [[Moonlight-Mishap/Loops/Quests & Questions]]

# [[Moonlight-Mishap/Loops/Agenda]]

# Sessions
```dataview
table summary
from "Moonlight-Mishap/Sessions"
where type = "session"
sort file.name asc
```
# Factions
```dataview
table description, rel, met, HQ
from "Moonlight-Mishap/Compendium"
where type = "faction"
sort file.name asc
```
# NPCs
```dataview
table race, occupation, faction, sex, location, rel, met, status
from "Moonlight-Mishap/Compendium"
where type = "npc"
sort file.name asc
```
# Info
```dataview
table description
from "Moonlight-Mishap/Compendium"
where type = "info"
sort file.name asc
```
