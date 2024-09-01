---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Path Assets"
PageType: AssetIndex
PageCategory: Path
PageOrder: 0
---
# [[_Assets Index|Assets]]: Path Summary
> **A Note about assets and progress moves**
> Some assets include abilities which might be applied to a variety of moves. This is usually phrased as “when you make a move to [blank].” However, most asset abilities apply only to action rolls. Unless an asset specifically defines a benefit for a progress move, you may not leverage an asset ability when making a progress roll.

## Ironsworn: Starforged Path Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	Aspect As "Character [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Path") & !contains(PageType, "Index") & contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## Ironsworn: Sundered Isles Path Assets
> **First Path Asset**
> [[AST_Cannoner|CANNONEER]]

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	Aspect As "Character [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Path") & !contains(PageType, "Index") & contains(SourceMaterial, "Sundered Isles")
SORT PageOrder asc
```

## Community Content Path Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	SourceMaterial As "Source",
	Aspect As "Character [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Path") & !contains(PageType, "Index") & !contains(SourceMaterial, "Starforged") & !contains(SourceMaterial, "Sundered Isles")
SORT PageOrder asc
```

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_Module Assets\|Module Assets]]** | #Pedia/Assets/Path | **[[_Vehicle Assets\|Vehicle Assets]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>