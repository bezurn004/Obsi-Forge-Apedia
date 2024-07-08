---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Module Assets"
PageType: AssetIndex
PageCategory: Module
PageOrder: 0
---
# [[_Assets Index|Assets]]: Module Summary
> **A Note about assets and progress moves**
> Some assets include abilities which might be applied to a variety of moves. This is usually phrased as “when you make a move to [blank].” However, most asset abilities apply only to action rolls. Unless an asset specifically defines a benefit for a progress move, you may not leverage an asset ability when making a progress roll.

For more information, see the rules related to [[GB_Assets#Modules|Module Assets]].

> **First Module Asset**
> [[AST_Engine Upgrade|ENGINE UPGRADE]]

## Ironsworn Starforged Module Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackLabels + " (" + TrackMax + ")"  As "Track (Amount)",
	Aspect As "Module [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Module") & !contains(PageType, "Index") & contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## Community Content Module Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackLabels + " (" + TrackMax + ")"  As "Track (Amount)",
	SourceMaterial As "Source",
	Aspect As "Module [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Module") & !contains(PageType, "Index") & !contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_Deed Assets\|Deed Assets]]** | #Pedia/Assets/Module | **[[_Path Assets\|Path Assets]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>