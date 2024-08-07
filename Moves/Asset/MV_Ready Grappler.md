---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Ready Grappler (move)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Ready Grappler"
RollType: Action
RollStat: [Integrity, WIts]
Trigger: ["When you take a minute or so to ready the grappler"]
AssetPage: AST_Grappler
AssociatedAsset: GRAPPLER
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - [[MV_Lose Momentum]]
  - [[MV_Withstand Damage]]
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Ready Grappler
## Ready Grappler: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the  [[AST_Grappler|GRAPPLER]].
>**When you take a minute or so to ready the grappler...** ^trigger

> [!warning] Action Roll
>  Roll +integrity or +wits. ^action-roll

> [!challenge-strong] On strong hit
>  The grappler is charged and may be fired. ^strong-hit


> [!challenge-weak] On a weak hit
>  Charging requires extra time or focus; [[MV_Lose Momentum|Lose Momentum]] (-1).  The grappler is then charged and may be fired. ^weak-hit

> [!challenge-miss] On a miss
>  Charging fails and you must [[MV_Withstand Damage|Withstand Damage]] (-2). ^miss

## Full Description
When you take a minute or so to ready the grappler, roll +integrity or +wits. 

On a strong hit, the grappler is charged and may be fired. 

On a weak hit, charging requires extra time or focus; [[MV_Lose Momentum|Lose Momentum]] (-1). 

On a miss, charging fails and you must [[MV_Withstand Damage|Withstand Damager]] (-2).

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	Category As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT Category asc, file.name asc
```
## Tags
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[MV_Read Heart\|Read Heart (move)]]** | #Pedia/Moves/Asset | **[[MV_Shroud In Darkness\|Shroud In Darknes (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>