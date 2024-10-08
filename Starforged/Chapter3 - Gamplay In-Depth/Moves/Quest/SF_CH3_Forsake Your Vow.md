---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Forsake Your Vow (SF Moves)"
PageType: Move
PageCategory: Quest
PageOrder: 4

## Move
MoveName: "Forsake Your Vow"
InlineCmd: FORSAKE
Trigger: 
- "Renounce a Quest"
- "Betray your promise"
- "Quest goal is lost to you"
RollType: None
ReferencedMoves: 
  - [[SF_CH3_Endure Stress]]
  - [[SF_CH3_Test Your Relationship]]
  - [[SF_CH3_Continue a Legacy]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Quest Moves|Quest]]: Forsake Your Vow
## Forsake Your Vow: Move Card
>[!abstract]  Trigger and Preparation
>**When you renounce your quest, betray your promise, or the goal is lost to you...** ^trigger

> [!tip]- Shared Vows
> Any allies who shared this vow will also clear it and may also envision a cost. ^group-play

> [!failure] Move Action
> Clear the vow and remove the track
> > [!cite]- Narrative Prompt
> > Envision the impact of this failure and choose one or more as appropriate to the nature of the vow.
> >- You are demoralized or dispirited: [[SF_CH3_Endure Stress|Endure Stress]] 
> >- A connection loses faith: [[SF_CH3_Test Your Relationship|Test Your Relationship]]
> >- You must abandon a path or resource: [[Discard an Asset]] #incomplete 
> >- Someone else pays a price: Envision how a person, being, or community bears the cost of the failure. [[Faction Suffers]] #incomplete 
> >- Someone else takes advantage: Envision how an enemy gains power. [[Faction Gain]] #incomplete 
> >- Your reputation suffers: Envision how this failure marks you. [[Lose a Mark]] #incomplete ^action

## Full Description
Make this move when you willfully abandon a quest, or if circumstances leave your goal unobtainable. 

Realizing you must Forsake Your Vow is a dramatic and disheartening decision. Consider how your failure affects your story and what you do to put yourself back on the proper path. Did you swear this vow in service to others? How does this impact your relationship with them? If your vow was a personal quest, how does this force you to rethink the path your life has taken? Where do you go from here? 

The move includes several prompts to consider for the ramifications of your vow and the narrative and mechanical costs. Choose the most appropriate (or more than one) and weave that outcome into your story. Depending on the situation, there may be long-term or delayed effects; if so, make note of them. 

If you abandon a quest that is central to your character’s motivations, you may decide your life as Ironsworn is done. If so, [[SF_CH3_Continue a Legacy|Continue a Legacy]] to see what you leave for those who follow in your footsteps.

> [!cite]- Narrative example
> You were sworn to recover a valuable cache of stolen supplies, but your quest has fallen out of reach. The thief’s starship was surprisingly fragile, and the supplies were reduced to atoms in the ensuing explosion. Now, you’ll need to report the bad news to your benefactor, the powerful head of a trade guild.

*160 CHAPTER 3: GAMEPLAY IN DEPTH*

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
| **[[SF_CH3_Fullfill Your Vow\|Fullfill Your Vow (SF Moves)]]** | #Starforged/Moves/Quest | **[[_SF_CH3_Connection Moves\|Connection Moves (SF)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>