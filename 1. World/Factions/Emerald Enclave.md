---
NoteType: Faction
HQ: Ilighôn, Vilhon Reach
Leader: The Elder Circle
Alignment: Neutral Good
---

> [!infobox]
> 
> ![[EmeraldEnclaveBanner.png|right lp|300]]
> ###### Basic Info
> Type | Stat
> | ---- | ---- |
> | Leader | `= "[[" + this.Leader + "]]"`
> | Location | `= "[[" + this.HQ + "]]"`
> | Alignment | `=this.Alignment` |

# Background
The Emerald Enclave is a far-ranging group that opposes threats to the natural world and helps others survive the many perils of the wild. A ranger might be hired to lead a caravan through a treacherous mountain pass or the frozen tundra of Icewind Dale. A druid might volunteer to help a small village prepare for a long, brutal winter. Barbarians and witches who live like hermits most of the year might defend a town against marauding orcs or barbarians. Members of the Emerald Enclave know how to survive, and more importantly, they want to help others do the same. They are not opposed to civilization or progress, but they strive to prevent civilization and the wilderness from destroying one another.  
Members of the Emerald Enclave are spread far and wide, and usually operate in isolation. They learn to depend on themselves more than others. Survival in a harsh world also demands great fortitude and mastery of certain fighting and survival skills. Members of the Enclave who dedicate themselves to helping others survive the perils of the wilderness are more social than others who are charged with defending sacred glades and preserving the natural balance.  

## BELIEFS
1. The natural order must be respected and preserved.
2. Forces that seek to upset the natural balance must be destroyed.
3. The wilderness can be harsh. Not everyone can survive in it without assistance.
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
