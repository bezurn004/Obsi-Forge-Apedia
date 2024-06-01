---
Alias: "Forsake Your Vow (move)"
PageType: Move
PageCategory: Quest
InlineCmd: FORSAKE
Trigger: 
- "Renounce a Quest"
- "Betray your promise"
- "Quest goal is lost to you"
RollType: None
---
# [[_Moves Index|Moves]] - [[_Quest Moves|Quest]]: Forsake Your Vow
## Forsake Your Vow: Move Card
>[!abstract]  Trigger and Preparation
>When you renounce your quest, betray your promise, or the goal is lost to you...

> [!tip]- Shared Vows
> Any allies who shared this vow will also clear it and may also envision a cost.

> [!todo] Move Action
> Clear the vow and remove the track
> > [!quote] Narrative Prompt
> > Envision the impact of this failure and choose one or more as appropriate to the nature of the vow.
> > - You are demoralized or dispirited: [[MV_Endure Stress|Endure Stress]] 
> > - A connection loses faith: [[MV_Test Your Relationship|Test Your Relationship]]
> > - You must abandon a path or resource: [[Discard an Asset]] #incomplete 
> > - Someone else pays a price: Envision how a person, being, or community bears the cost of the failure. [[Faction Suffers]] #incomplete 
> > - Someone else takes advantage: Envision how an enemy gains power. [[Faction Gain]] #incomplete 
> > - Your reputation suffers: Envision how this failure marks you. [[Lose a Mark]] #incomplete 

## Full Description
Make this move when you willfully abandon a quest, or if circumstances leave your goal unobtainable. 

Realizing you must Forsake Your Vow is a dramatic and disheartening decision. Consider how your failure affects your story and what you do to put yourself back on the proper path. Did you swear this vow in service to others? How does this impact your relationship with them? If your vow was a personal quest, how does this force you to rethink the path your life has taken? Where do you go from here? 

The move includes several prompts to consider for the ramifications of your vow and the narrative and mechanical costs. Choose the most appropriate (or more than one) and weave that outcome into your story. Depending on the situation, there may be long-term or delayed effects; if so, make note of them. 

If you abandon a quest that is central to your character’s motivations, you may decide your life as Ironsworn is done. If so, [[MV_Continue a Legacy|Continue a Legacy]] to see what you leave for those who follow in your footsteps.

> [!quote]- Narrative example
> You were sworn to recover a valuable cache of stolen supplies, but your quest has fallen out of reach. The thief’s starship was surprisingly fragile, and the supplies were reduced to atoms in the ensuing explosion. Now, you’ll need to report the bad news to your benefactor, the powerful head of a trade guild.


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
#Pedia/Moves/Quest

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>