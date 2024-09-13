---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "React Under Fire (SF Moves)"
PageType: Move
PageCategory: Combat
PageOrder: 3

## Move
MoveName: React Under Fire
InlineCmd: RUF
Trigger: 
- "When you are in a bad spot&"
- "Take action in a fight to avoid danger|"
- "Overcome an obstacle"
Approach: 
- "(Edge) Pursuit,Fleeing,Dodging,Getting back into position,Taking cover"
- "(Heart) Remaining stalwart against fear,Remaining stalwart against temptation"
- "(Iron) Blocking with force,Diverting with force,Taking the hit"
- "(Shadow) Moving into hiding,Creating a distraction"
- "(Wits) Changing the plan,Finding a way out,Cleverly bypassing an obstacle"
RollType: Action
RollStat: 
- Edge
- Heart
- Iron
- Shadow
- Wits

ReferencedMoves: 
  - [[SF_CH3_Clash]]
  - [[SF_CH3_Companion Takes a Hit]]
  - [[SF_CH3_Endure Harm]]
  - [[SF_CH3_Endure Stress]]
  - [[SF_CH3_Lose Momentum]]
  - [[SF_CH3_Sacrifice Resources]]
  - [[SF_CH3_Withstand Damage]]
  - [[SF_CH3_Pay the Price]]
  - [[SF_CH3_Face Danger]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Combat Moves|Combat]]: React Under Fire
## React Under Fire: move Card
>[!abstract]  Trigger and Preparation
>**When you are in a bad spot and take action in a fight to avoid danger or overcome an obstacle...** ^ttrigger

> [!error]- Improper Usage
> If you are in a bad spot and choose to fight back, you should instead [[SF_CH3_Clash|Clash]] to resolve your action. React Under Fire is often less risky, since you can use a favored stat, the penalty on a weak hit is relatively mild, and a strong hit can put you in good position for a follow-up move. But unlike [[SF_CH3_Clash|Clash]], you won’t have an opportunity to mark progress on a hit. ^improper

> [!tip]- Group Play
> This move cannot be made to cover for an ally. ^group-play

> [!warning] Action Roll
> Envision your approach and roll. If you are...
> -   In pursuit, fleeing, dodging, getting back into position, or taking cover: Roll +edge
> -   Remaining stalwart against fear or temptation: Roll +heart
> -   Blocking or diverting with force, or taking the hit: Roll +iron
> -   Moving into hiding or creating a distraction: Roll +shadow
> -   Changing the plan, finding a way out, or cleverly bypassing an obstacle: Roll +wits ^action-roll

> [!challenge-strong] On strong hit
> You succeed and are In Control and Take +1 momentum.
> > [!cite]- Narrative prompt
> > Envision how your actions have gained you control in the encounter. ^strong-hit

> [!challenge-weak] On a weak hit
> You are in a bad spot and must Make a [[_SF_CH3_Suffer Moves|Suffer Move]] (-1)
> > [!cite]- Narrative prompt
> >  You avoid the worst of the danger or overcome the obstacle, but not without a cost. ^weak-hit

> [!challenge-miss] On a miss
> You are in a Bad Spot and must [[SF_CH3_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > Envision how the situation has worsened. How will you react to turn the encounter in your favor? ^miss

## Full Description
React Under Fire is the combat-focused version of [[SF_CH3_Face Danger|Face Danger]], and is used instead of that move in a fight. When you are in a bad spot and try to get out of harm’s way, focus on defense, resist a foe’s attempt to gain advantage, or get past an obstacle, make this move. 

React Under Fire is often done in response to a foe who is trying to gain advantage through an action other than a direct attack. The enemy commander taunts you over the ship’s comms, trying to fluster you or provoke a reckless response. A trooper moves into position to get a shot at you from cover. A creature leaps at you, putting you off-balance for a follow-up attack. What do you do? Envision it, then make the move. 

> [!cite]- Narrative example
> You are chasing an enemy agent through the corridors of an orbital station. You roll a miss as you [[SF_CH3_Gain Ground|Gain Ground]], and are now in a bad spot. You envision rounding a corner to find the agent unleashing a spray of gunfire. You React Under Fire by leaping behind cover, and roll +edge. 

*181 COMBAT MOVES*

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
| **[[SF_CH3_Gain Ground\|Gain Ground (SF Moves)]]** | #Starforged/Moves/Combat | **[[SF_CH3_Strike\|Strike (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>