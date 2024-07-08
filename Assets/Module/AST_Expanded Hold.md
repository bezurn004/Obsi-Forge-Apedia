---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Expanded Hold (asset)"
  - "EXPANDED HOLD"
PageType: Asset
PageCategory: Module
PageOrder: 3

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
AssetName: "EXPANDED HOLD"
GameplayRole: Survival
Aspect: "Your vehicle carries up to 3 cargo."
PreReqCondition:
NameNum:
NameLabels:
NameValues:
TrackNum: 1
TrackLabels: Cargo
TrackMin: 0
TrackMax: 3
ConditionNum: 1
ConditionLabels: "Broken"
---
# [[_Assets Index|Assets]] - [[_Module Assets|Module]]: Expanded Hold
> [!mechanics]- [[AST_Expanded Hold|Expanded Hold (asset)]]
> **Module Aspect: ** Your vehicle carries up to 3 cargo. 
> > [!warning] Module Status | Cargo | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Broken
^Header
___
> [!note] Ability 1
> - [x] When you gain +supply, you may convert it to +cargo. 
> - When you make a move +supply, you may add +cargo. 
> - When you [[MV_Sacrifice Resources|Sacrafice Resources]], you may instead suffer -cargo for any portion of the cost. #ambiguous %%Need to determine applicable moves%%
^Ability1
___
> [!info] Ability 2
> - [ ] When you score a miss or weak hit as you make a move to barter or negotiate, and you have at least 1 cargo, you may sweeten the pot.
> 	- If you do, reroll all dice and add +cargo. Then, suffer -1 cargo.
> > [!faq]- Possible Moves
> > [[MV_Compel|Compel (move)]] - [[MV_Resupply|Resupply (move)]] - [[MV_Face Danger|Face Danger (move)]] - [[MV_Secure an Advantage|Secure an Advantage (move)]]
^Ability2
___
> [!todo] Ability 3
> - [ ] When you make a move to outrun a threat and have at least 1 cargo, you may first lighten your load by dropping cargo. 
> 	- If you do, suffer -cargo by the amount dropped, add +that amount
> 		- On a hit take +2 momentum.
> > [!faq]- Possible Moves
> > [[MV_Check Your Gear|Check Your Gear (move)]] - [[MV_Set a Course|Set a Course (move)]] - [[MV_Repair|Repair (move)]]
^Ability3
___

## Tags
| Previous Asset| Tags | Next Asset |
|:--- |:---:| ---:|
| **[[AST_Engine Upgrade\|ENGINE UPGRADE]]** | #Pedia/Assets/Module | **[[AST_Grappler\|GRAPPLER]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>