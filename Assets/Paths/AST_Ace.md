---
Alias: "Ace (asset)"
PageType: Asset
PageCategory: Path

Ability1: true
Abil1_MovesTrigger: ["Face Danger","React Under Fire"]
Abil1_MoveTriggerSE: "+1(AR)"
Abil1_MovesTake: 
Abil1_Narrative: ["guiding your vehicle through a hazard","guiding your vehicle out of harm’s way"]
Abil1_ActionResultSE: "?(ARo = 1 | ARo = 2):+1(MOM)"

Ability2: false
Abil2_MovesTrigger: "Gain Ground"
Abil2_MoveTriggerSE: "?(AD = 6 | AD = 5 | AD = 4):(holdAD = 'true', heldAD = AD.value)"
Abil2_TriggerNarrative: "maneuvering your vehicle against a foe"
Abil2_MovesTake: "Strike"
Abil2_ActionResultSE: "?(AD = 'held')"
Abil2_DetriggerNarratie: ["fail to Strike with a strong hit","make another move which changes your vehicle’s position"]

Ability3: false
Abil3_MovesTrigger: "Endure Stress"
Abil3_MoveTriggerSE: 
Abil3_TriggerNarrative: "while piloting a vehicle"
Abil3_MovesTake:
Abil3_ActionResultSE: "?(AR => 2): +1(MOM)"

GameplayRole: Adventure
Aspect:
PreReqCondiation: 
NameNum:
NameLabels:
NameValues:
TrackNum:
TrackLabes:
TrackMin:
TrackMax:
ConditionNum:
ConditionLabels:
---
# [[_Assets Index|Assets]] - [[_Path Assets|Path]]: Ace

> [!mechanics]- [[AST_Ace|Ace (asset)]]

^Header

___
> [!note] Ability 1
> - [x] When you [[MV_Face Danger|Face Danger]] or [[MV_React Under Fire|React Under Fire]] by guiding your vehicle through a hazard or out of harm’s way, add +1
> - On a hit Take +1 momentum.

^Ability1

___
> [!info] Ability 2
> - [ ] When you [[MV_Gain Ground|Gain Ground]] by maneuvering your vehicle against a foe, add +1. 
> - If you score a strong hit with a 4, 5, or 6 on the action die, you may put yourself in firing position.
> 	- If you do, set aside the action die or note its value. 
> 	- If you or an ally [[MV_Strike|Strike]] using the vehicle’s weapons, preset your action die with that value. 
> 	- This persists until you fail to score a strong hit on that move, or until you make another move which changes your vehicle’s position.

^Ability2

___
> [!todo] Ability 3
> - [ ] When you must [[MV_Endure Stress|Endure Stress]] while piloting a vehicle, you may roll +integrity. 
> - On a strong hit Take +1 momentum

^Ability3

___

#Pedia/Assets/Path

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>