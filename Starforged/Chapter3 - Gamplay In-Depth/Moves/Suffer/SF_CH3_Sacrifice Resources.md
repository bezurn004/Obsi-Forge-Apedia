---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Sacrifice Resources (SF Moves)"
PageType: Move
PageCategory: Suffer
PageOrder: 5

## Move
MoveName: "Sacrafice Resources"
InlineCmd: SR
Trigger: ["When you lose resources","When you consume resources"]
RollType: None
ReferencedMoves:
  - [[SF_CH3_Lose Momentum]]
  - [[SF_CH3_Endure Harm]]
  - [[SF_CH3_Endure Stress]]
  - [[SF_CH3_Companion Takes a Hit]]
  - [[SF_CH3_Withstand Damage]]
  - [[SF_CH3_Pay the Price]]
  - [[SF_CH3_Resupply]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Suffer Moves|Suffer]]: Sacrifice Resources
## Sacrafice Resources: Move Card
>[!abstract]  Trigger and Preparation
>**When you lose or consume resources...** ^trigger

> [!tip]- Group Play
> If you are playing with allies, supply is shared. You track the rise and fall of your supply meter together. When anyone makes this move, each of you adjust your supply meter to that new value. ^group-play

> [!warning] Move Action
> Suffer based on if this is a...
>- **Minor loss**, suffer -1 supply
>- **Serious loss**, suffer -2 supply
>- **Major loss**, suffer -3 supply
> If your supply is exhausted (reduced to 0), mark unprepared
> When you suffer a loss of resources while unprepared, envision how this causes you hardship and apply the cost to a different [[_SF_CH3_Suffer Moves|Suffer Move]]

## Full Description
Your ==[[SF_CH1_Condition Meters#Supply|supply meter]]== is an abstract representation of your overall readiness, shared between you and your allies. Make this move to reduce supply when you deplete provisions, lose equipment, expend munitions, use up fuel or energy, squander funds, give up cargo as a trade or concession, or otherwise suffer an impact on your preparedness. 

When you must [[SF_CH3_Pay the Price|Pay the Price]], you can Sacrifice Resources if a hit to your readiness is a fitting outcome of the current situation. Also, moves and assets can prompt you to Sacrifice Resources as a cost or concession, and may indicate a specific loss to apply, phrased as “Sacrifice Resources (-X).” 

If the cost is open to interpretation, consider the situation and reduce your supply meter as appropriate to the severity: 
- **Minor (-1):** A minor loss might be using up provisions while traveling or using extra ammo in a firefight
- **Serious (-2):** A serious loss is sacrificing valuable equipment or making a costly bribe
- **Major (-3):** A major loss is suffering a catastrophic fuel leak or jettisoning cargo to appease pirates. 
If in doubt, make it serious. 

When your supply is reduced to 0, mark ==[[SF_CH1_Impacts#Misfortunes|unprepared]]==. While you are unprepared, you cannot increase your supply meter. This impact can be cleared when you successfully [[SF_CH3_Resupply|Resupply]]. 

A lack of supply can affect your fitness, morale, and ability to take on challenges. If you suffer additional -supply while unprepared, you must apply an equal cost through another suffer move. For example, your ship might [[SF_CH3_Withstand Damage|Withstand Damage]] as energy reserves run low, or you [[SF_CH3_Endure Stress|Endure Stress]] as the hardships of the Forge take their toll

> [!cite]- Narrative example
> You need info on the comings and goings at a large starport, and attempt to [[SF_CH3_Make a Connection|Make a Connection]] with a local official. Unfortunately, you roll a weak hit and must introduce a complication or cost to begin the relationship. You envision paying a substantial bribe to get their cooperation, and Sacrifice Resources. 

*205 SUFFER MOVES*

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
| **[[SF_CH3_Companion Takes a Hit\|Companion Takes a Hit (SF Moves)]]** | #Starforged/Moves/Suffer | **[[SF_CH3_Withstand Damage\|Withstand Damage (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>