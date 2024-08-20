---
NoteType: NPC
Character: 
aliases: 
Gender: 
Race: 
Class: 
Age: 
Factions: 
Titles: 
Home: 
Alignment: 
Status: 
CurrentLocation:
---

<% await tp.file.move("/1. World/NPCs/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>
> [!infobox]
> # `=this.file.name`
> ![[ImagePlaceholder.png]]
> [[ImagePlaceholder.png|Show to Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `= "[[" + this.Home + "]]"`|
> Race | `=this.Race` |
> Class | `=this.Class` |
> Age | `=this.Age` |
> Faction | `= "[[" + this.Factions + "]]"`|
> Titles | `=this.Titles` |
> Alignment | `=this.Alignment` |
> Status | `=this.status` |
> CurrentLocation| `= "[[" + this.CurrentLocation + "]]"`|
> Statblock | 

# `=this.file.name`
## Profile
