---
date: 2024-01-29
campaign: Sunset Fortune
world: Tor
game_date: 
type:
  t: item
  s: wondrous item
  c: common
Attunement: false
Qty: "1"
Value_(each: 5
Value_(total): 5
location: Jean-Luc
description: This cloth mask converts the words that pass through it into vile obscenities
tags:
  - item
icon: FasCube
---

This cloth mask converts the words that pass through it into vile obscenities. While wearing this mask over your mouth, your words are heard as angry insults and swears instead of the ones you intend. You do not hear these words. A creature can make a DC 10 Intelligence (Investigation) or Wisdom (Insight) check to determine that the words it hears are not your own. Verbal spell components, command words, and actual obscenities you say are unaffected by the mask's magic and are heard normally by creatures within earshot.

_"You dortin' norbward dem nepple bang gunk stankin' bilt!"_

``` dataview
TABLE type.t, type.s
from "Sunset-Fortune/Compendium"
where type.t = "item" & type.s = "Jean-Luc"
sort file.name asc
```