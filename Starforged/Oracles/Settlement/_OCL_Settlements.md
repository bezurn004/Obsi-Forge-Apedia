---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Settlements Oracle"
PageType: Oracle
PageCategory: SettlementIndex
PageOrder: 0
---
# [[_OCL_Index|Oracles Summary]]: Settlements Oracle
Listed are the Oracles used to generate settlements during your travels through the Forge.

## [[OCL_Settle-Creation|Settlement Creation Oracle]]
To begin creating a settlement from scratch, start with this page which contains the **Location** a settlement and its rough **Population** based its region in the Forge. If you are generating a settlement as a prompt from another Oracle or source, you may already know one or both of these questions.

## [[OCL_Settle-Name|Settlement Name Oracle]]
Once a location and rough population are chosen, give the settlement a **Name**. Optionally, add a **Name Tag** to enhance the meaning for the settlement.

## [[OCL_Settle_Approach|Settlement Approach Oracle]]
After the settlement is created, generally you can stop there. Only when you begin to interact directly or indirectly slowly introduce new aspects of the settlement. As you learn about its **First Look**, your **Initial Contact ** as you approach, and the ruling **Authority** of the settlement.

## [[OCL_Settle-Concerns|Settlement Councerns Oracle]]
As you spend more time with a settlement and get involved with its populace, start to get an idea of their concerns. These are the **Projects** they undertake to sustain themselves and the lurking **Troubles** that arise from life in the perilous Forge.

## Settlement Oracles

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Settlement Oracle Focus",
	SourceMaterial As "Source Material",
	OracleDescriptor As "Description"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Settlement") & !contains(PageCategory, "Index")
SORT SourceMaterial, asc AND PageOrder, asc
```

## Tags
| Previous Section | Tags | Next Section | 
| :--- | :---: | ---: |
| **[[_OCL_Planets\|Planet Oracles]]** | #Pedia/Oracles/Settlements | **[[_OCL_Starships\|Starship Oracles]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>