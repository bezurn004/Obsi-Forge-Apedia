---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Characters Oracle"
PageType: Oracle
PageCategory: CharacterIndex
PageOrder: 0
---
# [[_OCL_Index|Oracles Summary]]: Characters
The oracles here provide inspiration to create aspects of characters, either NPC or player.  The oracles are condensed into related pages for concise content when peeling the onion during the character discovery process.

## [[OCL_Character-Names|Character Names Oracle]]
- [[OCL_Character-Names#Oracle: Character Given Name|Given Name]]: Character first name
- [[OCL_Character-Names#Oracle: Character Family Name|Family Name]]: Character last name
- [[OCL_Character-Names#Oracle: Character Call Sign|Call Sign]]: Character handle for communications

## [[OCL_Character-Approach|Character Approach Oracle]]
- [[OCL_Character-Approach#Oracle Character First Look {1-2}|First Look]]: appearance on first impressions
- [[OCL_Character-Approach#Oracle: Character Initial Disposition|Initial Disposition]]: character reaction upon meeting you

## [[OCL_Character-Drives|Character Drives Oracle]]
- [[OCL_Character-Drives#Oracle: Character Role|Chracter Role]]: learned skill or occupation
- [[OCL_Character-Drives#Oracle: Character Goal|Character Goal]]: driving purpose they pursue
- [[OCL_Character-Drives#Oracle Character Revealed Aspect {1-3}|Revealed Aspect]]: personality aspect revealed after deeper understanding

## Character Oracles

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Chracter Oracle Focus",
	SourceMaterial As "Source Material",
	OracleDescriptor As "Description"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Character") & !contains(PageCategory, "Index")
SORT SourceMaterial, asc & PageOrder, asc
```

## Tags
| Previous Section | Tags | Next Section | 
| :--- | :---: | ---: |
| **[[_OCL_Starships\|Starship Oracles]]** | #Pedia/Oracles/Characters | **[[_OCL_Creatures\|Creatures Oracle]]** |



<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>