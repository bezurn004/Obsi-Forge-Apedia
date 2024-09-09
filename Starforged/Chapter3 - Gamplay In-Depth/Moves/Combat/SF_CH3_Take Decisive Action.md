---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Take Decisive Action (SF Moves)"
PageType: Move
PageCategory: Combat
PageOrder: 6

## Move
MoveName: "Take Decisive Action"
InlineCmd: TDA
Trigger: "When you seize an objective in a fight"
RollType: Progress
ProgressTrack: Objective
ReferencedMoves: 
  - [[MV_Pay the Price]]
  - [[MV_Face Defeat]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Combat Moves|Combat]]: Take Decisive Action
## Take Decisive Action: Move Card
>[!abstract]  Trigger and Preparation
>**When you seize an objective in a fight, envision how you take decisive action...** envision how you take decisive action. ^trigger

> [!tip]- Group Play
> When you and your allies are fighting for a common objective, you share a progress track. Anyone involved with the objective can instigate the final push and Take Decisive Action, with other allies describing how they contribute to the move. If you then score a weak hit or miss, consider the impact for the group and who suffers the cost. ^group-play

> [!progress] Progress Roll
>  Roll the Challenge dice and compare to against the progress of the objective.
> - If you are in control, check the result as normal. 
> - If you are in a bad spot
> 	- count a strong hit with a match as strong hit
> 	- count a strong hit without a match as a weak hit
> 	- count a weak hit as a miss ^progress-roll

> [!challenge-strong] On strong hit
> You prevail over your objective. Take +1 momentum. 
> If any other objectives remain and the fight continues, you are In Control.
> > [!cite]- Narrative prompt
> > Envision how the encounter ends and what happens next.  If there are other objectives, how will you work to overcome them? ^strong-hit

> [!challenge-weak] On a weak hit
>  You prevail over your objective, but not without cost. Roll on the table below or choose one of the negative outcomes. 
>  If the fight continues, you are in a Bad Spot.
>  >![[#^weak-hit-table]]
> 
> > [!cite]- Narrative prompt
> > Envision the negative cost and what happens next.  If the encounter continues how will you react to the threat of the next objective? ^weak-hit

> [!challenge-miss] On a miss
> You are defeated or your objective is lost.  You must [[SF_CH3_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > If this was the only objective, the fight is lost. Envision what this means and the cost you must pay as appropriate to your objective and the intentions of your foes. 
> > If you score a miss and other objectives are still achievable, you can deal with the cost of this failure and press on. 
> > 	If those objectives are out of reach, you should instead [[SF_CH3_Face Defeat|Face Defeat]].  ^miss

## Full Description
Your objective is at hand, and you make a final effort to see it done. Do you succeed, or does the fight turn against you? Make this move to find out. 

This is a dramatic moment. Focus on it. Envision your intent. You reach the comm console and prepare to transmit the stolen plans. You arm a torpedo and target the station’s vulnerable exhaust port. You seize the forgespawn brood mother in the articulated claws of your exosuit. You level your gun at the enemy troopers and demand their surrender. 

Since this is a [[SF_CH1_Progress Tracks#Progress Moves|Progress Move]], tally the number of filled boxes on your quest progress track. This is your progress score. Only add fully filled boxes (those with four ticks). Then, roll your challenge dice, compare to the progress score, and resolve a strong hit, weak hit, or miss. You may not burn momentum, and you are not affected by negative momentum. If you are in a bad spot as you make this move, you are not poised for success; unless you roll a strong hit with a match, you must shift the result down one level. 

On a strong hit, the objective is achieved. If you still face other objectives (using separate progress tracks), you are in control and the fight continues.

*194 CHAPTER 3: GAMEPLAY IN DEPTH*

If you score a weak hit, the victory comes at a cost. Roll or choose an outcome from the table. Then, consider the narrative implications of this outcome and what happens next. If the fight continues with any remaining objectives, you are in a bad spot. 

On a miss, your final effort is undone through a surprising turn of events or dramatic failure, and you must [[SF_CH3_Pay the Price|Pay the Price]]. If this was the only objective, the fight is lost. Envision what this means and the cost you must pay as appropriate to your objective and the intentions of your foes.

If you score a miss and other objectives are still achievable, you can deal with the cost of this failure and press on. If those objectives are out of reach, you should instead [[SF_CH3_Face Defeat|Face Defeat]]. 

### Take Decisive Action Table
| dice: 1d100 | `dice: [[SF_CH3_Take Decisive Action#^weak-hit-table]]` |
| --- | --- |
| 1–40 | It’s worse than you thought: Make a [[_SF_CH3_Suffer Moves\|Suffer Moves]] (-2) |
| 41–52 | Victory is short-lived: A new peril or foe appears |
| 53–64 | You face collateral damage: Something is lost, damaged, or broken |
| 65–76 | Others pay the price: Someone else suffers the cost |
| 77–88 | Others won’t forget: You are marked for vengeance |
| 89–100 | It gets complicated: The true nature of a foe or objective is revealed |
^weak-hit-table

> [!cite]- Narrative example
> You are aboard your [[AST_Rover|ROVER]], speeding along a rocky ravine, under attack by an enemy ship. You are ready to Take Decisive Action, and envision driving into a cave to throw off your pursuer. You make the progress roll and score a weak hit, a success, but at a cost. You pick the “victory is short-lived” outcome, and envision the cave entrance collapsing behind you, trapping you in the darkness. 

*195 COMBAT MOVES*

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
| **[[SF_CH3_Clash\|Clash (SF Moves)]]** | #Starforged/Moves/Combat | **[[SF_CH3_Face Defeat\|Face Defeat (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>