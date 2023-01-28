---
Name: "React Under Fire"
PageType: Move
PageCategory: Combat
InlineCmd: RUF
RollType: Action
RollStat: [Edge, Heart, Iron, Shadow, Wits]
Trigger: [""]
---
# [[_Moves Index|Moves]]: React Under Fire
### Categories: [[_Combat Moves|Combat Moves]]
>[!abstract]  Context and Preparation
>When you are in a bad spot and take action in a fight to avoid danger or overcome an obstacle...

> [!error]- Improper Usage
> If you are in a bad spot and choose to fight back, you should instead [Clash](z_Obsi-Forge-Apedia/Moves/Combat/Clash.md) to resolve your action. React Under Fire is often less risky, since you can use a favored stat, the penalty on a weak hit is relatively mild, and a strong hit can put you in good position for a follow-up move. But unlike Clash, you won’t have an opportunity to mark progress on a hit.

> [!tip]- Group Play
> This move cannot be made to cover for an ally.

> [!warning] Action Roll
> Envision your approach and roll. If you are...
> -   In pursuit, fleeing, dodging, getting back into position, or taking cover: Roll +edge
> -   Remaining stalwart against fear or temptation: Roll +heart
> -   Blocking or diverting with force, or taking the hit: Roll +iron
> -   Moving into hiding or creating a distraction: Roll +shadow
> -   Changing the plan, finding a way out, or cleverly bypassing an obstacle: Roll +wits

> [!challenge-strong] On strong hit
> You succeed and are In Control and Take +1 momentum.
> > [!quote] Narrative prompt
> > Envision how your actions have gained you control in the encounter.

> [!challenge-weak] On a weak hit
> You are in a bad spot and must Make a [[_Suffer Moves]] (-1)
> > [!quote] Narrative prompt
> >  You avoid the worst of the danger or overcome the obstacle, but not without a cost.

> [!challenge-miss] On a miss
> You are in a Bad Spot and must [[Pay the Price]].
> > [!quote] Narrative prompt
> > Envision how the situation has worsened. How will you react to turn the encounter in your favor?

## Full Description
React Under Fire is the combat-focused version of Face Danger, and is used instead of that move in a fight. When you are in a bad spot and try to get out of harm’s way, focus on defense, resist a foe’s attempt to gain advantage, or get past an obstacle, make this move. 

React Under Fire is often done in response to a foe who is trying to gain advantage through an action other than a direct attack. The enemy commander taunts you over the ship’s comms, trying to fluster you or provoke a reckless response. A trooper moves into position to get a shot at you from cover. A creature leaps at you, putting you off-balance for a follow-up attack. What do you do? Envision it, then make the move. 

> [!quote]- Narrative example
> You are chasing an enemy agent through the corridors of an orbital station. You roll a miss as you Gain Ground, and are now in a bad spot. You envision rounding a corner to find the agent unleashing a spray of gunfire. You React Under Fire by leaping behind cover, and roll +edge. 

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