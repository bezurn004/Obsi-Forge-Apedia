---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Fullfill Your Vow (SF Moves)"
PageType: Move
PageCategory: Quest
PageOrder: 3

## Move
MoveName: "Fullfill Your Vow"
InlineCmd: FULFILL
Trigger: "When you reach the end of your quest" 
RollType: Progress
RollStat: Quest
Track: Progress(Encounter Objective[])
Strong Hit: 
Weak Hit: 
Miss: 
ReferencedMoves: 
  - [[SF_CH3_Swear an Iron Vow]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Quest Moves|Quest]]: Fulfill Your Vow
## Fulfill Your Vow: Move Card
>[!abstract]  Context and Preparation
>**When you reach the end of your quest...** ^trigger

> [!tip]- Group Play
>  Are you working with allies to fulfill a shared vow? If so, one of you represents the group and makes the progress roll.  
>  After the roll is made, any allies who shared this vow also mark the reward and envision the narrative. ^group-play

> [!progress] Progress Roll
>  Roll the challenge dice and compare to your quests progress. ^progress-roll

> [!challenge-strong] On strong hit
>  Mark a reward on your quests legacy track per the vow rank: 
> > [!cite]- Narrative prompt
> > Your vow is fulfilled.  Envision the outcome and what happens next as you take control of the next steps. ^strong-hit

> [!challenge-weak] On a weak hit
> The quest was successful, but without complication.  Choose one of the following rewards.
>- Apply the same rewards as a strong hit as above, but there is more to be done or you realize the truth of your quest. If you [[SF_CH3_Swear an Iron Vow|Swear an Iron Vow]] to set things right, take your full legacy reward.
>- Otherwise, make the reward one rank lower.
> > [!cite]- Narrative prompt
> > Envision the complication and possible new vow that is to be taken on. ^weak-hit

> [!challenge-miss] On a miss
>  Your vow is undone through an unexpected complication or realization. choose one. 
>- Give up on the quest: [[SF_CH3_Forsake Your Vow|Forsake Your Vow]]
>- Recommit to the quest: Roll both challenge dice, take the lowest value, and clear that number of progress boxes. Then, raise the vow's rank by one (if not already epic).
> > [!cite]- Narrative prompt
> > Envision what happens as your either give up or recommit to your quest. ^miss

## Full Description
The fiction driving your vow and the mechanical incentive represented by your progress track converge in the decisive moment when you believe your quest is at an end. Are you truly victorious? Make this move to find out. 

Since this is a [[SF_CH1_Progress Tracks#Progress Moves|Progress Move]], tally the number of filled boxes on your quest progress track. This is your progress score. Only add fully filled boxes (those with four ticks). Then, roll your challenge dice, compare to the progress score, and resolve a strong hit, weak hit, or miss as normal. You may not burn momentum, and you are not affected by negative momentum. 

Managing your mechanical progress and the fiction to reach this moment may require a bit of stagecraft. It’s the end of the third act. Your actors must be in position. Your sets and props need to be in place. The lights come up for the final scene… 

However, keep in mind it’s not necessary to fill your vow’s progress track before you Fullfill Your Vow. Has the fiction led you to a moment when your quest seems complete, but the progress track is not even half full? Go with it. A weak hit or miss on the Fullfill Your Vow can create interesting stories and motivate new vows

*158 CHAPTER 3: GAMEPLAY IN DEPTH*
*159 QUEST MOVES*

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
| **[[SF_CH3_Reach a Milestone\|Reach a Milestone (SF Moves)]]** | #Starforged/Moves/Quest | **[[SF_CH3_Forsake Your Vow\|Forsake Your Vow (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>