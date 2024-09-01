---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Finish an Expedition (move)"
PageType: Move
PageCategory: Exploration
PageOrder: 6

## Move
MoveName: "Finish an Expedition"
InlineCmd: FAE
Trigger: "When your expedition comes to an end"
RollType: Progress
ProgressTrack: Expedition
ReferencedMoves: 
  - [[MV_Reach a Milestone]]
  - [[MV_Set a Course]]
  - [[MV_Pay the Price]]
---
# [[_Moves Index|Moves]] - [[_Exploration Moves|Exploration]]: Finish an Expedition
## Finish An Expedition: Move Card
>[!abstract]  Context and Preparation
>**When your expedition comes to an end...** ^trigger

> [!tip]- Group Play
> If you are on an expedition with allies, one of you makes this move. Each of you benefit (or suffer) from the narrative outcome, and you mark legacy rewards together. ^group-play

> [!progress] Progress Roll
> Roll the Challenge dice and compare to your Expedition Progress Track ^progress-roll

> [!challenge-strong] On strong hit
> Mark a reward on your discoveries legacy track per the expedition's rank: See [[GB_Legacy Tracks#Marking Legacy Rewards|Marking Legacy Rewards]] 
> Any allies who shared this expedition also mark the reward.
> > [!cite]- Narrative Prompt
> > Consider the impact of your discoveries.
> > - If this was an interstellar voyage, did you trailblaze a new passage that you and others can follow?
> > - Did you uncover resources or encounter mysteries that will have a lasting impact on your setting?
> > - How has the expedition changed you?
> > 
> > Also consider how the expedition impacts your quests and vows.
> > - Does this serve as a milestone on a quest?  Make the [[MV_Reach a Milestone|Reach a Milestone]] move if so.
> > 
> > Once an expedition is complete, future travel along this route or within this site is streamlined. If you head back the way you came, or return in the future along the same path, you can [[MV_Set a Course|Set a Course]]

> [!challenge-weak] On a weak hit
> Same as on a strong hit, with the following adjustments
> 1. Make the legacy reward one rank lower.
> > [!cite]- Narrative prompt
> > You face a complication at the end of your expedition. Things are not what you expected, or a new danger reveals itself. Envision what you encounter, then play to see what happens.
> > Once the encounter is completed consider the impacts of your expedition as prompted for a strong hit. ^weak-hit

> [!challenge-miss] On a miss
> Something has gone wrong on your expedition, choose one:
>- Abandon the expedition: [[MV_Pay the Price|Pay the Price]]
>- Return to the expedition: Roll both challenge dice, take the lowest value, and clear that number of progress boxes. Then, raise the expedition's rank by one (if not already epic).
>    
> > [!cite]- Narrative prompt
> > Depending on your choice, envision what happens.
> > You realize you are off-course, relied on bad information, or face a turn of events that undermines the expedition or makes its cost too great.

## Full Description
When you have accrued progress on an expedition’s progress track and are ready to complete the expedition, make this move. 

Since this is a ==[[GB_Progress Tracks#Progress Moves|progress move]]==, tally the number of filled boxes on your progress track. This is your progress score. Only add fully filled boxes (those with four ticks). Then, roll your challenge dice, compare to your progress score, and resolve a strong hit, weak hit, or miss as normal. You may not burn momentum on this roll, and you are not affected by negative momentum.

If you are on an expedition with allies, one of you makes this move. Each of you benefit (or suffer) from the narrative outcome, and you mark legacy rewards together.

On a strong hit, you complete your survey or reach your destination. Mark progress on your ==discoveries legacy track== per the rank of the expedition. Then, consider the impact of your discoveries. If this was an interstellar voyage, did you trailblaze a new passage that you and others can follow? Did you uncover resources or encounter mysteries that will have a lasting impact on your setting? How has the expedition changed you?

On a weak hit, the journey or survey is complete, but something complicates the end of your expedition. Things are not what you expected, or a new danger reveals itself. Envision what you encounter, and make the legacy reward one rank lower. Then, play to see what happens.

On a hit, also consider how the expedition impacts your vows. If it serves as a milestone on a quest, make the Reach a Milestone move. See [[_Exploration Moves#COMBINING EXPEDITIONS AND QUESTS|Combiining Expeditions and Quests]] for details on pairing an expedition with a quest. Once an expedition is complete, future travel along this route or within this site is streamlined. If you head back the way you came, or return in the future along the same path, you can [[MV_Set a Course|Set a Course]].

On a miss, something has gone wrong. You realize you are off-course, relied on bad information, or face a turn of events that undermines the expedition or makes its cost too great. Depending on the circumstances and your choice, this might mean your expedition ends in failure, or that you push on while clearing some of your filled progress and raising the expedition’s rank.

> [!cite]- Narrative example
> On the rugged, forested world of Nemus, you are on an expedition to reach a fabled site called the Heart of the Ancients. This massive floating island, held aloft by mysterious forces, is said to contain a precursor vault with untold technological riches. But when you Finish Your Expedition, you roll a miss. You envision finding not a vault, but a map. The journey is not yet complete…



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
| **[[MV_Confront Chaos\|Confront Chaos (move)]]** | #Pedia/Moves/Progress - #Pedia/Moves/Exploration | **[[MV_Set a Course\|Set a Course (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>