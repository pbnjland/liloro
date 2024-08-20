---
obsidianUIMode: preview
assa:
---

```dataview
TABLE WITHOUT ID link(file.name) AS "Character", Player, ac, pasperc As "Pass Perc (WIS)"
from "1. World"
where contains(NoteType, "Player") 
where contains(Status, "Alive")
```

```meta-bind-button
label: New Journal Entry
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateJournal.md"
    fileName: NewJournal
```

```meta-bind-button
label: New NPC
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateNPC.md"
    fileName: NewNPC
```

```meta-bind-button
label: New Location
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/LocationTemplate.md"
    fileName: NewLocation
```

```meta-bind-button
label: New Faction
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateFaction.md"
    fileName: NewGroup
```

```meta-bind-button
label: New Magic Item
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateMagicItem.md"
    fileName: NewMagicItem
```

```meta-bind-button
label: New Player
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/CharacterTemplate.md"
    fileName: NewPlayer
```

```meta-bind-button
label: New Celebration
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/CelebrationTemplate.md"
    fileName: NewCelebration
```

```meta-bind-button
label: New Shop
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/ShopTemplate.md"
    fileName: NewShop
```

```meta-bind-button
label: New Item
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/ItemTemplate.md"
    fileName: NewItem
```
`BUTTON[button_quest]` 

## Known Languages

%% This will scan the player notes for any known languages and list the unique languages that the party know here. This is handy to determine quickly if the party can understand someone. %%

```dataviewjs
dv.list(dv.pages()
		.where(p => p.Status && p.Status.includes("Active") && p.Role && p.Role.includes("Player"))
		.PlayerKnownLanguages.distinct())
```
