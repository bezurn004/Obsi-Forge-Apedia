---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases:
  - "Starsmith Assets Companions"
PageType: AssetIndex
PageCategory: Companion
PageOrder: 0
---
# [[_STRSM Assets Index|Starsmith Assets]]: Companions
Below are the companions included in the Starsmith collection of community created material.

> **First Companion Asset**
> [[AST_Crew Member|CREW MEMBER]]

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]",
	TrackMax As Health,
	Aspect As "Companion [[HBC_Aspect|Aspect]]"
WHERE contains(PageType, "Asset") & contains(SourceMaterial, "Starsmith") & contains(PageCategory, "Companion") & !contains(PageType, "Index")
SORT Source asc, file.name asc
```

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_STRSM_Path Assets\|Starsmith Assets Paths]]** | #Starsmith/Assets/Companion | **[[_STRSM_Deed Assets\|Starsmith Assets Deeds]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>