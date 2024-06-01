---
Alias: "Heal (move)"
PageType: Move
PageCategory: Recover
InlineCmd: HEAL
Trigger: ["When you receive medical care","When you provide medical treatment"]
RollType: Action
RollStat: [Iron, With, Heart, Wits]
Trigger: [""] 
Stats: []
---
# [[_Moves Index|Moves]] - [[_Recover Moves|Recover]]: Heal

## Heal: Move Card
>[!abstract]  Trigger and Preparation
>When you receive medical care or provide treatment...

> [!error]- Improper Usage
> NPCs who are not companions do not have a health meter. When you attempt to give them medical aid, make this move and apply the result through the fiction. They will improve, or not, as defined by the move’s outcome. 
> If you are tending to a robot companion or other machine, you should instead use the [[MV_Repair|Repair (move)]].



> [!tip]- Group Play
> Heal can be used on allies

> [!warning] Action Roll
> Envision the situation and roll. If you…
>- Receive treatment from someone (not an ally): Roll +iron
>- Mend your own wounds: Roll +iron or +wits, whichever is lower
>- Obtain treatment for a companion: Roll +heart
>- Provide care: Roll +wits

> [!challenge-strong] On strong hit
> The care is helpful for you (or the patient). 
> If wounded::
>- Take or Give +2 health 
>-  If wounded, clear the impact
>
>Otherwise Take or Give +3 health
> > [!quote] Narrative prompt
> > Envision the quality of the care that has improved the health or cleared the wound.

> [!challenge-weak] On a weak hit
> As the results on a strong hit, but the recovery costs extra time or resources. Choose one: 
>- [[MV_Lose Momentum|Lose Momentum]] (-2)
>- [[MV_Sacrifice Resources|Sacrafice Resources]] (-2)
> > [!quote] Narrative prompt
> > Envision how the loss has provided the ability for your health to improve.

> [!challenge-miss] On a miss
> The aid is ineffective and the situation worsens. [[MV_Pay the Price|Pay the Price]]
> > [!quote] Narrative prompt
> > Envision how the care has hindered and the additional cost that must now be paid.

## Full Description
When you attempt to mend physical harm or sickness, for yourself, an ally, or an NPC, make this move. You’ll also make the Heal move if you or a biological companion are given medical aid by an NPC. The result of the move determines the scope and cost of the recovery. 

Medical technology in the Forge is not magic. Healing takes effort and time, a few minutes for a quick treatment to get someone on their feet, and hours or days for more severe injuries. Envision as appropriate to the circumstances. If you face extended downtime, consider the impact on your quests. 

On a strong hit, the care is effective. If the patient (you or an ally) has the wounded impact, you may clear it. 

A weak hit offers the same benefits, but also causes a delay or consumes resources. 

A miss can mean you’ve caused or suffered harm, the patient’s condition introduces new complications, or a perilous event interrupts the care. 

> [!quote]- Narrative example
> During a planetside expedition, you suffer from exposure to toxic spores and [[MV_Endure Harm|Endure Harm]]. Your health is now precipitously low, so you find a spot to rest, break out your medkit, and roll +iron (the lower of your iron and wits) to see how you fare. 

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