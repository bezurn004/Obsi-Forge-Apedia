---
Alias: "Face Defeat (move)"
PageType: Move
PageCategory: Combat
InlineCmd: FDEFEAT
Trigger: "When you abandon or are deprived of an objective"
RollType: None
---
# [[_Moves Index|Moves]] - [[_Combat Moves|Combat]]: Face Defeat

## Face Defeat: Move Card
>[!abstract]  Trigger and Preparation
>When you abandon or are deprived of an objective...

> [!error] Facing Defeat
> Clear the objective progress track and [[MV_Pay the Price|Pay the Price (move)]].
> If there are other objectives, you are in a Bad Spot. Move to resolve the remaining objectives.
> > [!quote] Narrative prompt
> > Envision the consequence of this failure.  How you react to the next?


## Full Description
Making the [[MV_Take Decisive Action|Take Decisive Action (move)]] is not the only way to resolve a combat objective. You can instead flee, surrender, shift to focus on another objective, or find yourself without any chance of success. When you can no longer bear the cost of the fight, or an objective falls out of reach, make this move. 

Face Defeat does not require a roll. Instead, you envision how you abandon or are deprived of your goal, clear that objective, and [[MV_Pay the Price|Pay the Price (move)]]. The cost you pay can be purely narrative as you deal with the fallout of this defeat. Or you might make a suffer move to represent an impact on your immediate condition or readiness, such as suffering stress, facing harm or damage, or losing momentum. 

If you have multiple objectives and do not Face Defeat for all of them, the fight isn’t over yet. If the situation and this defeat prompts a new combat objective, give it a rank and envision how you focus on this new goal. 

If you Face Defeat and the fight continues, you are in a bad spot. If you are working together with allies, the nature of the defeat should help decide who is put in a bad spot. If a single character was working toward an objective independently and must Face Defeat, they are in a bad spot. If multiple allies were trying to achieve the same objective, each of them is in a bad spot.


> [!quote]- Narrative example
> You are aiding the evacuation of a research facility that is overrun by aggressive, mutated creatures. You have two objectives: cover the evacuation and secure the research data. But you find yourself cut off from the labs, unable to press forward against a tide of beasts. You Face Defeat on the secure the research data objective. You are now in a bad spot, and envision getting surrounded in your moment of indecision. You’ll keep the cover the evacuation objective and add a new one: escape the horde.

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
#Pedia/Moves/Combat 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>