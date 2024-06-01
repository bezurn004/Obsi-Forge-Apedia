---
Alias: "Missile Array (asset)"
PageType: Asset
PageCategory: Module

Ability1:
Abil1_MovesTrigger:
Abil1_MoveTriggerSE:
Abil1_MovesTake:
Abil1_TriggerNarrative:
Abil1_ActionResultSE:

Ability2:
Abil2_MovesTrigger:
Abil2_MoveTriggerSE:
Abil2_TriggerNarrative:
Abil2_MovesTake:
Abil2_ActionResultSE:

Ability3:
Abil3_MovesTrigger:
Abil3_MoveTriggerSE:
Abil3_TriggerNarrative:
Abil3_MovesTake:
Abil3_Narrative:
Abil3_ActionResultSE:

GameplayRole: Combat
Aspect: "Your missile array is armed with 5 ammo."
PreReqCondition: 
NameNum:
NameLabels:
NameValues:
TrackNum: 1
TrackLabels: Ammo
TrackMin: 0
TrackMax: 5
ConditionNum: 1
ConditionLabels: "Broken"
---
# [[_Assets Index|Assets]] - [[_Module Assets|Module]]: Missile Array

> [!mechanics]- [[AST_Missile Array|Missile Array (asset)]]
> **Module Aspect: ** Your missile array is armed with 5 ammo. 
> > [!warning] Module Status | Ammo | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Broken

^Header

___
> [!note] Ability 1
> - [x] When you [[MV_Strike|Strike]] or [[MV_Clash|Clash]]with a missile attack, suffer -1 ammo and on a hit mark progress. 
> - If you [[MV_Resupply|Resupply]] in a place where your missiles can be replenished, you may exchange any earned +supply for +ammo.

^Ability1

___
> [!info] Ability 2
> - [ ] When you have at least 1 ammo and [[MV_Gain Ground|Gain Ground]] by locking a missile on target, add +1 and on a hit take +1 momentum.

^Ability2

___
> [!todo] Ability 3
> - [ ] When you have at least 3 ammo and [[MV_Take Decisive Action|Take Decisive Action]] by unleashing all of your missiles, roll an action die before making the progress roll. 
> 	- If your action die is equal to or less than ammo, you may reroll any challenge dice. Then, set ammo to 0.

^Ability3

___

#Pedia/Assets/Module 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>