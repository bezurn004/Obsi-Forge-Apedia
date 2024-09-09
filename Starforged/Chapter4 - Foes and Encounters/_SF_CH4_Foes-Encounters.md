---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Chapter 4 - Foes and Encounters (SF)"
PageType: "Foes and Encounters"
PageCategory: Index
PageOrder: 0
---
# [[_Starforged|IRONSWORN: STARFORGED]]
> ## CHAPTER 4
> # FOES AND ENCOUNTERS
## Contents
|  |  |
| --- |:---:|
| FORGING NPCs | [[SF_CH4_Forging NPCs\|Page 253]] |
| JOINING FORCES WITH NPCs | [[SF_CH4_Joining Forces with NPCs\|Page 254]] |
| NPC COMPONENTS | [[SF_CH4_NPC Components\|Page 256]] |
| SAMPLE NPCs | [[SF_CH4_Sample NPCs\|Page 258]] |

*251*

## Sample NPCs
_Below is a dataview query of all Denizens (NPCs). The disposition of the denizen is a categorization based on their interaction toward humanity in general._
- **Kind:** Will seek positive interactions with those they meet, so long as they do not pose a threat to their nature or kin.
- **Neutral:**  Do not concern themselves in the going on of other creatures. Protect themselves and  kin from harm or overt actions.
- **Natural:** Will seek prey in their domain, but will not overtly kill for sport or malice.
- **Aggressive:** Seeks prey when needed and will exert control or destroy any lifeforms on a whim per their nature._
```dataview
TABLE without ID
	link(file.link, DenizenName) As "Page Title",
	Summary As "Summary",
	Nature As "Nature",
	Disposition As "Disposition",
	DenizenRankNum As "Default Rank",
	SourceMaterial As "Source"
WHERE contains(PageCategory, "Denizen") & !contains(file.path, "Template") & !contains(PageCategory, "Index")
SORT PageOrder, asc
```

## Tags
| Previous Chapter | Tags | Next Chapter |
|:--- |:---:| ---:|
| **[[_SF_CH3_Gameplay In Depth\|Chapter 3 - Gameplay In Depth (SF)]]** | #Pedia/Gameplay/NPCs | **[[_SF_CH5_Index\|Oracles Summary]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>