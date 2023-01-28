---
Alias: "Module Assets"
PageType: AssetIndex
PageCategory: Module
---
# [[_Assets Index|Assets]]: Module Summary
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	GameplayRole As "Gameplay Role",
	TrackLabels + " (" + TrackMax + ")"  As "Track (Amount)",
	Aspect As "Module Aspect"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Module") & !contains(PageType, "Index")
```

#Pedia/Assets/Module 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>