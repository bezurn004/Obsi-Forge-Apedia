---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases:
  - "Starsmith Assets Deeds"
PageType: AssetIndex
PageCategory: Deed
---
# [[_STRSM Assets Index|Starsmith Assets]]: Deeds
Below are the deeds included in the Starsmith collection of community created material.

> **First Deed Asset**
> [[AST_Immortal Coil|IMMORTAL COIL]]

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role (concept)]]",
	PreReqCondition As "Pre-Req"
WHERE contains(PageType, "Asset") & contains(SourceMaterial, "Starsmith") & contains(PageCategory, "Deed") & !contains(PageType, "Index")
SORT Source asc, file.name asc
```

## Tags
| Previous Section | Tags | Content Index |
|:--- |:---:| ---:|
| [[_STRSM_Companion Assets\|Starsmith Assets Companions]] | #Starsmith/Assets/Deed | [[_STRSM Assets Index\|Starsmith Assets Index]] |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>