---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Companion Assets"
PageType: AssetIndex
PageCategory: Companion
PageOrder: 0
---
# [[_Assets Index|Assets]]: Companion Summary
> **A Note about assets and progress moves**
> Some assets include abilities which might be applied to a variety of moves. This is usually phrased as “when you make a move to [blank].” However, most asset abilities apply only to action rolls. Unless an asset specifically defines a benefit for a progress move, you may not leverage an asset ability when making a progress roll.

## Ironsworn Starforged Companion Assets
> **First Companion Asset**
> [[AST_Banshee|BANSHEE]]

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackLabels + " / " + TrackMax As "Track Name / Max",
	Aspect As "Companion [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Companion") & !contains(PageType, "Index") & contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## Ironsworn: Sundered Isles Companion Assets
> **First Companion Asset**
> [[AST_Albatross|ALBATROSS]]
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackLabels + " / " + TrackMax As "Track Name / Max",
	Aspect As "Companion [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Companion") & !contains(PageType, "Index") & contains(SourceMaterial, "Sundered Isles")
SORT PageOrder
```

## Community Content Companion Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackLabels + " / " + TrackMax As "Track Name / Max",
	SourceMaterial As "Source",
	Aspect As "Companion [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Companion") & !contains(PageType, "Index") & !contains(SourceMaterial, "Starforged") & !contains(SourceMaterial, "Sundered Isles")
SORT PageOrder asc
```

## Tags
| Chapter Index | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_Assets Index\|Assets]]** | #Pedia/Assets/Companion | **[[_Deed Assets\|Deed Assets]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>