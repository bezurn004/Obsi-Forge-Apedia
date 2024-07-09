---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "End a Session (move)"
PageType: Move
PageCategory: Session
PageOrder: 5

## Move
MoveName: End a Session
InlineCmd: EAS
Trigger: "When you end a significant session or chapter of play"
RollType: None
ReferencedMoves: 
  - [[MV_Begin a Session]]
  - [[MV_Develop a Relationship]]
  - [[MV_Reach a Milestone]]
---
# [[_Moves Index|Moves]] - [[_Session Moves|Session]]: End a Session

## End A Session: Move Card
>[!abstract]  Trigger and Preparation
>**When you end a significant session or chapter of play...**
>

>[!question] Missed Opportunities
>Reflect on the events of the game and identify any missed opportunities to mark progress.
>	- If you strengthened your ties to a connection, [[MV_Develop a Relationship|Develop a Relationship]]
>	- If you moved forward on a quest, [[MV_Reach a Milestone|Reach a Milestone]]
>If there is a quest, connection, or other situation you would like to give focus in your next session, make note of it and take +1 momentum.



## Full Description
Make this move to mark the end of a session. This is an opportunity to transition from the fictional space of the game and think or talk about the dramatic moments, thrilling successes, agonizing failures, unexpected surprises, and what lies ahead in your next session. 

You will also consider whether you missed any chances to mark progress on a connection or quest during play. Those milestones can sometimes pass you by during intense scenes, and this is an ideal moment to recap and catalog your successes. 

Optionally, you may also make note of anything you’d like to focus on for your next session. Consider your character’s goals and the elements of the story that interest you. This act of writing it down, putting a stake in the ground, is a reminder and encouragement to pick up that thread when you next [[MV_Begin a Session|Begin a Session]]. If you are playing with others, be respectful of sharing the spotlight and work together to affirm the aspects of the story and setting you want to explore in more detail, or take turns suggesting a focus from one session to the next. If you are playing as the guide, use this input from the players to help kick off the next session.

>As noted in the [[MV_Begin a Session|Begin a Session]] move, the start and end of your sessions can be a bit fuzzy if you aren’t sitting down to play for a few hours at a time. If it’s more appropriate to the structure of your game, you can use the End a Session move to mark the end of a chapter instead of a session. A chapter can be any meaningful narrative transition, whether it’s a suspenseful cliffhanger or the resolution of an expedition or quest.

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
| **[[MV_Take a Break\|Take a Break (move)]]** | #Pedia/Moves/Session | **[[_Adventure Moves\|Adventure Moves]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>