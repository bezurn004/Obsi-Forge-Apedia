---
Alias: "Finish an Expedition (move)"
PageType: Move
PageCategory: Exploration
InlineCmd: FAE
Trigger: "When your expedition comes to an end"
RollType: Progress
ProgressTrack: Expedition
---
# [[_Moves Index|Moves]] - [[_Exploration Moves|Exploration]]: Finish an Expedition

## Finish An Expedition: Move Card
>[!abstract]  Context and Preparation
>When your expedition comes to an end...

> [!tip]- Group Play
> If you are on an expedition with allies, one of you makes this move. Each of you benefit (or suffer) from the narrative outcome, and you mark legacy rewards together. 

> [!progress] Progress Roll
> Roll the Challenge dice and compare to your Expedition Progress

> [!challenge-strong] On strong hit
> Mark a reward on your discoveries legacy track per expedition's rank: See [[GP_Tracks#Marking Legacy Rewards|Marking Legacy Rewards]] 
> Any allies who shared this expedition also mark the reward.
> 
> > [!quote] Narrative prompt
> > You completed the expedition successfully.  Consider the impact of your discoveries. 
> > * Did you trailblaze a new passage that you and others can follow? 
> > * Did you uncover resources or encounter mysteries that will have a lasting impact on your setting
> > * How has the expedition changed you?
> > 
> > Also consider how the expedition impacts your quests and vows.
> > * Does this serve as a milestone on a quest?  Make the [[MV_Reach a Milestone|Reach a Milestone]] move if so.
> > 
> > Once an expedition is complete, future travel along this route or within this site is streamlined. If you head back the way you came, or return in the future along the same path, you can [[MV_Set a Course|Set a Course]]

> [!challenge-weak] On a weak hit
> Same as on a Strong hit, with the following adjustments
> 1. Make the legacy reward one rank lower.
> 
> > [!quote] Narrative prompt
> > You face a complication at the end of your expedition. Things are not what you expected, or a new danger reveals itself. Envision what you encounter, then play to see what happens.
> > Once the encounter is completed consider the impacts of your expedition as prompted for a Strong hit.

> [!challenge-miss] On a miss
> Something has gone wrong on your expedition, choose one:
> 1. Abandon the expedition: Pay the Price
> 2. Return to the expedition: Roll both challenge dice, take the lowest value, and clear that number of progress boxes. Then, raise the expedition's rank by one (if not already epic).
>    
> > [!quote] Narrative prompt
> > Depending on your choice, envision what happens.
> > You realize you are off-course, relied on bad information, or face a turn of events that undermines the expedition or makes its cost too great.

## Full Description
When you have accrued progress on an expedition’s progress track and are ready to complete the expedition, make this move. 

Since this is a [[GP_Tracks#Progress Moves|Progress move]], tally the number of filled boxes on your progress track. This is your progress score. Only add fully filled boxes (those with four ticks). Then, roll your challenge dice, compare to your progress score, and resolve a strong hit, weak hit, or miss as normal. You may not burn momentum on this roll, and you are not affected by negative momentum. 

> [!quote]- Narrative example
> On the rugged, forested world of Nemus, you are on an expedition to reach a fabled site called the Heart of the Ancients. This massive floating island, held aloft by mysterious forces, is said to contain a precursor vault with untold technological riches. But when you Finish Your Expedition, you roll a miss. You envision finding not a vault, but a map. The journey is not yet complete…

See [[_Exploration Moves#COMBINING EXPEDITIONS AND QUESTS|Combiining Expeditions and Quests]] for details on pairing an expedition with a quest.

## Related Assets
```dataview
TABLE without ID
	link(file.link, alias) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, alias) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Progress - #Pedia/Moves/Exploration 


<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>