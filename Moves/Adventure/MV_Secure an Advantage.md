---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Secure an Advantage (move)"
PageType: Move
PageCategory: 
- Adventure
- Scene Challenge
PageOrder: 2

## Move
MoveName: "Secure an Advantage"
InlineCmd: SAA
RollType: Action
Trigger: "When you assess a situation, make preparations, or attempt to gain leverage within a scene challenge"
Approach: 
- "(Edge) Speed,Mobility,Agility"
- "(Heart) Resolve,Command,Sociability"
- "(Iron) Strength,Endurance,Aggression"
- "(Shadow) Deception,Stealth,Trickery"
- "(Wits) Expertise,Focus,Observation"
RollStat: 
- Edge
- Heart
- Iron
- Shadow
- Wits
ReferencedMoves: 
  - [[MV_Gain Ground]]
  - [[MV_Pay the Price]]
  - [[MV_Face Danger]]
---
# [[_Moves Index|Moves]] | [[_Adventure Moves|Adventure]] | [[_Scene Moves|Scene Challenge]]: Secure an Advantage

## Secure an Advantage: Move Card
>[!abstract]  Trigger and Preparation
>**When you assess a situation, make preparations, or attempt to gain leverage**; not in an encounter or in a scene challenge; envision your action and roll. If you act... ^trigger

> [!error]- Improper Usage
> If you are in the midst of a fight, do not make this move. Instead, you should [[MV_Gain Ground|Gain Ground]] when attempting to reinforce your position during combat scenes. ^improper

> [!warning] Action Roll
> - With speed, mobility, or agility: Roll +edge
> - With resolve, command, or sociability: Roll +heart
> - With strength, endurance, aggression: Roll +iron
> - With deception, stealth, or trickery: Roll +shadow
> - With expertise, focus, or observation: Roll +wits ^action-roll

> [!challenge-strong] On a strong hit 
> Take both of the below
> 1. Take +2 Momentum
> 2. Add +1 to your next move (not a progress move)
> 
> *Scene Challenge*
> On a match: Mark +1 progress for the scene
> >[!cite]- Narrative prompt
> >You’ve identified an opportunity or gained the upper hand. Now it’s time to build on your success. ^strong-hit
> 

> [!challenge-weak] On a weak hit
> Take one of the below
>- Take +2 Momentum
>- Add +1 to your next move (not a progress move)
>    
> >[!cite]- Narrative prompt
> >You’ve learned something important, but it makes your quest more complicated or dangerous. 
> >Your character’s position is improved through the discovery of this information, but it’s unwelcome news all the same. ^weak-hit

> [!challenge-miss] On a miss 
> Your attempt to gain advantage has backfired. You must [[MV_Pay the Price|Pay the Price]]. 
> 
> *Scene Challenge*
> * On a miss - fill 1 Clock segment
> * On a match - fill 2 Clock segments
> 
> >[!cite]- Narrative prompt
> >You acted too slowly, presumed too much, were outwitted or outmatched, or were confounded by unlucky chance. ^miss

## Full Description
Triggering and resolving Secure an Advantage is similar to [[MV_Face Danger|Face Danger]]. You envision your action and roll + your most relevant stat. This move, however, is proactive rather than reactive. Instead of responding to an immediate obstacle or threat, you’re operating from a position of strength and attempting to bolster that position.

This move will often encompass a moment in time, such as trying to read your opponent in a not-so-friendly game of cards. Or it can represent preparation spanning minutes, hours, or even days.

> [!cite]- Narrative example
> You hope to secure the aid of a mercenary guild in a war against a powerful horde of raiders, and have gained an audience with the guild’s leader. In an attempt to start the meeting on good terms, you Secure an Advantage by praising their exploits in battle. You roll +heart to learn the impact of your flattery.
> Strong Hit Examples:
> * You moved into position to covertly study the enemy base. 
> * You prepared a clever disguise. 
> * You assembled an experimental engine-boosting device. 
> * You scouted the best path through the asteroid field. 

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
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[MV_Face Danger\|Face Danger (move)]]** | #Pedia/Moves/Adventure - #Pedia/Moves/Scene_Challenge | **[[MV_Gather Information\|Gather Information (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>