---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Loop Back (move)"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: [LinkMinutes, LinkHours, LinkDays]
StatValue: [4, 3, 2]
Trigger: [""]
AssociatedAsset: "Looper"
AssociatedAssetAbility: "Ability 2"
ReferencedMoves: 
  - INSERT
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Loop Back

## Move Card
>[!abstract]  Trigger and Preparation
> This move is enabled by the [[AST_Looper|LOOPER]]. 
> When you create a link to the current point in time, note the value of condition meters for you and your allies. You can retain only one active link.

> [!oracle] The Gap Roll
>  If you later loop back to this moment, roll +the gap in time: 
> 	 - +4 if minutes
> 	 - +3 if hours
> 	 - +2 if days
> 	 - +1 if weeks
> 	 - +0 if months
>  
>  You may not burn momentum on this roll.

> [!challenge-strong] On strong hit
> Return to the linked point, retain any progress, and set condition meters (except for spirit) to their original values.

> [!challenge-weak] On a weak hit
> As with a strong hit, but [[MV_Endure Stress|Endure Stress]] (-2)

> [!challenge-miss] On a miss
>  On a miss, as with a strong hit, but you find the timeline corrupted; [[MV_Pay the Price|Pay the Price (move)]].

## Full Description
When you create a link to the current point in time, note the value of condition meters for you and your allies. You can retain only one active link. If you later loop back to this moment, roll +the gap in time: +4 if minutes, +3 if hours, +2 if days, +1 if weeks, +0 if months. You may not burn momentum on this roll. 

On a strong hit, return to the linked point, retain any progress, and set condition meters (except for spirit) to their original values. 

On a weak hit, as above, but [[MV_Endure Stress|Endure Stress]] (-2). 

On a miss, as with a strong hit, but you find the timeline corrupted; [[MV_Pay the Price|Pay the Price (move)]].

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