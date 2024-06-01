---
Alias: "Companion Takes a Hit (move)"
PageType: Move
PageCategory: Suffer
InlineCmd: CTH
RollType: Action
RollStat: CompanionHealth
Trigger: [""] 
Stats: []
---
# [[_Moves Index|Moves]] - [[_Suffer Moves|Suffer]]: Companion Takes a Hit

## Companion Takes A Hit: Move Card
>[!abstract]  Trigger and Preparation
>When your companion faces physical hardship...

> [!warning] Action Roll
> Your companion will suffer
>- For minor harm, suffer -1
>- For serious harm, suffer -2
>- For major harm, suffer -3
> If your companion’s health is 0, [[MV_Lose Momentum|Lose Momentum]] equal to any remaining harm
> 
> Then, if *their health is 0* or *you choose to test their resilience*, roll +your companion’s health

> [!challenge-strong] On strong hit
> Give them +1 health
> > [!quote] Narrative prompt
> > Your companion rallies, envision their reaction and what happens next.

> [!challenge-weak] On a weak hit
> Choose one:
>- If your companion’s health is not 0, you may [[MV_Lose Momentum|Lose Momentum]] (-1) and give them +1 health.
>- Otherwise, they press on
> > [!quote] Narrative prompt
> > Envision how you both press on.

> [!challenge-miss] On a miss
> Choose one:
>- They suffer an additional -1 health
>- You [[MV_Lose Momentum|Lose Momentum]] (-2)
>If your companion’s health is 0, they are out of action until given aid. 
>If their health is 0 and you rolled a miss with a match on this move, they are dead or destroyed; discard the asset.
> > [!quote] Narrative prompt
> > Envision the further cost to your companion.

## Full Description
A [[GP_Assets#Companions|companion]] is a category of assets, a creature, robot, or other helper, that supports you on your adventures. When a companion is exposed to physical hardship, make this move. 

When you must [[MV_Pay the Price|Pay the Price]], you can make the Companion Takes a Hit move if harm to your companion is a fitting outcome of the current situation. Also, moves and assets can prompt you to make this move as a cost or concession, and may indicate a specific amount of harm to apply, phrased as “Companion Takes a Hit (-X).” 

Companion asset cards have a health meter. When you make this move, reduce your companion’s health by the amount of harm suffered: 
- Minor (-1):  Unarmed brawl; taking hits from a simple weapon; bumps and bruises; lesser creature attack; tiring effort; mild sickness; exposure to an unhealthy environment.
- Serious (-2): Powerful unarmed assault; forceful impact; small arms fire; deadly creature attack; draining effort; lingering sickness; exposure to a toxic environment.
- Major (-3): Heavy weaponry; mighty creature attack; stunning injury; exhausting effort; exposure to a deadly environment.
If in doubt, make it serious. 

If your companion’s health is reduced to 0, or was already at 0, you must [[MV_Lose Momentum|Lose Momentum]] and apply any remaining -health to your momentum meter. For example, if they were at 1 health and suffer major harm (-3), reduce the integrity to 0 and apply the remaining -2 to momentum. 

As with [[MV_Endure Harm|Endure Harm]], you can make an action roll to resist the hit, or can choose to suffer the cost and move on. If your companion’s health is 0, you must make the roll. 

When your companion’s health is at 0 and you score a miss, they are out of action. You cannot leverage their support until they gain at least +1 health. Envision what this means in the fiction of your scene. 

To give aid to a companion, make an appropriate move. Unless the asset describes otherwise, this is typically [[MV_Heal|Heal]] for people and creatures, and [[MV_Repair|Repair]] for mechanical companions

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

#Pedia/Moves/Suffer 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>