---
Alias: "Set a Course (move)"
PageType: Move
PageCategory: Exploration
InlineCmd: SAC
Trigger: "When you follow a known route through perilous space, across hazardous terrain, or within a mysterious site"
RollType: Action
RollStat: Supply
---
# [[_Moves Index|Moves]] - [[_Exploration Moves|Exploration]]: Set a Course

## Set A Course: Move Card
>[!abstract]  Trigger and Preparation
>When you follow a known route through perilous space, across hazardous terrain, or within a mysterious site...

>[!error]- Improper Usage
>If the destination or route you are trail blazing is a new or lost discovery, use the [[MV_Undertake an Expedition|Undertake an Expedition (move)]] instead.

>[!tip]- Group Play
>Only one character needs to make this move for the group.  If another player has unique knowledge, skills or resources that could be helpful on the journey, then [[MV_Aid Your Ally|Aid Your Ally (move)]]

> [!warning] Action Roll
> Roll + supply

> [!challenge-strong] On strong hit
> Take +1 Momentum
> > [!quote] Narrative prompt
> > You arrive safely at your destination. Hours, days, or weeks will have passed as appropriate to the scope of the journey, but the trip was uneventful. 
> > Envision the following
> > * How you managed the journey and what you did with any downtime?
> > * How does the situation favor you at your destination?

> [!challenge-weak] On a weak hit
> You arrive, but face a cost or complication.  Choose one:
> 1. Make one [[_Suffer Moves|Suffer Move]] (-2)
> 2. Make two [[_Suffer Moves|Suffer Moves]] (-2)
> 3. Face a complication at the destination.
>
> > [!quote] Narrative prompt
> > If the cost that was suffered enroute to the destination, how it impacts your situation?
> > If the consequence was faced at the destination, what is the nature of this complication?

> [!challenge-miss] On a miss
> You must [[MV_Pay the Price|Pay the Price]]
> > [!quote] Narrative prompt
> > On a miss, you are waylaid by a significant danger enroute. Envision what you encounter and do what you must to overcome this threat. If you survive, you can push on safely to your destination without making another move

## Full Description
When you are journeying along a known (but still perilous) path, make this move. Unlike [[MV_Undertake an Expedition|Undertake an Expedition]], which is resolved in individual segments, Set a Course condenses the narrative and mechanics of the entire journey into a single roll of the dice. 

For interstellar travel, plotted routes through the chaos of the Forge are called passages. When traveling in your [[AST_Starship|Starship (asset)]], you can Set a Course if you are following one of these charted paths. You’ll establish your own passages when you successfully [[MV_Undertake an Expedition|Undertake an Expedition]] through interstellar space, and you might have opportunities to obtain navigational data for a specific route through other means. See [[GP_Navigating the Forge|Navigating the Forge (gameplay)]] for more on interstellar travel within the Forge. 

For planetside travel and surveys within sites, you can Set a Course when you are journeying through a known area or along a previously established route.

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


#Pedia/Moves/Exploration 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>