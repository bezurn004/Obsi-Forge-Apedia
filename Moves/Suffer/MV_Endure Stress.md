---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Endure Stress (move)"
PageType: Move
PageCategory: Suffer
PageOrder: 3

## Oracle
MoveName: "Endure Stress"
InlineCmd: ES
Trigger: ["When you face mental strain","When you face mental shock","When you face mental despair"]
RollType: Action
RollStat: [Spirit, Heart]
ReferencedMoves: 
  - [[MV_Hearten]]
  - [[MV_Lose Momentum]]
  - [[MV_Pay the Price]]
  - [[MV_Face Desolution]]
  - [[MV_Forsake Your Vow]]
---
# [[_Moves Index|Moves]] - [[_Suffer Moves|Suffer]]: Endure Stress
## Endure Stress: Move Card
>[!abstract]  Trigger and Preparation
>**When you face mental strain, shock, or despair...** ^trigger

> [!error] Shaken Impact
> When you mark shaken, you cannot regain spirit until you successfully [[MV_Hearten|Hearten]] and clear that impact. ^improper

> [!warning] Action Roll
>- For minor stress, suffer -1
>- For serious stress ,suffer -2
>- For major stress, suffer -3
> If your spirit is 0, [[MV_Lose Momentum|Lose Momentum]] equal to any remaining stress
> Then, if *your spirit is 0* or *you choose* to resist the stress, roll +spirit or +heart, whichever is higher ^action-roll

> [!challenge-strong] On strong hit
> Choose one:
>- Shake it off: Take +1 spirit
>- Embrace the darkness: Take +1 momentum
> > [!cite]- Narrative prompt
> > Envision the how you adjust to the situation and what happens next. ^strong-hit

> [!challenge-weak] On a weak hit
> Choose one:
>- You may [[MV_Lose Momentum|Lose Momentum]] (-1) in exchange for +1 spirit
>- Otherwise, press on
> > [!cite]- Narrative prompt
> > Envision how the stress is dealt with and how you press on ^weak-hit

> [!challenge-miss] On a miss
>  It is worse than you thought, choose one:
>- Suffer an additional -1 spirit
>- [[MV_Lose Momentum|Lose Momentum]] (-2)
> If your spirit is 0, choose one:
>- You must also mark shaken or traumatized
>- Roll on the table below
> > ![[#^table-miss]]
> 
> > [!cite]- Narrative prompt
> > Envision how the stress weakened your resolve and what happens next. ^miss

## Full Description
Make this move when the unnerving perils of the Forge get the best of you, when you are discouraged or disheartened, or when you act against your best intentions. 

When you must [[MV_Pay the Price|Pay the Price]], you can Endure Stress if mental hardship is a fitting outcome of the current situation. Also, moves and assets can prompt you to Endure Stress as a cost or concession, and may indicate a specific amount of stress to suffer, phrased as “Endure Stress (-X).” 

When you Endure Stress, first, reduce your ==spirit meter== by the amount of stress suffered: minor (-1), serious (-2), or major (-3). If the cost is open to interpretation, consider the severity of the situation or nature of your foe. For example: 
- **Minor (-1 spirit):** Doldrums or melancholy; unsettling incident; frustrating failure. 
- **Serious (-2 spirit):** Loneliness or heartache; shocking incident; demoralizing failure; stinging remorse.
- **Major (-3 spirit):** Heart-rending despair; horrifying incident; dreadful failure; profound guilt. 

If in doubt, make it serious. 

If your spirit is reduced to 0, or was already at 0, you must [[MV_Lose Momentum|Lose Momentum]] and apply any remaining -spirit to your momentum meter. For example, if you were at 1 spirit and suffer major stress (-3), reduce your spirit to 0 and apply the remaining -2 to momentum. 

Next, you’ll make a choice: Do you attempt to resist this stress and make an action roll, or suffer the cost and move on? If you are at 0 spirit, you have no choice, you must make the roll. 

If you do make the roll, resolve the outcome as detailed. 
On a strong hit, you are unfazed; take +1 spirit (if you do not have the shaken impact) or +1 momentum. If you are in a fight, this strong hit puts you in control. 

On a weak hit, you can choose to trade -1 momentum for +1 spirit as you take a moment to steady yourself. Otherwise, take the stress and press on. 

On a miss, you must suffer an additional -1 spirit or [[MV_Lose Momentum|Lose Momentum]] (-2). When you score a miss and your spirit is now at 0, you also need to make an important decision. Do you risk the potential of a dire outcome by rolling on the table, or do you suffer an impact? The ==[[GB_Impacts#Burdens|shaken]]== impact is temporary and can be dealt when you successfully [[MV_Hearten|Hearten]]. But becoming ==[[GB_Impacts#Lasting Effects|traumatized]]== is an enduring, life-changing event. 

If you score a miss with 0 spirit and those impacts are already marked, you have no choice. Roll on the table to determine your fate. 

> [!cite]- Narrative example
> While traveling across the glassy lava fields of a furnace world in your [[AST_Exosuit|EXOSUIT]], you are attacked by a massive creature with a rock like hide and powerful, grasping limbs. As the fight turns against you, the beast grapples your [[AST_Exosuit|EXOSUIT]], dragging you to the ground. You [[MV_React Under Fire|React Under Fire]] to push it away, but roll a miss. You envision internal alarms blaring as the suit buckles under the pressure. The slavering jaws of the creature are only inches from your face. This seems like an appropriate moment to Endure Stress.

### Endure Stress Miss Table
| 1d100 | Result |
|:---:| --- |
| 1–10 | You are overwhelmed. [[MV_Face Desolution\|Face Desolution]]. |
| 11–25 | You give up. [[MV_Forsake Your Vow\|Forsake Your Vow]]. |
| 26–50 | You give in to fear or compulsion, and act against your better instincts. |
| 51–100 | You persevere. |
^table-miss

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
| **[[MV_Endure Harm\|Endure Harm (move)]]** | #Pedia/Moves/Suffer | **[[MV_Companion Takes a Hit\|Companion Takes a Hit (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>