---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Commemorate (move)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Commemorate"
RollType: Action
RollStat: Any
Trigger: ["When you create or perform a significant artistic work as a public memorial or tribute."]
AssetPage: AST_Artist
AssociatedAsset: ARTIST
AssociatedAssetAbility: "Ability 3"
ReferencedMoves: 
  - [[MV_Pay the Price]]
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Commemorate
## Commemorate: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Artist|ARTIST]]. 
>**When you create or perform a significant artistic work as a public memorial or tribute...** ^trigger

> [!warning] Action Roll
> Roll +the stat which best represents the work’s nature ^action-roll

> [!challenge-strong] On strong hit
>  The work will stand the test of time; mark 2 ticks on your bonds legacy track ^strong-hit


> [!challenge-weak] On a weak hit
>  Its impact is short-lived; mark 1 tick on your bonds legacy track ^weak-hit


> [!challenge-miss] On a miss
> The work is ignored, misunderstood, or co-opted, and you must [[MV_Pay the Price|Pay the Price]]. ^miss


## Full Description
When you create or perform a significant artistic work as a public memorial or tribute, roll +the stat which best represents the work’s nature. 
On a strong hit, the work will stand the test of time; mark 2 ticks on your bonds legacy track. 
On a weak hit, its impact is short-lived; mark 1 tick instead of 2. 
On a miss, the work is ignored, misunderstood, or co-opted, and you must [[MV_Pay the Price|Pay the Price]].

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
| **[[MV_Blazing Meditiation\|Blazing Meditation (move)]]** | #Pedia/Moves/Asset | **[[MV_Craft Projectiles\|Craft Projectiles (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>