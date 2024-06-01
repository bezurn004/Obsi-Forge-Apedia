---
Alias: "Sojourn (move)"
PageType: Move
PageCategory: Recover
InlineCmd: SOJOURN
Trigger: "When you spend time recovering within a community"
RollType: Action
RollStat: Heart
---
# [[_Moves Index|Moves]] - [[_Recover Moves|Recover]]: Sojourn

## Sojourn: Move Card
>[!abstract]  Trigger and Preparation
>When you spend time recovering within a community...

> [!tip]- Group Play
> You and your allies take the benefits from a hit on this move.  On a miss, if you [[MV_Pay the Price|Pay the Price]], only you take this cost, but the group takes the narrative consequence.

> [!warning] Action Roll
> Roll +heart

> [!challenge-strong] On strong hit
>  This is a safe refuge. You and your allies may each choose two recover moves: 
>- [[MV_Heal|Heal]]
>- [[MV_Hearten|Hearten]]
>- [[MV_Repair|Repair]]
>- [[MV_Resupply|Resupply]]
>Instead of rolling, assume an automatic strong hit for each. 
>An individual move can be taken more than once.
> > [!quote] Narrative prompt
> > Envision how you recoup in this community while taking the chosen respite.

> [!challenge-weak] On a weak hit
> You and your allies each make one [[_Recover Moves|Recover Move]] instead of two, with no more than three moves total among the group.
> > [!quote] Narrative prompt
> > Envision how you recoup, but note that why time is short or resources are strained.

> [!challenge-miss] On a miss
>  Choose one:
>- The community needs your help, or makes a costly demand in exchange for safe harbor. Envision what they ask of you. If you do it, or [[MV_Swear an Iron Vow|Swear an Iron Vow]] to see it done, resolve this move as a strong hit.
>- You find no relief, and the situation grows worse. [[MV_Pay the Price|Pay the Price]].
> > [!quote] Narrative prompt
> > Envision either taking on a new quest or why this community turns away your request for aid.

## Full Description
Communities stand as an oasis within the perilous depths of the Forge. They range from tiny frontier outposts with a handful of residents, to spacefaring merchant caravans, to sprawling stations with many thousands of inhabitants. When you rest, refit, and share fellowship within a community that is willing and able to help you, make this move. 

On a strong hit, you and your allies may each choose two recover moves. Instead of making an action roll for those moves, take an automatic strong hit. Envision this as socializing, bartering goods or data, spending funds, calling in favors, or simply asking for help. 

On a weak hit, you’ll take the same benefit for one [[_Recover Moves|Recover Move]]. 

On a miss, you have a choice. If you accept the burden of a trouble or demand, resolve this move as if you rolled a strong hit. Otherwise, something prevents you from finding relief. Your background or nature alienates others. Resources are too scarce to share. A sudden, perilous event awaits you. Envision what happens and [[MV_Pay the Price|Pay the Price]]. 

Sojourn requires hours or days, depending on your current circumstances and level of aid and recovery required. You can envision other interactions and perform additional moves during your layover. Sojourn is an overarching move that sets the tone for your visit and defines the ease of your recovery; it is not the only action you can take. 

When you visit a community, you should envision what makes it unique, what challenges the people face, and what opportunities or dangers await you. If you need inspiration, [[MV_Ask the Oracle|Ask the Oracle]]. Make this move only once when laying over within a community.


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