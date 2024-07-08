---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Deed Assets"
PageType: AssetIndex
PageCategory: Deed
PageOrder: 0
---
# [[_Assets Index|Assets]]: Deed Summary
> **A Note about assets and progress moves**
> Some assets include abilities which might be applied to a variety of moves. This is usually phrased as “when you make a move to [blank].” However, most asset abilities apply only to action rolls. Unless an asset specifically defines a benefit for a progress move, you may not leverage an asset ability when making a progress roll.

> **First Deed Asset**
> [[AST_Bonded|BONDED]]

## Ironsworn Starforged Deed Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	PreReqCondition As "Asset PreReq"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Deed") & !contains(PageType, "Index") & contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## Community Content Deed Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	SourceMaterial As "Source",
	PreReqCondition As "Asset PreReq"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Deed") & !contains(PageType, "Index") & !contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_Companion Assets\|Companion Assets]]** | #Pedia/Assets/Deeds  | **[[_Module Assets\|Module Assets]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>