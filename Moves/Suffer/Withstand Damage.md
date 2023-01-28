---
Name: "Withstand Damage"
PageType: Move
PageCategory: Suffer
InlineCmd: WD
RollType: Action
RollStat: Integrity
Trigger: [""] 
Stats: []
---
# [[_Moves Index|Moves]]: Withstand Damage
### Categories: [[_Suffer Moves|Suffer Moves]]
>[!abstract]  Context and Preparation
>When your vehicle faces a damaging situation or environment...

> [!error] Battered and Broken
> When you mark a vehicle as battered, you cannot regain integrity until you successfully [Repair](z_Obsi-Forge-Apedia/Moves/Recover/Repair.md) and spend repair points to clear that impact. 
> When a module is marked as broken, you cannot benefit from its abilities until you [Repair](z_Obsi-Forge-Apedia/Moves/Recover/Repair.md) and spend repair points to fix it.

> [!warning] Action Roll
>  Depending on the type: 
>- Minor damage, suffer -1 integrity
>- Serious damage, suffer -2 integrity
>- Major damage, suffer -3 integrity
>If your integrity is 0, [[Lose Momentum]] equal to any remaining damage. 
>
>Then, if *your integrity is 0* or *you choose* to resist the damage, roll +integrity.

> [!challenge-strong] On strong hit
> Choose one:
>-  Bypass: Take +1 integrity
>-  Ride it out: Take +1 momentum
>You are now In Control if in an encounter
> > [!quote] Narrative prompt
> > Envision how you overcome the hit to your vehicle and take control.

> [!challenge-weak] On a weak hit
> Choose one:
>- You may Lose Momentum (-1) in exchange for +1 integrity.
>- Otherwise, press on
> > [!quote] Narrative prompt
> > Envision the damage taken and how you press on.

> [!challenge-miss] On a miss
> Choose one:
>- Suffer an additional -1 integrity
>- Lose Momentum (-2). 
>
>If your integrity is 0, also suffer a cost according to the vehicle type
>- Command vehicle: 
>	- Mark the vehicle as battered or cursed
>	- Mark a module as broken
>	- Destroy a broken module by discarding it
>	- Roll on the table below. 
>If the command vehicle is destroyed, [[Overcome_Destruction]].
>- Support vehicle: 
>	- Mark the vehicle as battered
>	- Roll on the table below.
>If the vehicle is destroyed, discard the asset.
>- Incidental vehicle: Roll on the table below
>
> > [!quote] Narrative prompt
> > Envision the major consequence to the vehicle and what happens next.

| Roll | Result |
| --- | --- |
| 1–10 | Immediate catastrophic destruction. All aboard must [[Endure Harm]] or [[Face Death]], as appropriate. |
| 11–25 | Destruction is imminent and unavoidable. If you do not have the means or intention to get clear, [[Endure Harm]] or [[Face Death]], as appropriate. |
| 26–40 | Destruction is imminent, but can be averted if you [Repair](z_Obsi-Forge-Apedia/Moves/Recover/Repair.md) your vehicle and raise its integrity above 0. If you fail, see 11–25. |
| 41–55 | You cannot Repair this vehicle until you [Resupply](z_Obsi-Forge-Apedia/Moves/Recover/Resupply.md) and obtain a crucial replacement part. If you roll this result again prior to that, see 11–25. |
| 56–70 | The vehicle is crippled or out of your control. To get it back in action, you must [Repair](z_Obsi-Forge-Apedia/Moves/Recover/Repair.md) and raise its integrity above 0. |
| 71–85 | It’s a rough ride. All aboard must make the [[Endure Harm]], [[Endure Stress]], or [[Companion Takes a Hit]] move, suffering a serious (-2) cost. |
| 86–95 | You’ve lost fuel, energy, or cargo. [[Sacrifice Resources]] (-2). |
| 96–100 | Against all odds, the vehicle holds together |

## Full Description
Make this move when your command vehicle, support vehicle, or incidental vehicle (page 65) suffers enemy fire, collisions, mechanical failures, hazardous environments, the crushing embrace of a giant space squid, or any other damaging situation. 

When you must [[Pay the Price]], you can Withstand Damage if damage to your vehicle is a fitting outcome of the current situation. Also, moves and assets can prompt you to Withstand Damage as a cost or concession, and may indicate a specific amount of damage to suffer, phrased as “Withstand Damage (-X).” 

First, reduce the vehicle’s integrity meter by the amount of damage suffered: minor (-1), serious (-2), or major (-3). If the cost is open to interpretation, consider the severity of the situation or nature of your foe. For example: 
* Minor (-1 integrity): Wear and tear; incidental hits and bumps
* Serious (-2 integrity): Weapons fire; collisions; hull or engine stress
* Major (-3 integrity): Powerful weapon hits; destructive impact; explosions; hull breaches; systems failure
If in doubt, make it serious. 

If your integrity is reduced to 0, or was already at 0, you must Lose Momentum and apply any remaining -integrity to your momentum meter. For example, if you were at 1 integrity and suffer major damage (-3), reduce the integrity to 0 and apply the remaining -2 to momentum. 

Next, you’ll make a choice: Do you attempt to resist this damage and make an action roll, or suffer the cost and move on? If you are at 0 integrity, you have no choice, you must make the roll. 

If you do make the roll, resolve the outcome as detailed. 
On a strong hit, your vehicle holds together; take +1 integrity (if your vehicle does not have the battered impact) or +1 momentum. If you are in a fight, this strong hit puts you in control. 

On a weak hit, you can choose to trade -1 momentum for +1 integrity as you shunt power between systems or ease off the throttle. Otherwise, take the damage and press on. 

On a miss, you must suffer an additional -1 integrity to the vehicle or Lose Momentum (-2). When you score a miss and your integrity is now at 0, you also need to choose an additional cost according to your vehicle type. 

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
#Pedia/Moves/Suffer 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>