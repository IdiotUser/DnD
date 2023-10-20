---
type: beast
world: <% tp.user.getThisWorld(tp) %>
campaign: <% tp.file.folder(false) %>
sessionNum: <% tp.getThisGameNum(tp) %>
date: <% tp.date.now("YYYY-MM-DD") %>
fc-calender: <% tp.file.folder(false) %>
fc-date:
	year: <% tp.user.getThisDate(tp) [0] %>
	month: <% tp.user.getThisDate(tp) [1] %>
	day: <% tp.user.getThisDate(tp) [2] %>
fc-category: Sessions
summary " "
---
# Legends
# Identification
## Breeds and mutations
# Habitat
# Den locations

# Behaviour

## Brooding

## Breeding

## Defensive
## Hunting 
### Feeding grounds
### Prey
# Tracking
# Killing
