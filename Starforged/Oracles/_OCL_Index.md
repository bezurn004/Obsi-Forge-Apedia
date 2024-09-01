---
Alias: "Oracles Summary"
PageType: Oracles
PageCategory: Index
---
# [[_INDEX|Index]]: Oracles Summary
See the **[[OCL_Using Oracles|Using Oracles]]** section for guidelines while playing Ironsworn: Starforged.

# Browse Oracles By Topic
> [[OCL_Core|Core]]
> [[_OCL_Space-Encounters|Space Encounter]]
> [[_OCL_Planets|Planets]]
> [[_OCL_Settlements|Settlements]]
> [[_OCL_Starships|Starships]]
> [[_OCL_Characters|Characters]]
> [[_OCL_Creatures|Creatures]]
> [[_OCL_Factions|Factions]]
> [[_OCL_Derelicts|Derelicts]]
> [[_OCL_PrecursorVaults|Precursor Vaults]]
> [[_OCL_LocationThemes|Location Themes]]
> [[_OCL_Miscellaneous|Miscellaneous]]

## All Oracles
```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Oracle Focus",
	PageCategory As "Oracle Category",
	SourceMaterial As "Oracle Source"
WHERE contains(PageType, "Oracle") & !contains(PageCategory, "Index") & !contains(file.path, "template") & !contains(PageCategory, "Guideline") & !contains(file.path, "Template")
SORT SourceMaterial, Asc & PageCategory, Asc
```

## Tags
| Previous Chapter | Tags | Next Chapter | 
| :--- | :---: | ---: |
| **[[_GNPC_Foes-Encounters\|Foes and Encounters]]** | #Pedia/Oracles | **[[_Assets Index\|Assets]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>