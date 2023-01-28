---
Name: "Sacrafice Resources"
PageType: Move
PageCategory: Suffer
InlineCmd: SR
RollType: None
Trigger: [""] 
Stats: []
---

# [[_Moves Index|Moves]] Sacrifice Resources
### Categories: [[_Suffer Moves|Suffer Moves]]
>[!abstract]  Context and Preparation
>When you lose or consume resources...

> [!tip]- Group Play
> If you are playing with allies, supply is shared. You track the rise and fall of your supply meter together. When anyone makes this move, each of you adjust your supply meter to that new value. 

> [!warning] Move Action
> Suffer based on if this is a...
>- Minor loss, suffer -1 supply
>- Serious loss, suffer -2 supply
>- Major loss, suffer -3 supply
> 
> If your supply is exhausted (reduced to 0), mark unprepared
> When you suffer a loss of resources while unprepared, envision how this causes you hardship and apply the cost to a different [Suffer Move](_Suffer Moves)

## Full Description
Your supply meter (page 48) is an abstract representation of your overall readiness, shared between you and your allies. Make this move to reduce supply when you deplete provisions, lose equipment, expend munitions, use up fuel or energy, squander funds, give up cargo as a trade or concession, or otherwise suffer an impact on your preparedness. 

When you must [[Pay the Price]], you can Sacrifice Resources if a hit to your readiness is a fitting outcome of the current situation. Also, moves and assets can prompt you to Sacrifice Resources as a cost or concession, and may indicate a specific loss to apply, phrased as “Sacrifice Resources (-X).” 

If the cost is open to interpretation, consider the situation and reduce your supply meter as appropriate to the severity: 
- Minor (-1): A minor loss might be using up provisions while traveling or using extra ammo in a firefight
- Serious (-2): A serious loss is sacrificing valuable equipment or making a costly bribe
- Major (-3): A major loss is suffering a catastrophic fuel leak or jettisoning cargo to appease pirates. 
If in doubt, make it serious. 

When your supply is reduced to 0, mark unprepared (page 50). While you are unprepared, you cannot increase your supply meter. This impact can be cleared when you successfully Resupply. 

A lack of supply can affect your fitness, morale, and ability to take on challenges. If you suffer additional -supply while unprepared, you must apply an equal cost through another suffer move. For example, your ship might Withstand Damage as energy reserves run low, or you Endure Stress as the hardships of the Forge take their toll


> [!quote]- Narrative example
> You need info on the comings and goings at a large starport, and attempt to Make a Connection with a local official. Unfortunately, you roll a weak hit and must introduce a complication or cost to begin the relationship. You envision paying a substantial bribe to get their cooperation, and Sacrifice Resources. 

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
#Pedia/Moves/Suffer 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>