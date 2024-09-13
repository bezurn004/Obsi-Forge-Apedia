---
## Source
SourceMaterial: "Ironsworn: Sundered Isles"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: SI

## Page
aliases:
  - "LONGBOAT"
  - "Long Boat (asset)"
PageType: Asset
PageCategory: "Support Vehicle"
PageOrder: 22

## Ability1
Abil1: true
Abil1_MovesTrigger: 
Abil1_MoveTriggerSE: 
Abil1_MovesTake: 
Abil1_TriggerNarrative: 
Abil1_ActionResultSE: 

## Ability2
Abil2: false
Abil2_MovesTrigger: 
Abil2_MoveTriggerSE: 
Abil2_TriggerNarrative: 
Abil2_MovesTake: 
Abil2_ActionResultSE: 

## Ability3
Abil3: false
Abil3_MovesTrigger: 
Abil3_MoveTriggerSE: 
Abil3_TriggerNarrative: 
Abil3_MovesTake: 
Abil3_Narrative: 
Abil3_ActionResultSE: 

## Properties
AssetName: "LONGBOAT"
GameplayRole: 
Aspect: "Your longboat transports crew, passengers, and cargo to and from your flagship."
PreReqCondition: 
NameNum: 1
NameLabels: Name
NameValues: 
TrackNum: 1
TrackLabels: Integrity
TrackMin: 0
TrackMax: 4
ConditionNum: 1
ConditionLabels: Battered
---
# [[_Assets Index|Assets]] - [[_Vehicle Assets|Support Vehicle]]: Longboat

> [!mechanics]- [[AST_Longboat|LONGBOAT]]
> **Aspect:** Your longboat transports crew, passengers, and cargo to and from your flagship.
> > [!warning] <input type=texbox value="InsertName"> | Integrity | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Battered ^Header
 ___
> [!note] Ability 1
> - [x] When you (or a landing party under your command) use the craft to haul provisions as you [[SF_CH3_Resupply|Resupply]], you may roll +integrity.
> - If you do, on **a hit,** take either...
> 	- +1 supply
> 	- +1 momentum. ^Ability1
___
> [!info] Ability 2
> **Aspect:** Your longboat is reinforced to endure storms, shoals, and cannon fire.
> - [ ] When you [[SF_CH3_Withstand Damage|Withstand Damage]] and score a **miss,** reroll any dice. #ambiguous _only when taking the damage to the longboat presumably_
> - When you [[SF_CH3_Repair|Repair]] a battered longboat, clear the impact for 1 repair point (instead of 2). ^Ability2
___
> [!todo] Ability 3
> **Aspect:** Your crew is trained for a stealthy approach.
> - [ ] When you [[SF_CH3_Face Danger|Face Danger]] or [[SF_CH3_Gain Ground|Gain Ground]] using your longboat to board an enemy vessel or land on hostile shores, on **a hit,** add +1 and take +1 momentum. ^Ability3
___
## Tags

| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Flying Machine\|FLYING MACHINE]]** | #SunderedIsles/Assets/SupportVehicle - #AssetDeck/SunderedIsles | **[[AST_Cannoner\|CANNONEER]]** |

<font size=-2>Copyright ©2024 Shawn Tomkin. The text of this work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license. For license details, visit ironswornrpg.com. Updated June 2024 MUH051V200-PDF</font>