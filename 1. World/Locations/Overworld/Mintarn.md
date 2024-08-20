---
NoteType: Location
CommunitySize: Large City
Alignment: Neutral
Leader: Bloeth Embuirhan
Factions:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
  - Clan Ironstar
Population: 
Commonraces:
  - Humans
  - Dwarves
Religions: 
Exports:
  - Mercenaries
Imports:
---

> [!infobox]
> # `=this.file.name`
> ![[MapSnippetMintarn.png| small]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  |  Miles
> ---|---|---|
> [[Neverwinter]] | 🕓: `VIEW[round((521* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |521
> [[Waterdeep]] | 🕓: `VIEW[round((258* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |258
> [[Thornhold]] | 🕓: `VIEW[round((344* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |344
> [[Baldur's Gate]] | 🕓: `VIEW[round((277* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |277
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
Placeholder

### Placeholder Map
![[MapPlaceholder.png|Placeholder Map]]

### Placeholder Picture
![[ImagePlaceholder.png|Placeholder Picture]]

Placeholder

## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
Placeholder

## Valuables
Placeholder

## Internal Relationships
Placeholder

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder

