---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Strike (move)"
PageType: Move
PageCategory: Combat
PageOrder: 4

## Move
MoveName: Strike
InlineCmd: STRIKE
Trigger: "When you are in control and assault a foe from"
Approach: [["Close quarters"],["A distance"]]
RollType: Action
RollStat: [Edge, Iron]
ReferencedMoves: 
  - [[MV_Pay the Price]]
  - [[MV_Endure Harm]]
  - [[MV_Withstand Damage]]
  - [[MV_Lose Momentum]]
---
# [[_Moves Index|Moves]] - [[_Combat Moves|Combat]]: Strike
## Strike: Move Card
>[!abstract]  Trigger and Preparation
>**When you are in control and assault a foe from...** ^trigger

> [!warning] Action Roll
>- Close quarters roll +iron
>- A distance roll +edge ^action-roll

> [!challenge-strong] On strong hit
> Mark progress twice. You dominate your foe and stay in control.
> > [!cite]- Narrative prompt
> > Envision the reaction from your foe and how you continue to press the advantage. ^strong-hit

> [!challenge-weak] On a weak hit
> Mark progress twice, but you expose yourself to danger. You are in a bad spot.
> > [!cite]- Narrative prompt
> > Envision how you will be react to the foe taking control of the encounter. ^weak-hit

> [!challenge-miss] On a miss
> You are in a bad spot and must [[MV_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > The fight turns against you. Envision what price you have paid and how you will try to find a better position. ^miss

## Full Description
Make this move when you are in control and act to inflict harm or damage against your foe. 

Narratively, this move might represent a focused moment in time—a quick scuffle, a carefully aimed rifle shot, or the flight of a missile. Or it can depict an extended exchange as you attempt to keep your opponent on the defensive. Zoom in and out as appropriate to the scope of the fight. 

On a strong hit, you strike true. Envision the outcome and mark progress twice per the rank of the objective. For example, against a dangerous objective you would mark two boxes twice, or four full progress boxes. Any instance of “mark progress” gained through an asset ability stack with that result, allowing you to mark additional ticks or boxes per the rank of the challenge. See [[GB_Progress Tracks#Stacking Progress|stacking progress ]] for details. 

Narratively, a strong hit represents wounding or damaging an enemy, or wearing them down. You are in control and can envision your next action. 

On a weak hit, you’ve done some damage but are overextended or gave your enemy an opportunity. You mark progress twice, and are in a bad spot. How does your foe respond? 

On a miss, you must [[MV_Pay the Price|Pay the Price]]. Envision a price that fits the circumstances. Your opponent strikes back, and you [[MV_Endure Harm|Endure Harm]] or [[MV_Withstand Damage|Withstand Damage]]. You sacrifice position or advantage and [[MV_Lose Momentum|Lose Momentum]]. A companion or ally is put in harm’s way. Your weapon is out of ammo. A new danger reveals itself. Let the outcome flow out of the fiction, or roll on the [[MV_Pay the Price#Pay the Price Table|Pay the Price table]] to see what happens.

> [!cite]- Narrative example
> You are in the gun turret of your starship, helping fight a pack of enemy fighters. You are in control, and holding your shot until the last possible moment as a fighter swoops by at close range. You swivel the cannon, press the trigger, and Strike +iron to unleash a barrage of devastating fire.

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
| **[[MV_React Under Fire\|React Under Fire (move)]]** | #Pedia/Moves/Combat | **[[MV_Clash\|Clash (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>