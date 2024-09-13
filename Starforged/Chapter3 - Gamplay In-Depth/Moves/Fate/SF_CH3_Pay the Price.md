---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Pay the Price (SF Moves)"
PageType: Move
PageCategory: Fate
PageOrder: 2

## Move
MoveName: "Pay the Price"
InlineCmd: PTP
Trigger: "When you suffer the outcome of an action"
RollType: Oracle
RollTable: Oracle/PayThePrice
ReferencedMoves: 
  - [[SF_CH3_Ask the Oracle]]
  - [[SF_CH3_Lose Momentum]]
  - [[SF_CH3_Endure Harm]]
  - [[SF_CH3_Endure Stress]]
  - [[SF_CH3_Sacrifice Resources]]
  - [[SF_CH3_Withstand Damage]]
  - [[SF_CH3_Companion Takes a Hit]]
  - [[SF_CH3_Battle]]
  - [[SF_CH3_Clash]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Fate Moves|Fate]]: Pay the Price
## Pay The Price: Move Card
>[!abstract]  Trigger and Preparation
>**When you suffer the outcome of an action...** ^trigger

> [!tip]- Guided Play
>  In guided play, look to your guide for a ruling.

> [!oracle] Oracle Roll
> Choose one:
>- Make the most obvious negative outcome happen.
>- [[SF_CH3_Ask the Oracle|Ask the Oracle]] for inspiration. Interpret the answer as a hardship or complication appropriate to the situation.
>- Roll on the table below. If the result doesn’t fit the situation, roll again ^oracle-roll
> > ![[#^table-pay-the-price]]

## Full Description
Make this move when prompted by another move due to a negative outcome, or when the current situation naturally leads to a cost through your choices or actions. 

First, choose an option as described in the move. You may decide the outcome yourself, [[SF_CH3_Ask the Oracle|Ask the Oracle]] for insight, or roll on the included table. Whatever choice you make, always follow the fiction. If an appropriate and dramatic outcome springs to mind, go with it.

*232 CHAPTER 3: GAMEPLAY IN DEPTH*

### Resolving the Cost
Once you’ve identified the basics of the negative outcome, envision it in more detail. What happens? How does it change the current situation and your approach going forward? Focusing on the fiction as you Pay the Price will lead to deeper, more dramatic stories. 

In fact, Pay the Price can often impact the narrative without an immediate mechanical cost. An initial failure may lead to a complication or force a reactive move. A failure on a subsequent move can then introduce a mechanical penalty. In this way, failures build on each other, and the situation gets riskier and more intense. 

Similarly, narrative costs that reveal major complications and dramatic surprises don’t need mechanical reinforcement. The twists and turns of your story are often enough of a price to pay. 

That said, mechanical costs help spotlight the taxing perils of the Forge, give focus to your character’s status and readiness, and serve as a price to pay when you don’t want to introduce snowballing narrative complications. If there is a mechanical cost, consider its impact. 
- If you suffer a delay or momentary setback, [[SF_CH3_Lose Momentum|Lose Momentum]]. 
- If you face a physical hardship or injury, [[SF_CH3_Endure Harm|Endure Harm]]. 
- If you are disheartened or frightened, [[SF_CH3_Endure Stress|Endure Stress]].
- If you deplete supplies or lose preparedness, [[SF_CH3_Sacrifice Resources|Sacrifice Resources]].
- If your vehicle takes a hit, [[SF_CH3_Withstand Damage|Withstand Damage]].
- If an ally or [[SF_CH3_Companion Takes a Hit|Companion]] is put in harm’s way, apply the cost to them. 

The narrative and mechanical costs you endure, and the focus you give to them, should fit the circumstances and the move you are making. Scoring a miss as you [[SF_CH3_Battle|Battle]] implies a more dramatic cost than if you fail to [[SF_CH3_Clash|Clash]] within a more detailed fight scene. For dramatic moments and decisive moves, up the stakes.

### What's Next
Once you Pay the Price and resolve the immediate cost, envision what happens next and how you react. You are not in control. The situation is more complex and dangerous. You may need to respond with another move to restore your advantage and avoid further cost.

> [!cite]- Narrative example
> You suffer a cost during an interstellar journey, and roll on the Pay the Price table to learn that “you face a tough choice.” You envision a fierce energy storm blocking your path. You could go through it, and risk damage to your ship, or go around and delay your arrival at the next waypoint by several hours. You choose the safer course, and [[SF_CH3_Lose Momentum|Lose Momentum]]. 

*233 FATE MOVES*

### Pay the Price Table
| dice: 1d100 | `dice: [[SF_CH3_Pay the Price#^table-pay-the-price]]` |
| :---: | --- |
| 1 – 2 | A trusted individual or community acts against you |
| 3 – 4 | An individual or community you care about is exposed to danger |
| 5 – 7 | You encounter signs of a looming threat |
| 8 – 10 | You create an opportunity for an enemy |
| 11 – 14 | You face a tough choice |
| 15 – 18 | You face the consequences of an earlier choice |
| 19 – 22 | A surprising development complicates your quest |
| 23 – 26 | You are separated from something or someone |
| 27 – 32 | Your action causes collateral damage or has an unintended effect |
| 33 – 38 | Something of value is lost or destroyed |
| 39 – 44 | The environment or terrain introduces a new hazard |
| 45 – 50 | A new enemy is revealed |
| 51 – 56 | A friend, companion, or ally is in harm’s way (or you are, if alone) |
| 57 – 62 | Your equipment or vehicle malfunctions |
| 63 – 68 | Your vehicle suffers damage |
| 69 – 74 | You waste resources |
| 75 – 81 | You are harmed |
| 82 – 88 | You are stressed |
| 89 – 95 | You are delayed or put at a disadvantage |
| 96 – 100 | Roll twice |
^table-pay-the-price

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
| Previous Page | Tags | Next Section |
|:--- |:---:| ---:|
| **[[SF_CH3_Ask the Oracle\|Ask the Oracle (SF Moves)]]** | #Starforged/Moves/Fate | **[[SF_CH3_Clocks\|Clocks (SF In Depth)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>