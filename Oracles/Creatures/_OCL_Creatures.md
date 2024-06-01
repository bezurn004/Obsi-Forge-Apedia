---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Creatures Oracle"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Creatures
To create a creature roll on the oracles in this order.

- Location and Scale
- Basic Form
- Approach

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Creature Oracle Focus",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Creature") & !contains(PageCategory, "Index")
SORT PageOrder, asc
```

## Tags
#Pedia/Oracles/Creatures

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>