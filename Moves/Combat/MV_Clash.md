---
Alias: "Clash (move)"
PageType: Move
PageCategory: Combat
InlineCmd: CLASH
Trigger: "When you are in a bad spot and fight back against a foe"
Approach: [["Close quarters"],["From a distance"]]
RollType: Action
RollStat: [Iron, Edge]
---
# [[_Moves Index|Moves]] - [[_Combat Moves|Combat]]: Clash

## Clash: Move Card
>[!abstract]  Trigger and Preparation
>When you are in a bad spot and fight back against a foe...

> [!warning] Action Roll
> At close quarters roll +iron.
> Exchange fire at a distance roll +edge.

> [!challenge-strong] On strong hit
> Mark progress twice and are In Control
> > [!quote] Narrative prompt
> > You overwhelm your foe.  Envision your next steps as the encounter switches to your advantage.

> [!challenge-weak] On a weak hit
> Mark progress but remain in a Bad Spot and must [[MV_Pay the Price|Pay the Price (move)]].
> > [!quote] Narrative prompt
> > While you do make some progress, you are dealt a counterblow or setback.  Envision the cost and how you will react to your foe's next move.

> [!challenge-miss] On a miss
> Remain in a Bad Spot and you must [[MV_Pay the Price|Pay the Price (move)]]
> > [!quote] Narrative prompt
> > Your foe dominates this exchange and you do not make any headway.  What next will the foe do and  how will you try to overcome their advantage.

## Full Description
Make this move when you are in a bad spot and choose to fight back against your foe. 

First, envision your action and the fiction of the exchange. Is this a focused, dramatic moment where you each seek an opening? Or is it a flurry of attacks and counters, advances and retreats? The outcome of the move determines whether your foe presses their advantage, or if you turn the tide and take control. 

On a strong hit, you come out on top. As with the Strike move, mark progress twice per the rank of the objective. 

On a weak hit, you manage to inflict harm or damage and mark progress, but stay in a bad spot. Plus, you must [[MV_Pay the Price|Pay the Price (move)]]. The cost you suffer can be to [[MV_Endure Harm|Endure Harm (move)]] or [[MV_Withstand Damage|Withstand Damage (move)]]. Or you may face some other dramatic outcome as appropriate to the current situation and your foe’s intent. 

The result of a weak hit as you Clash, whether mechanical or purely narrative, should be more dire than the merely troublesome price you face if you [[MV_React Under Fire|React Under Fire (move)]] and score a weak hit. The weak hit with Clash enables you to mark progress, but comes at a cost. This is the risk and reward of wading into the fight. 

On a miss, you fail, don’t mark progress, stay in a bad spot, and must Pay the Price. This fight is turning against you.


> [!quote]- Narrative example
> You are attempting to hold off enemy troopers as your ally frantically preps the [[AST_Starship|Starship (asset)]] for launch. Your foes burst through the docking bay entrance, firing wildly at you and the ship. You level your guns and Clash to shoot back, rolling +edge since you are at a distance. 

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