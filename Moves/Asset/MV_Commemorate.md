---
Alias: "Commemorate (move)"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: Any
Trigger: [""]
AssociatedAsset: "Grappler"
AssociatedAssetAbility: "Ability 3"
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Commemorate

## Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Artist|Artist (asset)]]. 
>When you create or perform a significant artistic work as a public memorial or tribute...

> [!warning] Action Roll
> Roll +the stat which best represents the work’s nature

> [!challenge-strong] On strong hit
>  The work will stand the test of time; mark 2 ticks on your bonds legacy track


> [!challenge-weak] On a weak hit
>  Its impact is short-lived; mark 1 tick on your bonds legacy track


> [!challenge-miss] On a miss
> The work is ignored, misunderstood, or co-opted, and you must [[MV_Pay the Price|Pay the Price (move)]].


## Full Description
When you create or perform a significant artistic work as a public memorial or tribute, roll +the stat which best represents the work’s nature. 
On a strong hit, the work will stand the test of time; mark 2 ticks on your bonds legacy track. 
On a weak hit, its impact is short-lived; mark 1 tick instead of 2. 
On a miss, the work is ignored, misunderstood, or co-opted, and you must [[MV_Pay the Price|Pay the Price (move)]].

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