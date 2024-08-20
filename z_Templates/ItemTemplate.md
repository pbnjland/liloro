---
NoteType: Item
ItemName: 
ItemType:
---

<% await tp.file.move("/1. World/Equipment/" + tp.file.title) %>

<%*  
const hasTitle = !tp.file.title.startsWith("NewItem");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Item Name");  
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
> | ItemType | `= "[[" + this.Owner + "]]"`|

![[MapPlaceholder.png]]
# Overview

# Inventory



 
