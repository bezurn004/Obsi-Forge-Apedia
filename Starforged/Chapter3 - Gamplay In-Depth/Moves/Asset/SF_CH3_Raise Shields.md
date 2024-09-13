---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Raise Shields (SF Moves)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: Raise Sheilds
RollType: Action
RollStat: [Integrity, Wits]
Trigger: ["At any time you feel the need to raise your shields"]
AssetPage: AST_Shields
AssociatedAsset: SHIELDS
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - [[SF_CH3_Lose Momentum]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Asset Moves|Asset]]: Raise Shields
## Raise Shields: Move Card
>[!abstract]  Context and Preparation
>This move is enabled by the [[AST_Shields|SHIELDS]].
>**At any time you feel the need to raise your shields...** ^trigger

> [!warning] Action Roll
> Roll +integrity or your +wits. ^action-roll

> [!challenge-strong] On strong hit
> On a strong hit, set your shields to 4. ^strong-hit


> [!challenge-weak] On a weak hit
> On a weak hit, make them 3. ^weak-hit


> [!challenge-miss] On a miss
> On a miss, make them 2 but [[SF_CH3_Lose Momentum|Lose Momentum]] (-1) ^miss

## Full Description
When you raise your shields, roll +your vehicle’s integrity or +wits. 

On a strong hit, set your shields to 4. 

On a weak hit, make them 3. 

On a miss, make them 2 but [[SF_CH3_Lose Momentum|Lose Momentum]] (-1).

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[SF_CH3_Pull heartstrings\|Pull heartstrings (SF Moves)]]** | #Starforged/Moves/Asset | **[[SF_CH3_Read Heart\|Read Heart (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>