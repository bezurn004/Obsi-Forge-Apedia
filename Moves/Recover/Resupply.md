---
Name: "Resupply"
PageType: Move
PageCategory: Recover
InlineCmd: RESUPPLY
RollType: Action
RollStat: [Heart, Iron, Shadow, Wits]
Trigger: [""] 
Stats: []
---
# [[_Moves Index|Moves]]: Resupply
### Categories: [[_Recover Moves|Recover Moves]]
>[!abstract]  Context and Preparation
>When you attempt to bolster your readiness...

> [!tip]- Group Play
> If you’re adventuring with allies, you share the same supply value. When one of you makes this move and gains supply, each of you make the same adjustment to your supply meter

> [!warning] Action Roll
> Envision the opportunity and your approach. If you… 
>- Barter or make an appeal: Roll +heart
>- Threaten or seize: Roll +iron
>- Steal or swindle: Roll +shadow
>- Scavenge or craft: Roll +wits

> [!challenge-strong] On strong hit
> Choose one:
>- If you are unprepared
>	- Clear the impact
>	- Take +1 supply
>- Otherwise, take +2 supply
>- If you are in need of a specific item or resource that can reasonably be obtained, you acquire it. Take +1 momentum.
> > [!quote] Narrative prompt
> > Envision the items gained in resupplying.  If this is a specific item note it in your equipment listing.

> [!challenge-weak] On a weak hit
> As per a strong hit, but you must first deal with a cost, complication, or demand. 
> > [!quote] Narrative prompt
> > Envision the nature of this obstacle.  Then proceed to take the benefits of a strong hit.

> [!challenge-miss] On a miss
>  You encounter an unexpected peril, you must [[Pay the Price]].
> > [!quote] Narrative prompt
> > Envision the peril and how it prevents you from gaining the resources you need.

## Full Description
This move covers various opportunities to bolster your readiness, including bartering with merchants, obtaining funds, scavenging wrecks and ruins, crafting or repurposing equipment, and pillaging cargo. Resources are scarce in the Forge, so you should ensure you have the opportunity and means to Resupply before making the move. If in doubt, Ask the Oracle. 

First, pick the stat that best represents the situation and your approach, and make the action roll. 

A strong hit gives you a choice between bolstering your general supply or acquiring a specific, helpful item or resource. Take the option that best fits your needs and intent. 

A weak offers the same benefit, but an obstacle stands in your way. Envision the concession you must make or danger you must overcome to obtain the resources. 

On a miss, you take no benefit and things get worse. You attract unwanted attention, uncover an unexpected threat, are swindled by an underhanded merchant, or waste valuable time. 

Visiting a community is the most reliable means of bolstering your supply or obtaining unusual or valuable items. Large communities may have bustling markets where merchants peddle a variety of goods (lawful or otherwise), but even smaller outposts are often willing to lend support to a visiting spacer. 

Currencies and customs vary wildly among the settlements of the Forge, so bartering is the norm. When you Resupply within a community, envision what you seek and what you offer in trade. Data such as navigation charts and planetary scans are a valuable commodity; trailblazing spacers often visit dealers with a cache of data ready to exchange for food, fuel, ammo, and other necessities.

> [!quote]- Narrative example
> While exploring a derelict ship, you locate a cargo bay and search for worthwhile goods. Resupply +wits to see what you find. 

## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, title) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Recover 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>