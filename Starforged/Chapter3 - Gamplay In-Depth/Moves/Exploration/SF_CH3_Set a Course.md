---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Set a Course (SF Moves)"
PageType: Move
PageCategory: Exploration
PageOrder: 6

## Move
MoveName: "Set a Course"
InlineCmd: SAC
Trigger: "When you follow a known route through perilous space, across hazardous terrain, or within a mysterious site"
RollType: Action
RollStat: Supply
ReferencedMoves: 
  - [[SF_CH3_Undertake an Expedition]]
  - [[SF_CH3_Aid Your Ally]]
  - [[SF_CH3_Pay the Price]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Exploration Moves|Exploration]]: Set a Course
## Set A Course: Move Card
>[!abstract]  Trigger and Preparation
>**When you follow a known route through perilous space, across hazardous terrain, or within a mysterious site...** ^trigger

>[!error]- Improper Usage
>If the destination or route you are trail blazing is a new or lost discovery, use the [[SF_CH3_Undertake an Expedition|Undertake an Expedition (move)]] instead. ^improper

>[!tip]- Group Play
>Only one character needs to make this move for the group.  If another player has unique knowledge, skills or resources that could be helpful on the journey, then [[SF_CH3_Aid Your Ally|Aid Your Ally (move)]] ^group-play

> [!warning] Action Roll
> Roll + supply ^action-roll

> [!challenge-strong] On strong hit
> Take +1 Momentum
> > [!cite]- Narrative prompt
> > You arrive safely at your destination. Hours, days, or weeks will have passed as appropriate to the scope of the journey, but the trip was uneventful. 
> > Envision the following
> > * How you managed the journey and what you did with any downtime?
> > * How does the situation favor you at your destination? ^strong-hit

> [!challenge-weak] On a weak hit
> You arrive, but face a cost or complication.  Choose one:
>- Make one [[_SF_CH3_Suffer Moves|Suffer Move]] (-2)
>- Make two [[_SF_CH3_Suffer Moves|Suffer Moves]] (-2)
>- Face a complication at the destination.
> > [!cite]- Narrative prompt
> > If the cost that was suffered enroute to the destination, how it impacts your situation?
> > If the consequence was faced at the destination, what is the nature of this complication? ^weak-hit

> [!challenge-miss] On a miss
> You must [[SF_CH3_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > On a miss, you are waylaid by a significant danger enroute. Envision what you encounter and do what you must to overcome this threat. If you survive, you can push on safely to your destination without making another move ^miss

## Full Description
When you are journeying along a known (but still perilous) path, make this move. Unlike [[SF_CH3_Undertake an Expedition|Undertake an Expedition]], which is resolved in individual segments, Set a Course condenses the narrative and mechanics of the entire journey into a single roll of the dice. 

For interstellar travel, plotted routes through the chaos of the Forge are called ==passages==. When traveling in your [[AST_Starship|STARSHIP]], you can Set a Course if you are following one of these charted paths. You’ll establish your own passages when you successfully [[SF_CH3_Undertake an Expedition|Undertake an Expedition]] through interstellar space, and you might have opportunities to obtain navigational data for a specific route through other means. See [[SF_CH1_Navigating the Forge|Navigating The Forge (SF The Basics)]] for more on interstellar travel within the Forge. 

For planetside travel and surveys within sites, you can Set a Course when you are journeying through a known area or along a previously established route.

On a strong hit, you arrive safely at your destination. Hours, days, or weeks will have passed as appropriate to the scope of the journey, but the trip was uneventful. Envision how you managed the journey and what you did with any downtime.

On a weak hit, you reach your destination, but the journey extracts a price. Choose an option from the move and envision the cost or complication.

On a miss, you are waylaid by a significant danger en route. Envision what you encounter and do what you must to overcome this threat. If you survive, you can push on safely to your destination without making another move.

*180 CHAPTER 3: GAMEPLAY IN DEPTH*

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
| **[[SF_CH3_Finish an Expedition\|Finish an Expedition (SF Moves)]]** | #Starforged/Moves/Exploration | **[[_SF_CH3_Combat Moves\|Combat Moves (SF)]]** |


<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>