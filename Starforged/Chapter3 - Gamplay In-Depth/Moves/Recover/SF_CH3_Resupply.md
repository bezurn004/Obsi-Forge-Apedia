---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Resupply (SF Moves)"
PageType: Move
PageCategory: Recover
PageOrder: 4

## Move
MoveName: Resupply
InlineCmd: RESUPPLY
Trigger: "When you attempt to bolster your readiness"
Approach: ["Barter or make an appeal","Threaten or sieze","Steal or swindle","Scavenge or craft"]
RollType: Action
RollStat: [Heart, Iron, Shadow, Wits]
ReferencedMoves: 
  - [[MV_Pay the Price]]
  - [[MV_Ask the Oracle]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Recover Moves|Recover]]: Resupply
## Resupply: Move Card
>[!abstract]  Trigger and Preparation
>**When you attempt to bolster your readiness...** ^trigger

> [!tip]- Group Play
> If you’re adventuring with allies, you share the same supply value. When one of you makes this move and gains supply, each of you make the same adjustment to your supply meter ^grou-play

> [!warning] Action Roll
> Envision the opportunity and your approach. If you… 
>- Barter or make an appeal: Roll +heart
>- Threaten or seize: Roll +iron
>- Steal or swindle: Roll +shadow
>- Scavenge or craft: Roll +wits ^action-roll

> [!challenge-strong] On strong hit
> Choose one:
>- If you are unprepared
>	- Clear the impact
>	- Take +1 supply
>- Otherwise, take +2 supply
>- If you are in need of a specific item or resource that can reasonably be obtained, you acquire it. Take +1 momentum. %% #ambiguous - do you also get +2 supply if you need a specific resource?%%
> > [!cite]- Narrative prompt
> > Envision the items gained in resupplying.  If this is a specific item note it in your equipment listing. ^strong-hit

> [!challenge-weak] On a weak hit
> As per a strong hit, but you must first deal with a cost, complication, or demand. 
> > [!cite]- Narrative prompt
> > Envision the nature of this obstacle.  Then proceed to take the benefits of a strong hit. ^weak-hit

> [!challenge-miss] On a miss
>  You encounter an unexpected peril, you must [[SF_CH3_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > Envision the peril and how it prevents you from gaining the resources you need. ^miss

## Full Description
This move covers various opportunities to bolster your readiness, including bartering with merchants, obtaining funds, scavenging wrecks and ruins, crafting or repurposing equipment, and pillaging cargo. Resources are scarce in the Forge, so you should ensure you have the opportunity and means to Resupply before making the move. If in doubt, [[SF_CH3_Ask the Oracle|Ask the Oracle]]. 

First, pick the stat that best represents the situation and your approach, and make the action roll. 

A strong hit gives you a choice between bolstering your general supply or acquiring a specific, helpful item or resource. Take the option that best fits your needs and intent. 

A weak offers the same benefit, but an obstacle stands in your way. Envision the concession you must make or danger you must overcome to obtain the resources. 

On a miss, you take no benefit and things get worse. You attract unwanted attention, uncover an unexpected threat, are swindled by an underhanded merchant, or waste valuable time. 

*212 CHAPTER 3: GAMEPLAY IN DEPTH*

Visiting a community is the most reliable means of bolstering your supply or obtaining unusual or valuable items. Large communities may have bustling markets where merchants peddle a variety of goods (lawful or otherwise), but even smaller outposts are often willing to lend support to a visiting spacer. 

Currencies and customs vary wildly among the settlements of the Forge, so bartering is the norm. When you Resupply within a community, envision what you seek and what you offer in trade. Data such as navigation charts and planetary scans are a valuable commodity; trailblazing spacers often visit dealers with a cache of data ready to exchange for food, fuel, ammo, and other necessities.

> [!cite]- Narrative example
> While exploring a derelict ship, you locate a cargo bay and search for worthwhile goods. Resupply +wits to see what you find. 

*213 RECOVER MOVES*

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
| **[[SF_CH3_Hearten\|Hearten (SF Moves)]]** | #Starforged/Moves/Recover | **[[SF_CH3_Repair\|Repair (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>