---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Withstand Damage (move)"
PageType: Move
PageCategory: Suffer
PageOrder: 6

## Oracle
MoveName: "Withstand Damage"
InlineCmd: WD
Trigger: ["When your vehicle faces a damaging situation","When your vehicle faces damaging environment"]
RollType: Action
RollStat: Integrity
ReferencedMoves: 
  - [[MV_Repair]]
  - [[MV_Lose Momentum]]
  - [[MV_Overcome Destruction]]
  - [[MV_Endure Harm]]
  - [[MV_Face Death]]
  - [[MV_Resupply]]
  - [[MV_Endure Stress]]
  - [[MV_Companion Takes a Hit]]
  - [[MV_Sacrifice Resources]]
---
# [[_Moves Index|Moves]] - [[_Suffer Moves|Suffer]]: Withstand Damage
## Withstand Damage: Move Card
>[!abstract]  Trigger and Preparation
>**When your vehicle faces a damaging situation or environment**... ^trigger

> [!error] Battered and Broken
> When you mark a vehicle as battered, you cannot regain integrity until you successfully [[MV_Repair|Repair]] and spend repair points to clear that impact. 
> When a module is marked as broken, you cannot benefit from its abilities until you [[MV_Repair|Repair]] and spend repair points to fix it. ^impact

> [!warning] Action Roll
>  Depending on the type: 
>- **Minor damage**, suffer -1 integrity
>- **Serious damage**, suffer -2 integrity
>- **Major damage**, suffer -3 integrity
>If your integrity is 0, [[MV_Lose Momentum|Lose Momentum]] equal to any remaining damage. 
>Then, if *your integrity is 0* or *you choose* to resist the damage, roll +integrity. ^action-roll

> [!challenge-strong] On strong hit
> You are now In Control if in an encounter
>Choose one:
>-  Bypass: Take +1 integrity
>-  Ride it out: Take +1 momentum
> > [!cite]- Narrative prompt
> > Envision how you overcome the hit to your vehicle and take control. ^strong-hit

> [!challenge-weak] On a weak hit
> Choose one:
>- You may [[MV_Lose Momentum|Lose Momentum]] (-1) in exchange for +1 integrity.
>- Otherwise, press on
> > [!cite]- Narrative prompt
> > Envision the damage taken and how you press on. ^weak-hit

> [!challenge-miss] On a miss
> Choose one:
>- Suffer an additional -1 integrity
>- [[MV_Lose Momentum|Lose Momentum]] (-2). 
>If your integrity is 0, also suffer a cost according to the vehicle type
>- Command vehicle: 
>	- Mark the vehicle as battered or cursed
>	- Mark a module as broken
>	- Destroy a broken module by discarding it
>	- Roll on the table below. 
>If the command vehicle is destroyed, [[MV_Overcome Destruction|Overcome Destruction]].
>- Support vehicle: 
>	- Mark the vehicle as battered
>	- Roll on the table below.
>If the vehicle is destroyed, discard the asset. #consider %%add move card for Discard Asset%%
>- Incidental vehicle: Roll on the table below
> > ![[#^table-miss]]
>
> > [!cite]- Narrative prompt
> > Envision the major consequence to the vehicle and what happens next.

## Full Description
Make this move when your ==[[GB_Vehicles#Command Vehicle|command vehicle]]==, ==[[GB_Vehicles#Support Vehicles|support vehicle]]==, or ==[[GB_Vehicles#Incidental Vehicles|incidental vehicle]]== suffers enemy fire, collisions, mechanical failures, hazardous environments, the crushing embrace of a giant space squid, or any other damaging situation. 

When you must [[MV_Pay the Price|Pay the Price]], you can Withstand Damage if damage to your vehicle is a fitting outcome of the current situation. Also, moves and assets can prompt you to Withstand Damage as a cost or concession, and may indicate a specific amount of damage to suffer, phrased as “Withstand Damage (-X).” 

First, reduce the vehicle’s integrity meter by the amount of damage suffered: minor (-1), serious (-2), or major (-3). If the cost is open to interpretation, consider the severity of the situation or nature of your foe. For example: 
* **Minor (-1 integrity):** Wear and tear; incidental hits and bumps
* **Serious (-2 integrity):** Weapons fire; collisions; hull or engine stress
* **Major (-3 integrity):** Powerful weapon hits; destructive impact; explosions; hull breaches; systems failure
If in doubt, make it serious. 

If your integrity is reduced to 0, or was already at 0, you must [[MV_Lose Momentum|Lose Momentum]] and apply any remaining -integrity to your momentum meter. For example, if you were at 1 integrity and suffer major damage (-3), reduce the integrity to 0 and apply the remaining -2 to momentum. 

Next, you’ll make a choice: Do you attempt to resist this damage and make an action roll, or suffer the cost and move on? If you are at 0 integrity, you have no choice, you must make the roll. 

If you do make the roll, resolve the outcome as detailed. 
On a strong hit, your vehicle holds together; take +1 integrity (if your vehicle does not have the battered impact) or +1 momentum. If you are in a fight, this strong hit puts you in control. 

On a weak hit, you can choose to trade -1 momentum for +1 integrity as you shunt power between systems or ease off the throttle. Otherwise, take the damage and press on. 

On a miss, you must suffer an additional -1 integrity to the vehicle or [[MV_Lose Momentum|Lose Momentum]] (-2). When you score a miss and your integrity is now at 0, you also need to choose an additional cost according to your vehicle type.

### Withstand Damage Table
| 1d100 | Result |
|:---:| --- |
| 1–10 | Immediate catastrophic destruction. All aboard must [[MV_Endure Harm\|Endure Harm]] or [[MV_Face Death\|Face Death]], as appropriate. |
| 11–25 | Destruction is imminent and unavoidable. If you do not have the means or intention to get clear, [[MV_Endure Harm\|Endure Harm]] or [[MV_Face Death\|Face Death]], as appropriate. |
| 26–40 | Destruction is imminent, but can be averted if you [[MV_Repair\|Repair]] your vehicle and raise its integrity above 0. If you fail, see 11–25. |
| 41–55 | You cannot Repair this vehicle until you [[MV_Resupply\|Resupply]] and obtain a crucial replacement part. If you roll this result again prior to that, see 11–25. |
| 56–70 | The vehicle is crippled or out of your control. To get it back in action, you must [[MV_Repair\|Repair]] and raise its integrity above 0. |
| 71–85 | It’s a rough ride. All aboard must make the [[MV_Endure Harm\|Endure Harm]], [[MV_Endure Stress\|Endure Stress]], or [[MV_Companion Takes a Hit\|Companion Takes a Hit]], suffering a serious (-2) cost. |
| 86–95 | You’ve lost fuel, energy, or cargo. [[MV_Sacrifice Resources\|Sacrifice Resources]] (-2). |
| 96–100 | Against all odds, the vehicle holds together |
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
| Previous Page | Tags | Next Section |
|:--- |:---:| ---:|
| **[[MV_Sacrifice Resources\|Sacrafice Resources (move)]]** | #Pedia/Moves/Suffer | **[[_Recover Moves\|Recover Moves]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>