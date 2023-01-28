---
Name: "Time Travel"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: [LinkMinutes, LinkHours, LinkDays]
StatValue: [4, 3, 2]
Trigger: [""]
AssociatedAsset: "Looper"
AssociatedAssetAbility: "Ability 2"
---
# [[_Moves Index|Moves]] : Time Travel
### Categories: [[_Asset Moves|Asset Moves]]
>[!abstract]  Context and Preparation
> This move is enabled on the [Looper](z_Obsi-Forge-Apedia/Assets/Paths/Looper.md) Asset. When you create a link to the current point in time, note the value of condition meters for you and your allies. You can retain only one active link.

> [!warning] Action Roll
>  If you later loop back to this moment, roll +the gap in time: 
> 	 - +4 if minutes,
> 	 - +3 if hours
> 	 - +2 if days
>  
>  You may not burn momentum on this roll.

> [!challenge-strong] On strong hit
> Return to the linked point, retain any progress, and set condition meters (except for spirit) to their original values.

> [!challenge-weak] On a weak hit
> As with a strong hit, but [[Endure Stress]] (-2)

> [!challenge-miss] On a miss
>  On a miss, as with a strong hit, but you find the timeline corrupted; [[Pay the Price]].

## Full Description
When you create a link to the current point in time, note the value of condition meters for you and your allies. You can retain only one active link. If you later loop back to this moment, roll +the gap in time: +4 if minutes, +3 if hours, or +2 if days. You may not burn momentum on this roll. 

On a strong hit, return to the linked point, retain any progress, and set condition meters (except for spirit) to their original values. 

On a weak hit, as above, but [[Endure Stress]] (-2). 

On a miss, as with a strong hit, but you find the timeline corrupted; [[Pay the Price]].

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