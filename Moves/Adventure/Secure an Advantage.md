---
Name: "Secure an Advantage"
PageType: Move
PageCategory: [Adventure, "Scene Challenge"]
InlineCmd: SAA
RollType: Action
RollStat: [Edge, Heart, Iron, Shadow, WIts]
---
# [[_Moves Index|Moves]]: Secure an Advantage
### Categories: [[_Adventure Moves|Adventure Moves]]
>[!abstract]  Context and Preparation
>When you assess a situation, make preparations, or attempt to gain leverage within a scene challenge, envision your action and roll. If you act...

> [!error]- Improper Usage
> If you are in the midst of a fight, do not make this move. Instead, you should [[Gain Ground]] when attempting to reinforce your position during combat scenes.

> [!warning] Action Roll
> - With speed, mobility, or agility: Roll +edge
> - With resolve, command, or sociability: Roll +heart
> - With strength, endurance, aggression: Roll +iron
> - With deception, stealth, or trickery: Roll +shadow
> - With expertise, focus, or observation: Roll +wits

> [!challenge-strong] On a hit 
> Take both of the below
> 1. Take +2 Momentum
> 2. Add +1 to your next move (not a progress move)
> 
> *Scene Challenge*
> On a match: Mark +1 progress for the scene
> >[!quote] Narrative prompt
> >You’ve identified an opportunity or gained the upper hand. Now it’s time to build on your success. 
> 

> [!challenge-weak] On a weak hit
> Take one of the below
> 1.  Take +2 Momentum
> 2.  Add +1 to your next move (not a progress move)
>    
> >[!quote] Narrative prompt
> >You’ve learned something important, but it makes your quest more complicated or dangerous. 
> >Your character’s position is improved through the discovery of this information, but it’s unwelcome news all the same.

> [!challenge-miss] On a miss 
> Your attempt to gain advantage has backfired. You must [[Pay the Price]].
> 
> *Scene Challenge*
> * On a miss - fill 1 Clock segment
> * On a match - fill 2 Clock segments
> 
> >[!quote] Narrative prompt
> >You acted too slowly, presumed too much, were outwitted or outmatched, or were confounded by unlucky chance.

## Full Description
Triggering and resolving Secure an Advantage is similar to Face Danger. You envision your action and roll + your most relevant stat. This move, however, is proactive rather than reactive. Instead of responding to an immediate obstacle or threat, you’re operating from a position of strength and attempting to bolster that position.

This move will often encompass a moment in time, such as trying to read your opponent in a not-so-friendly game of cards. Or it can represent preparation spanning minutes, hours, or even days.

> [!quote]- Narrative example
> You hope to secure the aid of a mercenary guild in a war against a powerful horde of raiders, and have gained an audience with the guild’s leader. In an attempt to start the meeting on good terms, you Secure an Advantage by praising their exploits in battle. You roll +heart to learn the impact of your flattery.
> Strong Hit Examples:
> * You moved into position to covertly study the enemy base. 
> * You prepared a clever disguise. 
> * You assembled an experimental engine-boosting device. 
> * You scouted the best path through the asteroid field. 

### Move Categories
[[_Adventure Moves|Adventure Moves]] - [[_Scene Moves|Scene Challenge]]

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
#Pedia/Moves/Adventure 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>