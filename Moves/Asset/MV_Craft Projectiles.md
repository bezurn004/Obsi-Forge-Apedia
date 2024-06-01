---
Alias: "Craft Projectiles (move)"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: Wits
Trigger: [""]
AssociatedAsset: "Archer"
AssociatedAssetAbility: "Ability 1"
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Craft Projectiles
## Move Card

>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Archer|Archer (asset)]].
>When you have time to craft projectiles to replenish spent Ammo...


> [!warning] Action Roll
> Roll +wits

> [!challenge-strong] On strong hit
> Take +6 ammo, but do not exceed the maximum.


> [!challenge-weak] On a weak hit
> Take +4 ammo, but do not exceed the maximum.
> Make the move [[MV_Sacrifice Resources|Sacrifice Resources]] (-1).

> [!challenge-miss] On a miss
>Take +1 ammo, but do not exceed the maximum.
> Make the move [[MV_Sacrifice Resources|Sacrifice Resources]] (-1).


## Full Description
To replenish your ammo by crafting projectiles, roll +wits. 

On a strong hit, take up to +6 ammo. 

On a weak hit, take up to +4 ammo and [[MV_Sacrifice Resources|Sacrifice Resources]]] (-1). 

On a miss, take +1 ammo and [[MV_Sacrifice Resources|Sacrifice Resources]] (-1). 

## Related Assets
```dataview
TABLE without ID
	link(file.link, alias) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```
## Tags
#Pedia/Moves/Asset

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>