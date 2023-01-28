---
Name: "Explore a Waypoint"
PageType: Move
PageCategory: Exploration
InlineCmd: EAW
RollType: Action
RollStat: Wits
---
# [[_Moves Index|Moves]]: Explore a Waypoint
### Categories: [[_Exploration Moves|Exploration Moves]]
>[!abstract]  Context and Preparation
>When you divert from an expedition to examine a notable location...

> [!warning] Action Roll
> Roll + wits

> [!challenge-strong] On strong hit
> Take +2 momentum and choose one. *Optional* On a match, you may instead [[Make a Discovery]].
> 1. Find an **Opportunity**
> 2. Gain **Progress**. Mark progress on your expedition, per its rank.
> 
> >[!quote] Narrative prompt
> >If you choose to find an **Opportunity**, take a moment to bring what you find to life. What is it? How can it help you? 
> >
> >The opportunity should make sense in the context of the location and the purpose of your exploration. It might also enable additional moves, such as finding a secure spot to [Repair](z_Obsi-Forge-Apedia/Moves/Recover/Repair.md), or discovering valuable salvage you can use to [Resupply](z_Obsi-Forge-Apedia/Moves/Recover/Resupply.md). 
> >
> >If you choose to gain **Progress**, envision how you earn this advantage. Is it a shortcut, helpful data, insight into the nature of the region, or some other discovery that speeds you along your way? 

> [!challenge-weak] On a weak hit
> Take +1 momentum
> > [!quote] Narrative prompt
> > You encounter something curious or helpful, but also face an immediate peril or learn something that foreshadows future danger. Envision what you encounter and what you do next. Trying to learn more or leverage this opportunity may force you into deeper peril. 

> [!challenge-miss] On a miss
> You must [[Pay the Price]]. 
> *Optional* On a match, you may instead [[Confront Chaos]]
> > [!quote] Narrative prompt
> > Your exploration has gone wrong or uncovered an unexpected hazard.  Resolve the situation

## Full Description
When you encounter a promising waypoint in the midst of an expedition and choose to explore that location in depth, make this move to see what you find. This move is best used sparingly for remarkable or unusual locations, rather than as a matter of course.

> [!quote]- Narrative example
> You are delving an abandoned mining facility deep in the heart of a crystalline asteroid. The site is full of dark passages and dormant industrial equipment. But you come across a high-tech research lab where the power is still active. What is this place? You Explore a Waypoint to take a closer look. 

### Perils and Opportunities 
If you reveal a peril or opportunity as you Explore a Waypoint, you can Ask the Oracle for insight. There are oracle tables for perils and opportunities for several common environments, including space (304–305), [[Planets]] (320–321), [[Derelicts]] (352–359), and [[Precursor Vaults]] (367–369).

Most results on those peril tables are a setup for a new threat or complication. You encounter an obstacle that must be overcome, or a foe who must be dealt with, or a mystery that must be solved. If you need clarification for an abstract or suggestive result, [[Ask the Oracle]]. Then, zoom in and resolve the situation. If a move is triggered, make it. 

Other results as you encounter a peril or [[Pay the Price]] may suggest an immediate consequence, such as making a [Suffer Moves](_Suffer Moves) (page 198). If so, make it happen. Varying the focus and nature of the dangers you encounter will help you manage the pace of your story. If it’s interesting and dramatic, zoom in. Otherwise, apply the consequence and move on. 

### Discoveries and Chaos
If you roll a match as you Explore a Waypoint, you can choose to encounter something wondrous or dreadful. 
* On a strong hit with a match, [[Make a Discovery]].
* On a miss with a match, [[Confront Chaos]]. 
Those moves offer prompts for the nature of what you uncover and allow you to mark rewards on your discoveries legacy track. 

>[!question] Matches are not a mandate
>This is a choice, not a mandate. Even on a match, you can choose to resolve the Explore a Waypoint move using the default outcomes. 

### Managing the scope of a waypoint 
The scale of your exploration may vary. On an interstellar expedition, you might Explore a Waypoint and resolve a days-long survey of an entire planet with one roll of the dice. Inside an alien vault, the same move can represent your examination of a single chamber in a matter of minutes. Envision your actions and outcome as appropriate to the situation and the level of story focus you give to the location. 

You can even choose to spotlight a notable waypoint by making your exploration of that location an expedition of its own. In that case, you do not Explore a Waypoint. Instead, [[Undertake an Expedition]]. You are nesting one expedition within another, each with its own progress track. 

> [!quote]- Narrative example
> During a planetside expedition, you encounter a ruined settlement. If you delve into the remains of this place, you can Explore a Waypoint to quickly resolve the search from a zoomed out perspective. Or you can choose to Undertake an Expedition within the site, giving the survey its own rank and progress track.

## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, title) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Exploration 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>