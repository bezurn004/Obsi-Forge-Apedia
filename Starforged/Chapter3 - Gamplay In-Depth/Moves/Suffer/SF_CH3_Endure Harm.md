---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Endure Harm (SF Moves)"
PageType: Move
PageCategory: Suffer
PageOrder: 2

## Move
MoveName: "Endure Harm"
InlineCmd: EH
Trigger: ["When you face physical injury","When you face fatigue","When you face illness"]
RollType: Action
RollStat: Health
ReferencedMoves: 
  - [[SF_CH3_Heal]]
  - [[SF_CH3_Lose Momentum]]
  - [[SF_CH3_Face Death]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Suffer Moves|Suffer]]: Endure Harm
## Endure Harm: Move Card
>[!abstract]  Trigger and Preparation
>**When you face physical injury, fatigue, or illness...** ^trigger

> [!error]- Wounded Impact
> When you mark [[SF_CH1_Impacts#Misfortunes|wounded]], you cannot regain health until you successfully [[SF_CH3_Heal|Heal]] and clear that impact. ^wounded-impact

> [!warning] Action
>- For minor harm, suffer -1
>- For serious harm, suffer -2
>- For major harm, suffer -3
> If your health is 0. [[SF_CH3_Lose Momentum|Lose Momentum]] equal to any remaining harm.
> > [!warning] Action Roll
> > Then, if your **health is 0** or **you choose to resist** the harm 
> > roll +health or +iron, whichever is higher. ^action

> [!challenge-strong] On strong hit
> Choose one:
>- Shake it off: Take +1 health
>- Embrace the pain: Take +1 momentum
>If you are in an encounter you are In Control
> > [!cite]- Narrative prompt
> > Envision how the harm has emboldened you to take the next action. ^strong-hit

> [!challenge-weak] On a weak hit
>-  You may [[SF_CH3_Lose Momentum|Lose Momentum]] (-1) in exchange for +1 health. 
>-  Otherwise, press on.
> > [!cite]- Narrative prompt
> > Envision what happens next ^weak-hit

> [!challenge-miss] On a miss
>  Suffer an additional -1 health or [[SF_CH3_Lose Momentum|Lose Momentum]] (-2). 
>  If your health is 0, choose one:
>- You must also mark wounded or permanently harmed
>- Roll on the table below.
> > ![[#^table-miss]]
> 
> > [!cite]- Narrative prompt
> > Envision the consequence of the result from this new setback ^miss
## Full Description
Make this move when you bear the brunt of a physical attack or impact, are exposed to harmful environments, are stricken with disease or sickness, or face a wearying undertaking. 

When you must Pay the Price, you can Endure Harm if physical harm is a fitting outcome of the current situation. Also, moves and assets can prompt you to Endure Harm as a cost or concession, and may indicate a specific amount of stress to suffer, phrased as “Endure Harm (-X).” 

> [!cite]- Narrative example
> You Face Danger to help extinguish a shipboard fire, and roll a weak hit. You’ve succeeded, but must face a troublesome cost. You envision the heat and smoke wearing you down, and Endure Harm.

*200 CHAPTER 3: GAMEPLAY IN DEPTH*

When you Endure Harm, first, reduce your health meter by the amount of harm suffered: minor (-1), serious (-2), or major (-3). If the cost is open to interpretation, consider the severity of the situation or nature of your foe. For example: 
- **Minor (-1 health):** Unarmed brawl; taking hits from a simple weapon; bumps and bruises; lesser creature attack; tiring effort; mild sickness; exposure to an unhealthy environment. 
- **Serious (-2 health):** Powerful unarmed assault; forceful impact; small arms fire; deadly creature attack; draining effort; lingering sickness; exposure to a toxic environment. 
- **Major (-3 health):** Heavy weaponry; mighty creature attack; stunning injury; exhausting effort; exposure to a deadly environment. 
- 
If in doubt, make it serious. 

If your health is reduced to 0, or was already at 0, you must [[SF_CH3_Lose Momentum|Lose Momentum]] and apply any remaining -health to your momentum meter. For example, if you were at 1 health and suffer major harm (-3), reduce your health to 0 and apply the remaining -2 to momentum. 

Next, you’ll make a choice: Do you attempt to resist this harm and make an action roll, or suffer the cost and move on? If you are at 0 health, you have no choice, you must make the roll. 

If you do make the roll, resolve the outcome as detailed. 
On a strong hit, you are undaunted; take +1 health or +1 momentum. If you are in a fight, this strong hit puts you in control.

On a weak hit, you can choose to trade -1 momentum for +1 health as you roll with the punches. Otherwise, take the harm and press on. 

On a miss, you must suffer an additional -1 health or [[SF_CH3_Lose Momentum|Lose Momentum]] (-2). When you score a miss and your health is now at 0, you also need to make an important decision. Do you risk the potential of a dire outcome by rolling on the table, or do you suffer an impact? The [[SF_CH1_Impacts#Misfortunes|wounded impact]] is temporary and can be dealt when you successfully [[SF_CH3_Heal|Heal]]. But becoming [[SF_CH1_Impacts#Lasting Effects|permanetly harmed]] is an enduring, life changing event. 

If you score a miss with 0 health and those impacts are already marked, you have no choice. Roll on the table to determine your fate.

*201 SUFFER MOVES*

## Endure Harm Miss Table
| dice: 1d100 | `dice: [[SF_CH3_Endure Harm#^table-miss]]` |
| :---: | --- |
| 1–10 | You suffer mortal harm. [[SF_CH3_Face Death\|Face Death]]. |
| 11–20 | You are dying. Within an hour or two, you must [[SF_CH3_Heal\|Heal]] and raise your health above 0, or [[SF_CH3_Face Death\|Face Death]]. |
| 21–35 | You are unconscious and out of action. If left alone, you come back to your senses in an hour or two. If you are vulnerable to ongoing harm, [[SF_CH3_Face Death\|Face Death]] |
| 36–50 | You are reeling. If you engage in any vigorous activity before taking a breather, roll on this table again (before resolving the other move). |
| 51–100 | You are still standing |
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

## Tags)
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[SF_CH3_Lose Momentum\|Lose Momentum (SF Moves)]]** | #Starforged/Moves/Suffer | **[[SF_CH3_Endure Stress\|Endure Stress (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>