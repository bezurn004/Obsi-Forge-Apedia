---
Name: "Face Danger"
PageType: Move
PageCategory: [Adventure, "Scene Challenge"]
InlineCmd: FD
RollType: Action
RollStat: [Edge, Heart, Iron, Shadow, Wits]
Trigger: ["Speed","Mobility","Agility","Resolve","Command","Sociability","Strenght","Endurance","Aggression","Deceoption","Stealth","Trickery","Focus","Observation"]
Strong Hit: ["+1 Momentum","+1 Momentum","Progress(Scene_Challenge)"]
Weak Hit: ["Moves/Suffer","Moves/Suffer && +1 Clock_Segement[Scene_Challenge]"]
Miss: ["Moves/Pay the Price"]
Miss_Matched: 
---
# [[_Moves Index|Moves]]: Face Danger
### Categories: [[_Adventure Moves|Adventure Moves]] - [[_Scene Moves|Scene Challenge]]
>[!abstract]  Context and Preparation
>When you attempt something risky or react to an imminent threat...

> [!error]- Improper Usage
> If you are in the midst of a fight, do not make this move. [[React_Under_Fire]] is a variation of this move used for combat scenes. If you’re in a fight overcoming an obstacle or avoiding an immediate danger, whether in a vehicle or on foot, make that move instead of this one.

> [!warning] Action Roll
> Envision your action and roll. If you act..
> - With speed, mobility, or agility: Roll +edge
> - With resolve, command, or sociability: Roll +heart
> - With strength, endurance, or aggression: Roll +iron
> - With deception, stealth, or trickery: Roll +shadow
> - With expertise, focus, or observation: Roll +wits

> [!challenge-strong] On a strong hit 
> Take +1 Momentum
> 
> *Scene Challenge*
> * On a hit: Mark +1 progress for the scene
> * On a match: Mark +2 progress for the scene
>   
> >[!quote] Narrative prompt
> >You succeed. You are in control. What do you do next?

> [!challenge-weak] On a weak hit
> Choose one
> 1. Choose a fitting [Suffer Move](_Suffer Moves) at (-1)
> 2. If appropriate to the situation, an ally can suffer the cost by making the [[Companion Takes a Hit]] move.
>
> *Scene Challenge*
> 1. Mark +1 progress for the scene
> 2. Fill +1 Clock segment for the scene
> >[!quote] Narrative prompt
> >You overcome the obstacle or avoid the threat, but not without cost. 

> [!challenge-miss] On a miss
> You must [[Pay the Price]] 
> 
> *Scene Challenge*
> 1. On a miss: Fill +1 Clock segment for the scene
> 2.  On a match: Fill +2 Clock segments for the scene
>   
>   >[!quote] Narrative prompt
>   > * You are thwarted in your action, fail to oppose the threat, or are successful but at great cost. 
>   > * You might suffer an immediate narrative and mechanical cost, such as your vehicle taking a hit as you [[Withstand Damage]]. 
>   > * Or the miss might simply introduce an escalating danger or new complication. Either way, the miss should trigger a result that is more dramatic or harrowing than the cost you pay on a weak hit.

## Full Description
This move is a catch-all for risky, dramatic, or complex actions not covered by another move. If you’re trying to overcome an obstacle or resist a threat, and another move doesn’t seem to apply, Face Danger to see what happens. Envision your approach, select the stat that best reflects how you deal with the obstacle, and make the action roll.

> [!quote]- Narrative Example
> While riding your HOVERBIKE across a snowbound world, you find yourself in the path of an avalanche. You decide to try to outrun the deluge at top speed, and Face Danger +edge.

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
#Pedia/Moves/Adventure #Pedia/Moves/Scene_Challenge

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>