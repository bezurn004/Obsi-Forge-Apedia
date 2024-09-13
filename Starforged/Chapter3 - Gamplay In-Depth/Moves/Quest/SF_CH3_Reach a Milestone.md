---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Reach a Milestone (SF Moves)"
PageType: Move
PageCategory: Quest
PageOrder: 2

## Move
MoveName: "Reach a Milestone"
InlineCmd: RAM
Trigger: 
- "overcoming a critical obstacle"
- "gaining meaningful insight"
- "completing a perious expedition"
- "acquiring a crucial item or resource"
- "earning vital support"
- "defeating a notable foe"
RollType: None
Track: Progress(Encounter Objective[])
ReferencedMoves: 
  - [[SF_CH3_Swear an Iron Vow]]
  - [[SF_CH3_Ask the Oracle]]
  - [[SF_CH3_Fullfill Your Vow]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Quest Moves|Quest]]: Reach a Milestone
## Reach A Milestone: Move Card
>[!abstract]  Trigger and Preparation
>When you make headway in your quest by doing any of the following...
>- overcoming a critical obstacle
>- gaining meaningful insight
>- completing a perilous expedition
>- acquiring a crucial item or resource
>- earning vital support
>- defeating a notable foe ^trigger

> [!tip]- Group Play
> All allies should mark progress on their shared vow ^group-pay

> [!success] Move Action
> Mark progress on the Quest Track per the vow rank ^action

## Full Description
When you [[SF_CH3_Swear an Iron Vow|Swear an Iron Vow]], the quest is given a challenge rank and managed through a progress track. Then, as you strive to complete your quest, you face and overcome challenges. Some of these challenges arise naturally out of the fiction of your situation. Others represent narrative twists introduced when you interpret the result of a move or when you [[SF_CH3_Ask the Oracle|Ask the Oracle]] for inspiration. When you reach these turning points and forge ahead in your vow, make this move and mark progress on the related quest. 

The move includes a list of milestone triggers, but there is flexibility in how you interpret accomplishments and events in your story. The pace of your quests is largely defined by what you set as milestones. They should be meaningful to your character and your vow, requiring effort and sacrifice. An insignificant discovery or effortless success is probably not a milestone. 

If you’re not sure if something is worthy of a milestone, trust your instincts and the type of play experience you want to create. If you’re playing co-op or guided, talk it out at the table. If you are in doubt, err on the side of success; Reach a Milestone and play to see what happens next. 

If you find your story moving to a resolution well ahead of your progress track, envision some complications or twists that alter your path and create new opportunities for milestones. But remember it’s not necessary to fill the quest progress track before you [[SF_CH3_Fullfill Your Vow|Fullfill Your Vow]]. Use the Reach a Milestone move as a pacing mechanism to move things toward an exciting conclusion with a good chance of success, but don’t fight the story when it feels inevitable. Let the chips fall where they may.


> [!cite]- Narrative example
> You need to properly arm the farmers to fight the marauding raiders, so you reach out to a black market connection and call in a favor. Once the weapons are secured, you Reach a Milestone. 

*157 QUEST MOVES*

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
| **[[SF_CH3_Swear an Iron Vow\|Swear an Iron Vow (SF Moves)]]** | #Starforged/Moves/Quest | **[[SF_CH3_Fullfill Your Vow\|Fullfill Your Vow (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>