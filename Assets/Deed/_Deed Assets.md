---
Alias: "Deed Assets"
PageType: AssetIndex
PageCategory: Deed
---
# [[_Assets Index|Assets]]: Deed Summary
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	GameplayRole As "[[Gameplay Role]]",
	PreReqCondition As "Asset PreReq"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Deed") & !contains(PageType, "Index")
```

#Pedia/Assets/Deeds 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>