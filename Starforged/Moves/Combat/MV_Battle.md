---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Battle (move)"
PageType: Move
PageCategory: Combat
PageOrder: 8

## Move
MoveName: Battle
InlineCmd: BATTLE
RollType: Action
Trigger: "When you fight a battle and it happens in a blur"
Approach: [["Speed","Environment to your advantage"],["Courage","Leadership","Companions"],["Close quarters","Overpower foe"],["Trickery"],["Tactics"]]
RollStat: [Edge, Heart, Iron, Shadow, Wits]
ReferencedMoves: 
  - [[MV_Pay the Price]]
  - [[MV_Enter the Fray]]
---
# [[_Moves Index|Moves]] - [[_Combat Moves|Combat]]: Battle
## Battle: Move Card
>[!abstract]  Trigger and Preparation
>**When you fight a battle and it happens in a blur...** ^trigger

> [!tip]- Group Play
> When you and your allies Battle together, one of you takes the lead and makes the move. On a strong hit, everyone benefits from the narrative success, but only the character making the move takes the momentum bonus. On a weak hit or miss, suffer an outcome that fits the situation, either to an individual or the group. ^group-play

> [!warning] Action Roll
> Envision your objective, if you...
>-  Fight at range, or using your speed and the environment to your advantage: Roll +edge.
>-  Fight depending on your courage, leadership, or companions: Roll +heart.
>-  Fight in close to overpower your foe: Roll +iron.
>-  Fight using trickery to befuddle your foe: Roll +shadow.
>-  Fight using careful tactics to outsmart your foe: Roll +wits. ^action-roll

> [!challenge-strong] On strong hit
> You achieve your objective unconditionally. 
> You and any allies who joined the battle may Take +2 momentum.
> > [!cite]- Narrative prompt
> > Envision what you will do next now that the objective is overcome. ^strong-hit

> [!challenge-weak] On a weak hit
>  You achieve your objective, but not without cost. You must [[MV_Pay the Price|Pay the Price (move)]].
> > [!cite]- Narrative prompt
> > Envision both the success and cost suffered in achieving your objective. What will happen next? ^weak-hit

> [!challenge-miss] On a miss
> You are defeated or the objective is lost.  You must [[MV_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > Envision how the loss of this objective sets back your overall progress.  This should hurt more than the cost of a weak hit. However, this should not be the end of your story.  Move forward and try to reclaim what was lost. ^miss

## Full Description
Make this move as an alternative to a detailed combat scene. If your story doesn’t emphasize fighting, or you’d rather abstract combat encounters, you can use this move exclusively. Or you can drop it into some portion of a larger scene. Perhaps you Battle to deal with lesser foes, then [[MV_Enter the Fray|Enter The Fray]] for your main objective. The mix of Battle and detailed fight scenes can guide your focus to what is interesting or important. 

A strong hit is unconditional success. You achieve your objective and your foes are defeated, surrender, or flee as appropriate to their nature and your intent. 

A weak hit means you achieve your objective, but at some cost. Since this is the resolution of an extended scene, the price you pay on a weak hit should be meaningful. 

If you score a miss as you Battle, you fail to achieve your objective and must [[MV_Pay the Price|Pay the Price]]. Make it hurt, but not in such a way that it puts an end to your story. Envision what happens, apply the cost of this failure, and decide how you move forward. 

> [!cite]- Narrative example
> Sentry bots attack as you approach the enemy outpost. You don’t want to focus on this fight, so you Battle to see what happens. 

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
| **[[MV_Face Defeat\|Face Defeat (move)]]** | #Pedia/Moves/Combat | **[[_Suffer Moves\|Suffer Moves]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>