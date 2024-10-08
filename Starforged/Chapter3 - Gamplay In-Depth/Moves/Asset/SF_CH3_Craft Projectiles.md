---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Craft Projectiles (SF Moves)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Craft Projectiles"
RollType: Action
RollStat: Wits
Trigger: ["When you have time to craft projectiles to replenish spent Ammo..."]
AssetPage: AST_Archer
AssociatedAsset: ARCHER
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - [[SF_CH3_Sacrifice Resources]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Asset Moves|Asset]]: Craft Projectiles
## Craft Projectiles: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Archer|ARCHER]].
>**When you have time to craft projectiles to replenish spent Ammo...** ^trigger


> [!warning] Action Roll
> Roll +wits ^action-roll

> [!challenge-strong] On strong hit
> Take +6 ammo, but do not exceed the maximum. ^strong-hit


> [!challenge-weak] On a weak hit
> Take +4 ammo, but do not exceed the maximum.
> Make the move [[SF_CH3_Sacrifice Resources|Sacrifice Resources]] (-1). ^weak-hit

> [!challenge-miss] On a miss
>Take +1 ammo, but do not exceed the maximum.
> Make the move [[SF_CH3_Sacrifice Resources|Sacrifice Resources]] (-1). ^miss


## Full Description
To replenish your ammo by crafting projectiles, roll +wits. 

On a strong hit, take up to +6 ammo. 

On a weak hit, take up to +4 ammo and [[SF_CH3_Sacrifice Resources|Sacrifice Resources]]] (-1). 

On a miss, take +1 ammo and [[SF_CH3_Sacrifice Resources|Sacrifice Resources]] (-1). 

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
| **[[SF_CH3_Commemorate\|Commemorate (SF Moves)]]** | #Starforged/Moves/Asset | **[[SF_CH3_Establish Haven\|Establish Haven (SF moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>