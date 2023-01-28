---
Name: "Establish Haven"
PageType: Move
PageCategory: Asset
RollType: Progress
RollStat:
ProgressTrack: Legacy
Trigger: [""]
AssociatedAsset: "Vanguard"
AssociatedAssetAbility: "Ability 1"
---
# [[_Moves Index|Moves]]: Establish Haven
### Categories: [[_Asset Moves|Asset Moves]]

>[!abstract]  Context and Preparation
>To use this move requires the [Vanguard](z_Obsi-Forge-Apedia/Assets/Deed/Vanguard.md) Asset. When you seek a safe location in a remote environment.


> [!progress] Progress Roll
> Make a progress roll against your discoveries legacy track.

> [!challenge-strong] On strong hit
> You establish a haven; add +2 whenever you make a recovery move at that location.  
> > [!quote] Narrative prompt
> > Envision the nature of the haven and how it provides solace for recovery moves.

> [!challenge-weak] On a weak hit
> As with a strong hit, but add +1 when making a recovery move.
> > [!quote] Narrative prompt
> > Envision the nature of the haven and how it provides solace for recovery moves.


> [!challenge-miss] On a miss
> On a miss, you are drawn into a bad situation and must [[Pay the Price]].
> > [!quote] Narrative prompt
> > Envision the bad situation and how you are to overcome it.


## Full Description
When you seek a safe location in a remote environment, make a progress roll against your discoveries legacy track. 

On a strong hit, you establish a haven; add +2 whenever you make a [[_Recover Moves|Recover Moves]] at that location. 

On a weak hit, as above, but add +1 when making a recovery move. 

On a miss, you are drawn into a bad situation and must Pay the Price

## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Asset 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>