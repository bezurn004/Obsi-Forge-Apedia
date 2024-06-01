---
Alias: "Assets"
---

# [[_INDEX|Index]]: Assets
## Asset Categories

### [[_Companion Assets|Companion Assets]]
NPC's who accompany the character.

### [[_Deed Assets|Deed Assets]]
Accomplishments or misfortunes available when the character reaches certain ranks.

### [[_Module Assets|Module Assets]]
Add-ons that can be applied to vehicles, usually only the Starship.

### [[_Path Assets|Path Assets]]
Professions or areas of study that provide abilities to the character based on their background.

### [[_Vehicle Assets|Vehicle Assets]]
Provide transportation, saftey, and abilities while undertaking explorations in the Forge.

## All Assets by Category
```dataview
TABLE without ID
	link(file.link, alias) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & !contains(PageType, "Index") & !contains(file.path, "Template")
SORT PageCategory asc, file.name asc
```

#Pedia/Assets 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>