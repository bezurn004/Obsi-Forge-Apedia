---
Alias: "Hearten (move)"
PageType: Move
PageCategory: Recover
InlineCmd: HEARTEN
Trigger: ["When you socialize","When you share intimacy","When you find a moment of peace"]
RollType: Action
RollStat: Heart
---
# [[_Moves Index|Moves]] - [[_Recover Moves|Recover]]: Hearten

## Hearten: Move Card
>[!abstract]  Trigger and Preparation
>When you socialize, share intimacy, or find a moment of peace...

> [!tip]- Group Play
> If you Hearten by building your relationship with an ally, such as sharing something of yourself or providing mutual emotional support, one or both of you may make the move and roll the dice. 
>- If the results are wildly divergent (such as a strong hit for one and a miss for the other), consider how the two of you come away from this time together with a different understanding or reaction. 
>- If an ally is instead focusing on providing emotional support for another member of the team, they can make the [[MV_Aid Your Ally|Aid Your Ally]] to bolster that character’s attempt to Hearten

> [!warning] Action Roll
> Roll +heart

> [!challenge-strong] On strong hit
> You find companionship or comfort and your spirit is strengthened. 
> If you make this move as you [[MV_Sojourn|Sojourn]], take +1 more
> If you are shaken
>- Clear the impact
>- Take +1 spirit. 
>
> Otherwise, take +2 spirit. 
> 
> > [!quote] Narrative prompt
> > Envision how to time spent offers your spirit recovery.

> [!challenge-weak] On a weak hit
> As on a strong hit, but this indulgence is fleeting. Envision an interruption, complication, or inner conflict. 
> [[MV_Lose Momentum|Lose Momentum]] (-1)
> > [!quote] Narrative prompt
> > Envision how the time spent offers some respite, but what has interrupted your full recovery

> [!challenge-miss] On a miss
> You take no comfort and the situation worsens, [[MV_Pay the Price|Pay the Price]].
> > [!quote] Narrative prompt
> > Envision how your attempt to hearten has instead caused more distress.

## Full Description
When isolation, stress, fear, regret, heartache, and misfortune have taken their toll, make this move to renew your mental energy and fortitude. 

First, envision the opportunity to Hearten. This might mean spending meaningful time with a connection or ally, seeking opportunities to socialize or indulge within a community, finding solitary comfort through prayer or meditation, or gaining inspiration through natural wonders. 

On a strong hit, you gain spirit. If you have the shaken impact, you may clear it. 

On a weak hit, you recover, but this interlude is bittersweet and introduces new complications or emotional unrest. Envision what happens and Lose Momentum to represent this setback. 

On a miss, your attempt to find comfort is undone by a dramatic event, emotional conflict, lingering trauma, or dire realization. 

> [!quote]- Narrative example
> The bar at Paxton Depot is a popular watering hole for spacers in the sector, so you stop by to swap stories, pick up the latest rumors, and cheer yourself up with a few drinks. You roll to Hearten, and score a weak hit. You take the boost to your spirit, but envision the ill-timed entrance of a local merchant you once conned. 

## Related Assets
```dataview
TABLE without ID
	link(file.link, alias) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, alias) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Recover 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>