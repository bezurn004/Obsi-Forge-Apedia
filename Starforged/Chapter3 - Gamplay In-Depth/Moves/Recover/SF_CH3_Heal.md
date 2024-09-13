---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Heal (SF Moves)"
PageType: Move
PageCategory: Recover
PageOrder: 2

## Move
MoveName: "Heal"
InlineCmd: HEAL
Trigger: ["When you receive medical care","When you provide medical treatment"]
Approach: ["Receive treatment from someone (not an ally)","Mend your own wounds","Obtain treatment for a companion","Provide care"]
RollType: Action
RollStat: [Iron, With, Heart, Wits]
Trigger: [""] 
Stats: []
ReferencedMoves: 
  - [[SF_CH3_Lose Momentum]]
  - [[SF_CH3_Sacrifice Resources]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Recover Moves|Recover]]: Heal
## Heal: Move Card
>[!abstract]  Trigger and Preparation
>**When you receive medical care or provide treatment...** ^trigger

> [!error]- Improper Usage
> NPCs who are not companions do not have a health meter. When you attempt to give them medical aid, make this move and apply the result through the fiction. They will improve, or not, as defined by the move’s outcome. 
> If you are tending to a robot companion or other machine, you should instead use the [[SF_CH3_Repair|Repair]]. ^improper

> [!tip]- Group Play
> Heal can be used on allies ^grou-play

> [!warning] Action Roll
> Envision the situation and roll. If you…
>- Receive treatment from someone (not an ally): Roll +iron
>- Mend your own wounds: Roll +iron or +wits, whichever is lower
>- Obtain treatment for a companion: Roll +heart
>- Provide care: Roll +wits ^action-roll

> [!challenge-strong] On strong hit
> The care is helpful for you (or the patient). 
>- If wounded::
>	- Take or Give +2 health 
>	- Clear the impact
>- Otherwise Take or Give +3 health
> > [!cite]- Narrative prompt
> > Envision the quality of the care that has improved the health or cleared the wound. ^strong-hit

> [!challenge-weak] On a weak hit
> As the results on a strong hit, but the recovery costs extra time or resources. Choose one: 
>- [[SF_CH3_Lose Momentum|Lose Momentum]] (-2)
>- [[SF_CH3_Sacrifice Resources|Sacrafice Resources]] (-2)
> > [!cite]- Narrative prompt
> > Envision how the loss has provided the ability for your health to improve. ^weak-hit

> [!challenge-miss] On a miss
> The aid is ineffective and the situation worsens. [[SF_CH3_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > Envision how the care has hindered and the additional cost that must now be paid. ^miss

## Full Description
When you attempt to mend physical harm or sickness, for yourself, an ally, or an NPC, make this move. You’ll also make the Heal move if you or a biological companion are given medical aid by an NPC. The result of the move determines the scope and cost of the recovery. 

Medical technology in the Forge is not magic. Healing takes effort and time, a few minutes for a quick treatment to get someone on their feet, and hours or days for more severe injuries. Envision as appropriate to the circumstances. If you face extended downtime, consider the impact on your quests. 

On a strong hit, the care is effective. If the patient (you or an ally) has the ==[[SF_CH1_Impacts#Misfortunes|wounded]]== impact, you may clear it. 

A weak hit offers the same benefits, but also causes a delay or consumes resources. 

A miss can mean you’ve caused or suffered harm, the patient’s condition introduces new complications, or a perilous event interrupts the care. 

> [!cite]- Narrative example
> During a planetside expedition, you suffer from exposure to toxic spores and [[SF_CH3_Endure Harm|Endure Harm]]. Your health is now precipitously low, so you find a spot to rest, break out your medkit, and roll +iron (the lower of your iron and wits) to see how you fare. 

*210 CHAPTER 3: GAMEPLAY IN DEPTH*

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
| **[[SF_CH3_Sojourn\|Sojourn (SF Moves)]]** |#Starforged/Moves/Recover | **[[SF_CH3_Hearten\|Hearten (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>