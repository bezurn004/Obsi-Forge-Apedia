---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Blazing Meditation (SF Moves)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Blazing Meditation"
RollType: Action
RollStat: Spirit
Trigger: [""]
AssetPage: AST_Firebrand
AssociatedAsset: FIREBRAND
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - [[SF_CH3_Endure Harm]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Asset Moves|Asset]]: Blazing Meditation
## Blazing Meditation: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Firebrand|FIREBRAND]].
>**When you rest and meditate to gather this energy...** ^trigger

> [!warning] Action Roll
> Roll +spirit ^action-roll

> [!challenge-strong] On strong hit
>  Take up to +3 fire. ^strong-hit

> [!challenge-weak] On a weak hit
> Take +2 fire. ^weak-hit

> [!challenge-miss] On a miss
> Take +2 fire but [[SF_CH3_Endure Harm|Endure Harm]] (-2). ^miss

## Full Description
When you rest and meditate to gather this energy, roll +spirit. 

On a strong hit, take up to +3 fire. 

On a weak hit, take +2. 

On a miss, take +2 fire but [[SF_CH3_Endure Harm|Endure Harm]] (-2).

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Section Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[_SF_CH3_Asset Moves\|Asset Moves]]** | #Starforged/Moves/Asset | **[[SF_CH3_Commemorate\|Commemorate (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>

