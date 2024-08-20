---
NoteType: Faction
Alignment: Lawful Good
Leader: Larael Silverhand
HQ: Regional
---



> [!infobox]
> 
>![[Lord's AllianceSymbol.png]]
>[[Lord's AllianceSymbol.png|Show to Players]]
> ###### Basic Info
> Type | Stat
> | ---- | ---- |
> | Leader | `= "[[" + this.Leader + "]]"`
> | Location | `=this.HQ`
> | Alignment | `=this.Alignment` |
> 
# `=this.file.name`
# Background
Depending on who was asked, the Lords' Alliance was considered either a strong coalition, or unsteady pact of political powers. While the Alliance was said by some to be a collective of aggressive and self-serving figureheads, others insisted they were among the most secure governing bodies in the west. The truth, as it usually was, lay somewhere between the two extremes. While the members often held opposing views and held interests that conflicted with their peers, these rivalries were set aside when true danger emerged to threaten their collective safety and prosperity. The true strength of the alliance, it was said, manifested when its members banded together on collaborative endeavors.

While some of these cities and city-states held more influence than others,[4] they aligned their goals for the greater good and prosperity of the whole alliance. Collectively they believed in the preservation of civilization for the better of their people.

The alliance's emblem was a golden crown set over a field of red.[13]
## Leaders
These were the member states and their leaders as of 1489 DR.

Amphail: Lord Dauner Ilzimmer
Baldur's Gate: Grand Duke of Baldur's Gate and Marshal of the Flaming Fists Ulder Ravengard
Daggerford: Duchess Morwen Daggerford
Longsaddle: Dowell Harpell
Mithral Hall: Queen Dagnabbet Waybeard
Mirabar: Marchion Selin Ramur
Neverwinter: Lord Protector Dagult Neverember
Silverymoon: High Mage Taern Hornblade
Waterdeep: Open Lord Laeral Silverhand (she was also the leader of the Alliance)
Yartar: Waterbaron Nestra Ruthiol

## Beliefs
1. If civilization is to survive, all must unite against the dark forces that threaten it.
2. Glory comes from protecting one’s home and honoring its leaders.
3. The best defense is a strong offense.
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



