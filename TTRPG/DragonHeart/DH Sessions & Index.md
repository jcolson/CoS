---
title: Dragon Hearts Sessions & Index
created: 2021-12-31T13:34:17+00:00
tags: []
updated: 2022-01-17T10:49:11+00:00
---
# Dragon Hearts Sessions & Index
## Campaign Support
[[DH NPCs]]
Primary Location: [[Hannat]]
[[Snack Master]]
# Characters
```dataview
table alias, player, class, race, faction, background, player.location as location
from "TTRPG/DragonHeart"
where contains(tags,"dh-character")
sort created desc
``````

## Sessions
```dataview
table title, created, updated
from "TTRPG/DragonHeart"
where contains(tags,"dh-session")
sort created desc
```
