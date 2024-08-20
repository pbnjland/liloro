---
tags:
  - Category/Settlement
CommunitySize: Outpost
Alignment: Neutral Good
NoteType: Location
Leader: Falcon the Hunter
Factions:
  - Emerald Enclave
Population: "1"
Commonraces: 
Religions: 
Exports: 
Imports:
---


> [!infobox]
> # `=this.file.name`
> ![[MapSnippetFalcon'sNest.png|cover small]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  |
> ---|---|
> [[2. Session Journals/After The Fire Arc/Session 2 - 7/12/24/Logging Camp]] | 🕓: `VIEW[round((20.8* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> [[Thundertree]] | 🕓: `VIEW[round((40.6* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> [[Phandalin]] | 🕓: `VIEW[round((142* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> [[1. World/Locations/Neverwinter/Neverwinter]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> [[Nesmé]] | 🕓: `VIEW[round((255* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
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
Base of operations for the [[Emerald Enclave]] in Neverwinter Wood.  Currently manned by [[Falcon The Hunter]], used regionally during High Harvesttide to induct new members.  Lodge has been in use for many years, and has had many donors and visitors during it's time.  The banners of nobility that hang throughout the lodge were once considered friends of the Enclave...some still are.  There are also several designs dedicated to the [[Seven Sisters]] hidden throughout the lodge.  These hint at the identity of it's current master.  

![[MapSnippetFalcon'sMap.png]]

## Notable NPCs
[[Falcon The Hunter]]

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

