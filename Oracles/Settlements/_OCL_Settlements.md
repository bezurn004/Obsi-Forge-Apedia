---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Settlements Oracle"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Settlements Oracle
Listed are the Oracles used to generate settlements during your travels through the Forge.

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Settlement Oracle Focus",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Settlement") & !contains(PageCategory, "Index")
SORT OracleOrder, asc
```


## Tags
#Pedia/Oracles/Settlements

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>