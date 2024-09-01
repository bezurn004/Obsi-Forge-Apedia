---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Establish Haven (move)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Establish Haven"
RollType: Progress
RollStat:
ProgressTrack: Legacy
Trigger: ["When you seek a safe location in a remote environment"]
AssetPage: AST_Vanguard
AssociatedAsset: VANGUARD
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - [[MV_Sojourn]]
  - [[MV_Heal]]
  - [[MV_Hearten]]
  - [[MV_Resupply]]
  - [[MV_Repair]]
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Establish Haven
## Establish Haven: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Vanguard|VANGUARD]].
>**When you seek a safe location in a remote environment...** ^trigger


> [!progress] Progress Roll
> Make a progress roll against your discoveries legacy track. ^progress-roll

> [!challenge-strong] On strong hit
> You establish a haven; add +2 whenever you make a [[_Recover Moves|Recover Moves]] at that location.  
> > [!cite]- Narrative prompt
> > Envision the nature of the haven and how it provides solace for [[_Recover Moves|Recover Moves]]. ^strong-hit

> [!challenge-weak] On a weak hit
> As with a strong hit, but add +1 when making a [[_Recover Moves|Recover Moves]].
> > [!cite]- Narrative prompt
> > Envision the nature of the haven and how it provides solace for [[_Recover Moves|Recover Moves]]. ^weak-hit

> [!challenge-miss] On a miss
> On a miss, you are drawn into a bad situation and must [[MV_Pay the Price|Pay the Price (move)]].
> > [!cite]- Narrative prompt
> > Envision the bad situation and how you are to overcome it. ^miss

## Full Description
When you seek a safe location in a remote environment, make a progress roll against your discoveries legacy track. 

On a strong hit, you establish a haven; add +2 whenever you make a [[_Recover Moves|Recover Moves]] at that location. 

On a weak hit, as above, but add +1 when making a [[_Recover Moves|Recover Moves]]. 

On a miss, you are drawn into a bad situation and must [[MV_Pay the Price|Pay the Price (move)]]

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
| **[[MV_Craft Projectiles\|Craft Projectiles (move)]]** | #Pedia/Moves/Asset | **[[MV_Loop Back\|Loop Back (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>