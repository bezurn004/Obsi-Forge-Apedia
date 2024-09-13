---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Gain Ground (SF Moves)"
PageType: Move
PageCategory: Combat
PageOrder: 2

## Move
MoveName: "Gain Ground"
InlineCmd: GG
Trigger: 
- "When you are in control&"
- "Take action in a fight to reinforce your position|"
- "Move toward an objective|"
Approach:
- "(Edge) Pursuit,Fleeing,Manuvering"
- "(Heart) Charging boldly into action,Coming to the aid of others,Negotiating,Commanding"
- "(Iron) Gaining leverage with force,Power through,Making a threat"
- "(Shadow) Hiding,Preparing an ambush,Misdirecting"
- "(Wits) Coordinating a plan,Studying the situation,Cleverly gaining leverage"
RollType: Action
RollStat: 
- "Edge"
- "Heart"
- "Iron"
- "Shadow"
- "Wits"
ReferencedMoves: 
  - [[SF_CH3_Strike]]
  - [[SF_CH3_Aid Your Ally]]
  - [[SF_CH3_Pay the Price]]
  - [[SF_CH3_Secure an Advantage]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Combat Moves|Combat]]: Gain Ground
## Gain Ground: Move Card
>[!abstract]  Trigger and Preparation
>**When you are in control and take action in a fight to reinforce your position or move toward an objective...** ^trigger

> [!error]- Improper Usage
> If you are instead acting to inflict direct harm or damage while you are in control, make the [[SF_CH3_Strike|Strike]]. ^improper

> [!tip]- Group Play
> To assist another player with their narrative situation, make the move [[SF_CH3_Aid Your Ally|Aid Your Ally]] to provide them the benefit of your actions instead. ^group-play

> [!warning] Action Roll
> Envision your approach and roll. If you are...
> - In pursuit, fleeing, or maneuvering: Roll +edge
> - Charging boldly into action, coming to the aid of others, negotiating, or commanding: Roll +heart
> - Gaining leverage with force, powering through, or making a threat: Roll +iron
> - Hiding, preparing an ambush, or misdirecting: Roll +shadow
> - Coordinating a plan, studying a situation, or cleverly gaining leverage: Roll +wits ^action-roll

> [!challenge-strong] On strong hit
> You stay in control and choose two.
> - Mark progress
> - Take +2 momentum
> - Add +1 on your next move (not a progress move)
> > [!cite]- Narrative prompt
> > Envision how the benefits taken applies to the situation of the encounter. ^strong-hit

> [!challenge-weak] On a weak hit
> You stay in control and choose one.
> - Mark progress
> - Take +2 momentum
> - Add +1 on your next move (not a progress move)
> > [!cite]- Narrative prompt
> > Envision how the benefit taken applies to the situation of the encounter. ^weak-hit

> [!challenge-miss] On a miss
> You are in a Bad Spot and you must [[SF_CH3_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > Your foe gains the upper hand, the fight moves to a new location, or you encounter a new peril.  Envision how to cost taken impacts the encounter.

## Full Description
This move is the combat-focused version of [[SF_CH3_Secure an Advantage|Secure an Advantage]], used when you are in control to build advantage against a foe or move toward your objective. 

When you Gain Ground, picture the situation. Consider the environment, the gear and tech you bring to bear, and your own abilities. Consider your enemy, and their tactics and readiness. What can you use to your advantage? Envision your action, then make the move.

Since a hit on Gain Ground includes an option to mark progress, you can achieve your objective in a fight without relying solely (or possibly at all) on direct physical violence. This move, unlike others, also lets you stay in control on a weak hit. It’s a powerful option to build momentum and progress.

> [!cite]- Narrative example
> In the upper atmosphere of a Jovian world, your [[AST_Starship|STARSHIP]] is attacked and pursued by a swarm of enemy fighters. You decide to Gain Ground by hiding in an expanse of storm-wracked clouds. Will this throw some of them off your trail? You roll +shadow to find out.

*190 CHAPTER 3: GAMEPLAY IN DEPTH*

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
| **[[SF_CH3_Enter the Fray\|Enter The Fray (SF Moves)]]** | #Starforged/Moves/Combat | **[[SF_CH3_React Under Fire\|React Under Fire (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>
