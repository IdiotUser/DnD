
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
list from "Þe Weal of Eventide/Compendium"
where type = "character"
sort file.name asc
```
# [[Quests & Questions]]

# [[Agenda]]

# Sessions
```dataview
table summary
from "Þe Weal of Eventide/Sessions"
where type = "session"
sort file.name asc
```
# Factions
```dataview
table description, rel, met, HQ
from "Þe Weal of Eventide/Compendium"
where type = "faction"
sort file.name asc
```
# NPCs
```dataview
table race, occupation, faction, sex, location, rel, met, status
from "Þe Weal of Eventide/Compendium"
where type = "npc"
sort file.name asc
```
# Info
```dataview
table description
from "Þe Weal of Eventide/Compendium"
where type = "info"
sort file.name asc
```
