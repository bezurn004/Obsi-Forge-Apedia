---
Name: "Charge Grappler"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: [Integrity, WIts]
Trigger: [""]
AssociatedAsset: "Grappler"
AssociatedAssetAbility: "Ability 1"
---
# [[_Moves Index|Moves]] : Charge Grappler
### Categories: [[_Asset Moves|Asset Moves]]
>[!abstract]  Context and Preparation
>This move is enabled on the  [Grappler](z_Obsi-Forge-Apedia/Assets/Module/Grappler.md) Asset. When you take a minute or so to ready the grappler...

> [!warning] Action Roll
>  Roll +integrity or +wits.

> [!challenge-strong] On strong hit
>  The grappler is charged and may be fired.


> [!challenge-weak] On a weak hit
>  Charging requires extra time or focus; [[Lose Momentum]](-1)..  The grappler is then charged and may be fired.

> [!challenge-miss] On a miss
>  Charging fails and you must [[Withstand Damage]] (-2).

## Full Description
When you take a minute or so to ready the grappler, roll +integrity or +wits. 

On a strong hit, the grappler is charged and may be fired. 

On a weak hit, charging requires extra time or focus; Lose Momentum (-1). 

On a miss, charging fails and you must [[Withstand Damage]] (-2).

## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	Category As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT Category asc, file.name asc
```
## Tags
#Pedia/Moves/Asset 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>