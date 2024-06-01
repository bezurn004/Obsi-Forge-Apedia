---
Alias: "Establish Haven (move)"
PageType: Move
PageCategory: Asset
RollType: Progress
RollStat:
ProgressTrack: Legacy
Trigger: [""]
AssociatedAsset: "Vanguard"
AssociatedAssetAbility: "Ability 1"
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Establish Haven

## Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Vanguard|Vanguard (asset)]].
>When you seek a safe location in a remote environment...


> [!progress] Progress Roll
> Make a progress roll against your discoveries legacy track.

> [!challenge-strong] On strong hit
> You establish a haven; add +2 whenever you make a[[_Recover Moves|Recover Moves] at that location.  
> > [!quote] Narrative prompt
> > Envision the nature of the haven and how it provides solace for [[_Recover Moves|Recover Moves]].

> [!challenge-weak] On a weak hit
> As with a strong hit, but add +1 when making a [[_Recover Moves|Recover Moves]].
> > [!quote] Narrative prompt
> > Envision the nature of the haven and how it provides solace for [[_Recover Moves|Recover Moves]].


> [!challenge-miss] On a miss
> On a miss, you are drawn into a bad situation and must [[MV_Pay the Price|Pay the Price (move)]].
> > [!quote] Narrative prompt
> > Envision the bad situation and how you are to overcome it.


## Full Description
When you seek a safe location in a remote environment, make a progress roll against your discoveries legacy track. 

On a strong hit, you establish a haven; add +2 whenever you make a [[_Recover Moves|Recover Moves]] at that location. 

On a weak hit, as above, but add +1 when making a [[_Recover Moves|Recover Moves]]. 

On a miss, you are drawn into a bad situation and must [[MV_Pay the Price|Pay the Price (move)]]

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