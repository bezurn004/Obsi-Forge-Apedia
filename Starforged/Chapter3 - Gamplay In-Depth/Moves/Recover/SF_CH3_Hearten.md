---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Hearten (SF Moves)"
PageType: Move
PageCategory: Recover
PageOrder: 3

## Move
MoveName: Hearten
InlineCmd: HEARTEN
Trigger: ["When you socialize","When you share intimacy","When you find a moment of peace"]
RollType: Action
RollStat: Heart
ReferencedMoves: 
  - [[SF_CH3_Sojourn]]
  - [[SF_CH3_Lose Momentum]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Recover Moves|Recover]]: Hearten
## Hearten: Move Card
>[!abstract]  Trigger and Preparation
>**When you socialize, share intimacy, or find a moment of peace...** ^trigger

> [!tip]- Group Play
> If you Hearten by building your relationship with an ally, such as sharing something of yourself or providing mutual emotional support, one or both of you may make the move and roll the dice. 
>- If the results are wildly divergent (such as a strong hit for one and a miss for the other), consider how the two of you come away from this time together with a different understanding or reaction. 
>- If an ally is instead focusing on providing emotional support for another member of the team, they can make the [[SF_CH3_Aid Your Ally|Aid Your Ally]] to bolster that character’s attempt to Hearten ^group-play

> [!warning] Action Roll
> Roll +heart ^action-roll

> [!challenge-strong] On strong hit
> You find companionship or comfort and your spirit is strengthened. 
>- If you make this move as you [[SF_CH3_Sojourn|Sojourn]], take +1 more
>- If you are shaken
>	- Clear the impact
>	- Take +1 spirit. 
>- Otherwise, take +2 spirit. 
> > [!cite]- Narrative prompt
> > Envision how to time spent offers your spirit recovery. ^strong-hit

> [!challenge-weak] On a weak hit
> As on a strong hit, but this indulgence is fleeting. Envision an interruption, complication, or inner conflict. 
> [[SF_CH3_Lose Momentum|Lose Momentum]] (-1)
> > [!cite]- Narrative prompt
> > Envision how the time spent offers some respite, but what has interrupted your full recovery ^weak-hit

> [!challenge-miss] On a miss
> You take no comfort and the situation worsens, [[SF_CH3_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > Envision how your attempt to hearten has instead caused more distress. ^miss

## Full Description
When isolation, stress, fear, regret, heartache, and misfortune have taken their toll, make this move to renew your mental energy and fortitude. 

First, envision the opportunity to Hearten. This might mean spending meaningful time with a connection or ally, seeking opportunities to socialize or indulge within a community, finding solitary comfort through prayer or meditation, or gaining inspiration through natural wonders. 

On a strong hit, you gain spirit. If you have the shaken impact, you may clear it. 

On a weak hit, you recover, but this interlude is bittersweet and introduces new complications or emotional unrest. Envision what happens and Lose Momentum to represent this setback. 

On a miss, your attempt to find comfort is undone by a dramatic event, emotional conflict, lingering trauma, or dire realization. 

> [!cite]- Narrative example
> The bar at Paxton Depot is a popular watering hole for spacers in the sector, so you stop by to swap stories, pick up the latest rumors, and cheer yourself up with a few drinks. You roll to Hearten, and score a weak hit. You take the boost to your spirit, but envision the ill-timed entrance of a local merchant you once conned. 

*211 RECOVER MOVES*

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, MoveName) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(ReferencedMoves, this.file.name) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[SF_CH3_Heal\|Heal (SF Moves)]]** | #Starforged/Moves/Recover | **[[SF_CH3_Resupply\|Resupply (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>