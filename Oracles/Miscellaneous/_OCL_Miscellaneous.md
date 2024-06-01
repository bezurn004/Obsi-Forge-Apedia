---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Miscellaneous Oracles"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Miscellaneous
The oracles below do not fit into any particular category.

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Location Theme Oracle Focus",
	OracleDescriptor As "Description",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(Oracle, "Misc") & !contains(PageCategory, "Index") & !contains(file.path, "Template")
SORT OracleFocus, asc
```

## Tags
#Pedia/Oracles 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>