---
Name: "Gain Ground"
PageType: Move
PageCategory: Combat
InlineCmd: GG
InlineCmd:
RollType: Action
RollStat: [Edge, Heart, Iron, Shadow, Wits]
Trigger: [""]
---
# [[_Moves Index|Moves]]: Gain Ground
### Categories: [[_Combat Moves|Combat Moves]]
>[!abstract]  Context and Preparation
>When you are in control and take action in a fight to reinforce your position or move toward an objective...

> [!error]- Improper Usage
> If you are instead acting to inflict direct harm or damage while you are in control, make the [Strike](z_Obsi-Forge-Apedia/Moves/Combat/Strike.md) move.

> [!tip]- Group Play
> To assist another player with their narrative situation, make the move [[Aid Your Ally]] to provide them the benefit of your actions instead.

> [!warning] Action Roll
> Envision your approach and roll. If you are...
> 
> - In pursuit, fleeing, or maneuvering: Roll +edge
> - Charging boldly into action, coming to the aid of others, negotiating, or commanding: Roll +heart
> - Gaining leverage with force, powering through, or making a threat: Roll +iron
> - Hiding, preparing an ambush, or misdirecting: Roll +shadow
> - Coordinating a plan, studying a situation, or cleverly gaining leverage: Roll +wits

> [!challenge-strong] On strong hit
> You stay in control and choose two.
> - Mark progress
> - Take +2 momentum
> - Add +1 on your next move (not a progress move)
> > [!quote] Narrative prompt
> > Envision how the benefits taken applies to the situation of the encounter.

> [!challenge-weak] On a weak hit
> You stay in control and choose one.
> - Mark progress
> - Take +2 momentum
> - Add +1 on your next move (not a progress move)
> > [!quote] Narrative prompt
> > Envision how the benefit taken applies to the situation of the encounter.

> [!challenge-miss] On a miss
> You are in a Bad Spot and you must [[Pay the Price]].
> > [!quote] Narrative prompt
> > Your foe gains the upper hand, the fight moves to a new location, or you encounter a new peril.  Envision how to cost taken impacts the encounter.

## Full Description
This move is the combat-focused version of Secure an Advantage, used when you are in control to build advantage against a foe or move toward your objective. 

When you Gain Ground, picture the situation. Consider the environment, the gear and tech you bring to bear, and your own abilities. Consider your enemy, and their tactics and readiness. What can you use to your advantage? Envision your action, then make the move.

Since a hit on Gain Ground includes an option to mark progress, you can achieve your objective in a fight without relying solely (or possibly at all) on direct physical violence. This move—unlike others—also lets you stay in control on a weak hit. It’s a powerful option to build momentum and progress.

> [!quote]- Narrative example
> In the upper atmosphere of a Jovian world, your STARSHIP is attacked and pursued by a swarm of enemy fighters. You decide to Gain Ground by hiding in an expanse of storm-wracked clouds. Will this throw some of them off your trail? You roll +shadow to find out

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
