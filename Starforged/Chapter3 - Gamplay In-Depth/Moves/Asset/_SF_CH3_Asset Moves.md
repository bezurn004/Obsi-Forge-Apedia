---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Asset Moves (SF)"
PageType: MoveIndex
PageCategory: Asset
---

# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|In Depth]]: Asset Moves
_The Asset moves are created from the associated assets to make the presentation of abilities in-line with the moves documentation style._

#consider *Look for any source material to put here if needed*

```dataview
TABLE without ID
	link(file.link, MoveName) As "Move Name",
	"[[" + AssetPage + "|" + AssociatedAsset + "]] " + AssociatedAssetAbility As "Asset Ability",
	RollType As "Roll Type"
WHERE contains(PageType, "Move") & contains(PageCategory, "Asset") & !contains(PageType, "Index")
SORT file.name asc
```


## Tags
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[_SF_CH3_Fate Moves\|Fate Moves (SF)]]** | #Starforged/Moves/Asset  | **[[SF_CH3_Clocks\|Clocks (SF In Depth)]]** |


<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>