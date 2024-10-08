---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Clash (SF Moves)"
PageType: Move
PageCategory: Combat
PageOrder: 5

## Move
MoveName: Clash
InlineCmd: CLASH
Trigger: "When you are in a bad spot and fight back against a foe"
Approach: [["Close quarters"],["From a distance"]]
RollType: Action
RollStat: [Iron, Edge]
ReferencedMoves: 
  - [[SF_CH3_Pay the Price]]
  - [[SF_CH3_Endure Harm]]
  - [[SF_CH3_Withstand Damage]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Combat Moves|Combat]]: Clash
## Clash: Move Card
>[!abstract]  Trigger and Preparation
>**When you are in a bad spot and fight back against a foe...** ^trigger

> [!warning] Action Roll
>- At close quarters roll +iron.
>- Exchange fire at a distance roll +edge. ^action-roll

> [!challenge-strong] On strong hit
> Mark progress twice and are In Control
> > [!cite]- Narrative prompt
> > You overwhelm your foe.  Envision your next steps as the encounter switches to your advantage. ^strong-hit

> [!challenge-weak] On a weak hit
> Mark progress but remain in a Bad Spot and must [[SF_CH3_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > While you do make some progress, you are dealt a counterblow or setback.  Envision the cost and how you will react to your foe's next move. ^weak-hit

> [!challenge-miss] On a miss
> Remain in a Bad Spot and you must [[SF_CH3_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > Your foe dominates this exchange and you do not make any headway.  What next will the foe do and  how will you try to overcome their advantage. ^miss

## Full Description
Make this move when you are in a bad spot and choose to fight back against your foe. 

First, envision your action and the fiction of the exchange. Is this a focused, dramatic moment where you each seek an opening? Or is it a flurry of attacks and counters, advances and retreats? The outcome of the move determines whether your foe presses their advantage, or if you turn the tide and take control. 

On a strong hit, you come out on top. As with the Strike move, mark progress twice per the rank of the objective. 

On a weak hit, you manage to inflict harm or damage and mark progress, but stay in a bad spot. Plus, you must [[SF_CH3_Pay the Price|Pay the Price]]. The cost you suffer can be to [[SF_CH3_Endure Harm|Endure Harm]] or [[SF_CH3_Withstand Damage|Withstand Damage]]. Or you may face some other dramatic outcome as appropriate to the current situation and your foe’s intent. 

The result of a weak hit as you Clash, whether mechanical or purely narrative, should be more dire than the merely troublesome price you face if you [[SF_CH3_React Under Fire|React Under Fire]] and score a weak hit. The weak hit with Clash enables you to mark progress, but comes at a cost. This is the risk and reward of wading into the fight. 

On a miss, you fail, don’t mark progress, stay in a bad spot, and must [[SF_CH3_Pay the Price|Pay the Price]] . This fight is turning against you.

> [!cite]- Narrative example
> You are attempting to hold off enemy troopers as your ally frantically preps the [[AST_Starship|STARSHIP]] for launch. Your foes burst through the docking bay entrance, firing wildly at you and the ship. You level your guns and Clash to shoot back, rolling +edge since you are at a distance. 

*193 COMBAT MOVES*

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
| **[[SF_CH3_Strike\|Strike (SF Moves)]]** | #Starforged/Moves/Combat | **[[SF_CH3_Take Decisive Action\|Take Decisive Action (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>