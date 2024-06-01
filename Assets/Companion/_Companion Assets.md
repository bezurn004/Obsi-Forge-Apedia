---
Alias: "Companion Assets"
PageType: AssetIndex
PageCategory: Companion
---
# [[_Assets Index|Assets]]: Companion Summary
```dataview
TABLE without ID
	link(file.link, alias) As "Asset Name",
	GameplayRole As "[[Gameplay Role]]",
	TrackMax As "Max Health",
	Aspect As "Companion [[Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Companion") & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

#Pedia/Assets/Companion 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>