---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases:
  - "Starsmith Assets Paths"
PageType: AssetIndex
PageCategory: Path
PageOrder: 0
---
# [[_STRSM Assets Index|Starsmith Assets]]: Paths
Below are the paths included in the Starsmith collection of community created material.

> **First Path Asset**
> [[AST_Constable\|CONSTABLE]]

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role (concept)]]",
	Aspect As "[[HBC_Aspect|Aspect (concept)]]"
WHERE contains(PageType, "Asset") & contains(SourceMaterial, "Starsmith") & contains(PageCategory, "Path") & !contains(PageType, "Index")
SORT Source asc, file.name asc
```

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[_STRSM_Module Assets\|Starsmith Assets Modules]]** | #Starsmith/Assets/Path | **[[_STRSM_Companion Assets\|Starsmith Assets Companions]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>