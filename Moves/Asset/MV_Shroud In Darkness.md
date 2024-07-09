---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Shroud In Darknes (move)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Shroud In Darkness"
RollType: None
RollStat: Shadow
Trigger: ["When you expand your veil to immerse your surroundings in darkness"]
AssetPage: AST_Shade
AssociatedAsset: SHADE
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - INSERT
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Shroud In Darkness
## Shroud In Darkness: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Shade|SHADE]].
>**When you expand your veil to immerse your surroundings in darkness...** ^trigger

> [!warning] Action Roll
> Roll +shadow ^action-roll

> [!challenge-strong] On strong hit
>  On a strong hit, the darkness extends to all adjacent spaces. ^strong-hit

> [!challenge-weak] On a weak hit
> On a weak hit, only your immediate surroundings are made dark. ^weak-hit

> [!challenge-miss] On a miss
>  On a miss, you fail and draw unwanted attention. ^miss

## Full Description
When you expand your veil to immerse your surroundings in darkness, roll +shadow. 

On a strong hit, the darkness extends to all adjacent spaces. 

On a weak hit, only your immediate surroundings are made dark. 

On a miss, you fail and draw unwanted attention.

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Previous Page | Tags | Chapter Page |
|:--- |:---:| ---:|
| **[[MV_Ready Grappler\|Ready Grappler (move)]]** | #Pedia/Moves/Asset | **[[_Moves Index\|Gameplay In Depth]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>