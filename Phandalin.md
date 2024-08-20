---
NoteType: Location
CommunitySize: Hamlet
Alignment: Neutral
Leader: Harbin Wester
Factions:
  - Zhentarim
Population: "200"
Commonraces:
  - Humans
Religions: Tymora
Exports:
  - Ore
  - Jewels
Imports: 
Defenses: Lord's Alliance
---

> [!infobox]
> # `=this.file.name`
> ![[MapSnippetPhandalin.png|small]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  | Miles
> ---|---|---|
> [[Neverwinter]] | 🕓: `VIEW[round((147* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`  | 147
> [[Umbrage Hill]] | 🕓: `VIEW[round((17* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]` | 17
> [[Axeholm]] | 🕓: `VIEW[round((30* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`  | 30
> [[Waterdeep]] | 🕓: `VIEW[round((346* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]` | 346
> [[Leilon]] | 🕓: `VIEW[round((52* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`  | 52
> [[C & H Farm]] | 🕓: `VIEW[round((121* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`  | 121
> [[Thornhold]] | 🕓: `VIEW[round((174* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`   | 174
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)



# `=this.file.name`
## Overview
Frontier mining town near the foothills of the Sword Mountains.  The region is rich in natural resources and adventuring opportunities.  The town has quickly grown off the news of local miner Don John Demarshé finding gold, silver and ore.

The party was last here 24th Kythorn 1491DR.  

### Current Story
Harbin has gone to Neverwinter, been gone for 2 tendays.  Sildar left for Waterdeep a day before, something about Griffin's and Neverwinter.  Sildar did send a group of  10 Lord's Alliance as town guard currently, they are based in Tresendar, also tasked with cleaning and repairing the place.  Halia has been placed in charge of Phandalin.  

![[PhandalinMap.png|500]]

## Notable NPCs
Harbin Wester - Town master
Halia Thornton - Current town master in Harbin's absence, runs Miner's Exchange
Elmar Barthen - Runs Barthen's Provisions (El MAR, never El MER)
Linene Graywind - Runs Lionshield Coster
Sariah - Took over Stonehill Inn and Daran Edermath's Orchard
Tommy - Young town guard
Simmy - town guard, reads scrolls "Welcome to Phandalin, home of the right people in the right places doing the right jobs at the right time.  Please state your business. "
## Points of Interest
### Original Locations
**Barthen's Provisions**: The biggest trading post in Phandalin, which stayed open from sunup to sundown. It was run by a lean and balding, middle-aged man with a kindly manner, Elmar Barthen.

**Edermath Orchard**: An orchard field with the simple cottage of a silver-haired half-elf named Daran Edermath. Daran was a retired marshal in the lands of the Dragon Coast. When he retired, he returned to the Neverwinter region, which was his original home, to grow apples and make cider.  Daran has died and his farm is now operated by Sariah and others in the area that were in need. 

**Lionshield Coster**: A weapons and armor supplier owned by the Lionshield Coster. The master of this post is a sweet older woman named Linene Graywind.

**Phandalin Miner's Exchange**: A trading post where miners had their finds weighed and paid out.  Run by Halia Thornton, who trades more than gems and jewels in the area.  She has many connections and many, many sending stones.

**Shrine of Luck**: A small shrine made of stones from ruins and Phandalin's only temple, dedicated to Tymora.  A curiosity more than anything. 

**The Sleeping Giant**: A rundown establishment that was originally offered to the party during their first stay in Phandalin.  It has been cleaned up and re-opened by Sariah and the people from Daran's orchard.  Sariah has established the Gorunn family here.  

**Stonehill Inn**: A modest inn that is now run by Sariah Halkitt.

**Townmaster's Hall**: A small building that served as the seat of the town government. It also housed a small, but serviceable jail in the cellar.

**Tresendar Manor**: More of a castle than a manor, this was an ancient building that was abandoned after the orc raids of 951 DR. In the late 15th century DR, the cellars—once served as a safe haven when the estate was attacked. It also served as a resting place for the deceased members of the Tresendar family—were turned into the hideout of the Redbrands. 

### New Locations
**Smith** - Local blacksmith Hotath Brocksopp, burly human short on words and intelligence.  People have nicknamed him "Hot" as when visiting him at the forge he states "I'm hot"

Various homes and smaller businesses

Graequil Burrow - Seamstress
Belic
Mertt
Barris
# Notable Members
```dataview
List 
from "1. World"
where (contains(Home, this.file.name)or contains(CurrentLocation, this.file.name))
and (contains(NoteType, "Player")or contains(NoteType, "NPC"))
```

# Celebrations
```dataview
List
from "1. World"
where contains(Location, this.file.name)
and contains(NoteType, "Celebration")
```
