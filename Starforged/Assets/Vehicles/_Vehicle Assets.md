---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Vehicle Assets"
PageType: AssetIndex
PageCategory: Vehicle
PageOrder: 0
---
# [[_Assets Index|Assets]]: Vehicle Summary
> **A Note about assets and progress moves**
> Some assets include abilities which might be applied to a variety of moves. This is usually phrased as “when you make a move to [blank].” However, most asset abilities apply only to action rolls. Unless an asset specifically defines a benefit for a progress move, you may not leverage an asset ability when making a progress roll.

For more information, see the gameplay rules for [[GB_Assets#Support Vehicles|Vehicle Assets]].

## Ironsworn: Starforged Vehicle Assets
> **First Vehicle Asset**
> [[AST_Starship|STARSHIP]]
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role (concept)]]",
	TrackMax As "Integrity (Max)",
	Aspect As "Vehicle [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Vehicle") & !contains(PageType, "Index") & contains(SourceMaterial, "Starforged")
SORT PageCategory asc, file.name asc
```

## Ironsworn: Sundered Isles Vehicle Assets
> **First Vehicle Asset**
> [[AST_Sailing Ship|SAILING SHIP]]
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role (concept)]]",
	TrackMax As "Integrity (Max)",
	Aspect As "Vehicle [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Vehicle") & !contains(PageType, "Index") & contains(SourceMaterial, "Sundered Isles")
SORT PageOrder, asc
```


## Community Content Vehicle Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role (concept)]]",
	TrackMax As "Integrity (Max)",
	Aspect As "Vehicle [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(PageCategory, "Vehicle") & !contains(PageType, "Index") & !contains(SourceMaterial, "Starforged") & !contains(SourceMaterial, "Sundered Isles")
SORT PageOrder asc
```

## Tags
| Previous Section | Tags | Chapter Page |
|:--- |:---:| ---:|
| **[[_Path Assets\|Path Assets]]** | #Pedia/Assets/SupportVehicle | **[[_Assets Index\|Assets]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>