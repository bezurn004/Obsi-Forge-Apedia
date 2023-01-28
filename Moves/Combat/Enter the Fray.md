---
Name: "Enter The Fray"
PageType: Move
PageCategory: Combat
InlineCmd: ETF
RollType: Action
RollStat: [Edge, Heart, Iron, SHadow, Wits]
Trigger: ["On the move","Facing off against your foe","In the thick of it at close quarters","Preparing to act against an unaware foe","Caught in a trap","Sizing up the situation"]
Track: Progress(Encounter Objective[])
Strong Hit: "+2 Momentum & In Control"
Weak Hit: ["+2 Momentum & Bad Spot","In Control"]
Miss: "Bad Spot"
---
# [[_Moves Index|Moves]]: Enter the fray
### Categories: [[_Combat Moves|Combat Moves]]
When you initiate combat or are forced into a fight
>[!abstract]  Context and Preparation
>When you initiate combat or are forced into a fight, envision your objective and give it a rank. If the combat includes discrete challenges or phases, set an objective with a rank for each...

> [!warning] Action Roll
> Then, roll to see if you are in control. If you are...
> - On the move: Roll +edge
> - Facing off against your foe: Roll +heart
> - In the thick of it at close quarters: Roll +iron
> - Preparing to act against an unaware foe: Roll +shadow
> - Caught in a trap or sizing up the situation: Roll +wits

> [!tip]- Group Play
> If you are fighting alongside allies, each of you rolls to determine your individual position as you Enter the Fray. Then, you and the other players envision the scene, describe your intent, and play to see what happens. You can share objectives, although you might focus on different tasks within the scope of each objective. 

> [!challenge-strong] On strong hit
> Gain both:
> 1. +2 Momentum, 
> 2. You are in control
>    
> > [!quote] Narrative prompt
> > Envision the situation as the battle begins.  You are first to move, what will you do?

> [!challenge-weak] On a weak hit
> Choose one:
> 1. +2 Momentum
> 2. You are in control
>    
> > [!quote] Narrative prompt
> > Envison the situation as the battle begins.  
> > * If you are in control, what will you do?
> > * If you are in a bad spot, how will you react?

> [!challenge-miss] On a miss
> You are in a bad spot
> > [!quote] Narrative prompt
> > Envision how the fight begins, how will you react?

## Full Description
Make this move when high-stakes combat is joined. First, define one or more objectives (page 183) and give each a rank: troublesome, dangerous, formidable, extreme, or epic. The foes, environment, and the nature of your goal can all have an impact on the rank of an objective. 
* If you are outmatched, make the rank higher. 
* If you are well-prepared and in a position of strength, make it lower. 

You might even use separate objectives and progress tracks to represent distinct stages, goals, or foes. 

Once you’ve set your objectives, envision the situation and roll with the appropriate stat. The result determines your position at the start of the fight: **in control** or in a **bad spot** (page 184). On a strong hit, you are in control and gain momentum. On a weak hit, choose one of those starting advantages. On a miss, you are in a bad spot; you’re caught unaware, put on the defense, or need to maneuver to get into the fight. 

> [!quote]- Narrative example
> You and your ally locate a precursor data archive in the midst of an ancient, devastated city. You need time to decipher the cryptic controls of the archive, but are suddenly attacked by hostile, insectlike creatures. When you Enter the Fray, you set an objective to retrieve the precursor data. Your ally will help make progress on that objective by fending off the swarm.

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