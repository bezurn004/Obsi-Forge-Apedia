---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Factions Oracle"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Factions
Factions add scale and narrative opportunities to your setting. But keep it manageable. Don’t overload your campaign with factions. Instead, focus on your interactions and entanglements with members of a few interesting factions.

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Faction Oracle Focus",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Faction") & !contains(PageCategory, "Index")
SORT OracleOrder, asc
```

## Tags
#Pedia/Oracles/Factions

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>