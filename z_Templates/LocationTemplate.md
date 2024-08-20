---
NoteType: Location
LocationName: 
CommunitySize: 
Population: 
Commonraces: 
Leader: 
Imports: 
Exports: 
Religions: 
Factions:
---

<% await tp.file.move("/1. World/Locations/" + tp.file.title) %>

<%*  
const hasTitle = !tp.file.title.startsWith("NewLocation");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Location Name");  
await tp.file.rename(title);  
} else {  
title = tp.file.title;  
}  
_%>

> [!infobox]
> ![[MapPlaceholder.png|right lp]]
> 
> | Type | Stat |
> | ---- | ---- |
> | Leader | `= "[[" + this.Leader + "]]"`|
> | Population Size | `VIEW[{Population_Size}]` |
> | Major Race | `VIEW[{Demographics}]` |
> | Test | Testing |

![[MapPlaceholder.png]]
# Overview

# Factions

# Notable Members
```dataview
List 
from "1. World"
where contains(Home, this.file.name)
and (contains(NoteType, "Player")or contains(NoteType, "NPC"))
```

# Celebrations
```dataview
List
from "1. World"
where contains(Location, this.file.name)
and contains(NoteType, "Celebration")
```
# POIs

# Enemies

 
