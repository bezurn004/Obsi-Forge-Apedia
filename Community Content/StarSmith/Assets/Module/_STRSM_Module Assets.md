---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases:
  - "Starsmith Assets Modules"
PageType: AssetIndex
PageCategory: Module
PageOrder: 0
---
# [[_STRSM Assets Index|Starsmith Assets]]: Modules
All modules are designed as upgrades or additions to your command vehicle, but you could reskin them to be attached to support vehicles much like the original Rover asset. For these modules, I tried to think of some of the classics that were missing (like a Holodeck!) but also modules that provide similar mechanical benefits to existing modules while coming at it from a slightly different narrative framing.

> **First Module Asset**
> [[AST_Aeroponics|AEROPONICS]]

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackLabels + " (" + TrackMax + ")"  As "Track (Amount)",
	Aspect As "[[HBC_Aspect|Moduale Aspect]]"
WHERE contains(PageType, "Asset") & contains(SourceMaterial, "Starsmith") & contains(PageCategory, "Module") & !contains(PageType, "Index")
SORT Source asc, file.name asc
```

## Tags
| Content Index | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_STRSM Assets Index\|Starsmith Assets Index]]** | #Starsmith/Assets/Modules | **[[_STRSM_Path Assets\|Starsmith Assets Paths]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>