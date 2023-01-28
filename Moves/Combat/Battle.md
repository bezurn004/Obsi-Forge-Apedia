---
Name: "Battle"
PageType: Move
PageCategory: Combat
InlineCmd: BATTLE
RollType: Action
RollStat: [Edge, Heart, Iron, Shadow, Wits]
Trigger: [""]
---
# [[_Moves Index|Moves]]: Battle
### Categories: [[_Combat Moves|Combat Moves]]
>[!abstract]  Context and Preparation
>When you fight a battle and it happens in a blur,..

> [!tip]- Group Play
> When you and your allies Battle together, one of you takes the lead and makes the move. On a strong hit, everyone benefits from the narrative success, but only the character making the move takes the momentum bonus. On a weak hit or miss, suffer an outcome that fits the situation, either to an individual or the group.

> [!warning] Action Roll
> Envision your objective, if you...
> -   Fight at range, or using your speed and the environment to your advantage: Roll +edge.
> -   Fight depending on your courage, leadership, or companions: Roll +heart.
> -   Fight in close to overpower your foe: Roll +iron.
> -   Fight using trickery to befuddle your foe: Roll +shadow.
> -   Fight using careful tactics to outsmart your foe: Roll +wits.

> [!challenge-strong] On strong hit
> You achieve your objective unconditionally. 
> You and any allies who joined the battle may Take +2 momentum.
> > [!quote] Narrative prompt
> > Envision what you will do next now that the objective is overcome.

> [!challenge-weak] On a weak hit
>  You achieve your objective, but not without cost. You must [[Pay the Price]].
> > [!quote] Narrative prompt
> > Envision both the success and cost suffered in achieving your objective.  What will happen next?

> [!challenge-miss] On a miss
> You are defeated or the objective is lost.  You must [[Pay the Price]].
> > [!quote] Narrative prompt
> > Envision how the loss of this objective sets back your overall progress.  This should hurt more than the cost of a weak hit. However, this should not be the end of your story.  Move forward and try to reclaim what was lost.

## Full Description
Make this move as an alternative to a detailed combat scene. If your story doesn’t emphasize fighting, or you’d rather abstract combat encounters, you can use this move exclusively. Or you can drop it into some portion of a larger scene. Perhaps you Battle to deal with lesser foes, then Enter the Fray for your main objective. The mix of Battle and detailed fight scenes can guide your focus to what is interesting or important. 

A strong hit is unconditional success. You achieve your objective and your foes are defeated, surrender, or flee as appropriate to their nature and your intent. 

A weak hit means you achieve your objective, but at some cost. Since this is the resolution of an extended scene, the price you pay on a weak hit should be meaningful. 

If you score a miss as you Battle, you fail to achieve your objective and must Pay the Price. Make it hurt, but not in such a way that it puts an end to your story. Envision what happens, apply the cost of this failure, and decide how you move forward. 

> [!quote]- Narrative example
> Sentry bots attack as you approach the enemy outpost. You don’t want to focus on this fight, so you Battle to see what happens. 

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
#Pedia/Moves/Combat 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>