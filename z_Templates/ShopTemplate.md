---
NoteType: Location
LocationName: 
Home: 
Owner: 
Merchandise:
---

<% await tp.file.move("/1. World/Locations/" + tp.file.title) %>

<%*  
const hasTitle = !tp.file.title.startsWith("NewShop");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Shop Name");  
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
> | Owner | `= "[[" + this.Owner + "]]"`|
> | Location | `= "[[" + this.Home + "]]"`|
> | Merchandise | `VIEW[{Merchandise}]` |

![[MapPlaceholder.png]]
# Overview

# Inventory



 
