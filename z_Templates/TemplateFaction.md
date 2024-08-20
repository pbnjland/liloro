---
NoteType: Faction
Alignment: 
Leader: 
HQ:
---

<% await tp.file.move("/1. World/Factions/" + tp.file.title) %>

<%*  
const hasTitle = !tp.file.title.startsWith("NewGroup");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Group Name");  
await tp.file.rename(title);  
} else {  
title = tp.file.title;  
}  
_%>

> [!infobox]
> 
> ![[ImagePlaceholder.png|right lp|300]]
> ###### Basic Info
> Type | Stat
> | ---- | ---- |
> | Leader | `= "[[" + this.Leader + "]]"`
> | Location| `= "[[" + this.HQ + "]]"`
> | Alignment | `=this.Alignment` |
> 
# `=this.file.name`
# Background

## BELIEFS

# Notable Members
```dataview

Table Class, Titles, Home, CurrentLocation
FROM "1. World"
where contains(Factions, this.file.name)
and (contains(NoteType, "NPC") or contains(NoteType, "Player"))

```

# Base Locations

 ```dataview
List
From "1. World"
where contains(Factions, this.file.name)
and contains(NoteType, "Location")
```



