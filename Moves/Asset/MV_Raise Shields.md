---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Raise Shields (move)"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: [Integrity, Wits]
Trigger: [""]
AssociatedAsset: "Shields"
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - INSERT
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Raise Shields

>[!abstract]  Context and Preparation
>This move is enabled by the [[AST_Shields|SHIELDS]].
>At any time you feel the need to raise your shields...

> [!warning] Action Roll
> Roll +integrity or your +wits.

> [!challenge-strong] On strong hit
> On a strong hit, set your shields to 4.


> [!challenge-weak] On a weak hit
> On a weak hit, make them 3.


> [!challenge-miss] On a miss
> On a miss, make them 2 but [[MV_Lose Momentum|Lose Momentum (move)]] (-1)


## Full Description
When you raise your shields, roll +your vehicle’s integrity or +wits. 

On a strong hit, set your shields to 4. 

On a weak hit, make them 3. 

On a miss, make them 2 but [[MV_Lose Momentum|Lose Momentum (move)]] (-1).

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
| **LINK** |  | **LINK** |

#Pedia/Moves/Asset 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>