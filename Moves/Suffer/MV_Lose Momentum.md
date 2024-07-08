---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Lose Momentum (move)"
PageType: Move
PageCategory: Suffer
PageOrder: 1

## Oracle
MoveName: "Lose Momentum"
InlineCmd: LM
Trigger: ["When you are delayed","When you are disadvantaged"]
RollType: None
ReferencedMoves: 
  - [[MV_Pay the Price]]
---
# [[_Moves Index|Moves]] - [[_Suffer Moves|Suffer]]: Lose Momentum
## Lose Momentum: Move Card
>[!abstract]  Trigger and Preparation
>**When you are delayed or disadvantaged...** ^trigger

> [!warning] Move Action
>- For a minor setback suffer -1
>- For a serious setback suffer -2
>- For a major setback suffer -3 ^action

> [!error] Negative Momentum
> When your momentum is at its minimum (-6) and you must suffer -momentum, choose one.
>- Envision how the price is paid and apply the cost to a different suffer move.
>- Envision how this undermines your progress on a vow, expedition, connection, or combat. Then, clear 1 unit of progress on that track per its rank: troublesome=3 boxes; dangerous=2 boxes; formidable=1 box; extreme=2 ticks; epic=1 tick. ^negative-momentum

## Full Description
Your ==[[GB_Momentum|momentum meter]]== tracks your character’s overall inertia, luck, and confidence, and will ebb and flow through a session. Make this move when you must [[MV_Pay the Price|Pay the Price]] and face a situational delay or disadvantage. Also, moves and assets will prompt you to Lose Momentum as a cost or concession, and may indicate a specific amount to suffer, phrased as “Lose Momentum (-X).” 

When you make this move, reduce your momentum meter according to the nature of the setback: minor (-1), serious (-2), or major (-3). If the cost is open to interpretation, consider the scope of the situation. A minor setback is a slight inconvenience, while a major setback is a dramatic delay or hindrance. If in doubt, make it serious. 

Not every new problem should result in a loss of momentum. A complication or danger is often a great enough cost by itself, and doesn’t need mechanical impact to affect your character and story. Use the Lose Momentum move for meaningful but short-lived setbacks. Bigger misfortunes can stand on their own. 

When you suffer a loss of momentum while your momentum meter is at its lowest point (-6), the leftover momentum must be traded for an equal cost through another suffer move. Or it must be accounted for as lost progress in a progress track, using the vow, connection, expedition, or fight that is most relevant to the current situation. Make a choice between those two options as appropriate to the situation, and envision how this setback is reflected in the fiction.


> [!cite]- Narrative example
> You are riding your [[AST_Skiff|SKIFF]] across storm-tossed seas. When you must [[MV_Pay the Price|Pay the Price]], you envision a large wave swamping your vehicle. The [[AST_Skiff|SKIFF]] nearly keels over, and your gear is soaked. You Lose Momentum as you struggle to get back on course. 

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
| Section Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[_Suffer Moves\|Suffer Moves]]** | #Pedia/Moves/Suffer | **[[MV_Endure Harm\|Endure Harm (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>