---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Symbiote (asset)"
  - "SYMBIOTE"
PageType: Asset
PageCategory: Companion
PageOrder: 78

## Ability1
Abil1_Aspect:
Abil1_MovesTrigger:
Abil1_MoveTriggerSE:
Abil1_MovesTake:
Abil1_TriggerNarrative:
Abil1_ActionResultSE:

## Ability2
Abil2_Aspect:
Abil2_MovesTrigger:
Abil2_MoveTriggerSE:
Abil2_TriggerNarrative:
Abil2_MovesTake:
Abil2_ActionResultSE:

## Ability3
Abil3_Aspect:
Abil3_MovesTrigger:
Abil3_MoveTriggerSE:
Abil3_TriggerNarrative:
Abil3_MovesTake:
Abil3_Narrative:
Abil3_ActionResultSE:

## Properties
AssetName: "SYMBIOTE"
GameplayRole: Any
Aspect: "You are physically bound to a being with 2 health."
PreReqCondition: 
NameNum: 1
NameLabels: "Companion Name"
NameValues:
TrackNum: 1
TrackLabels: Health
TrackMin: 0
TrackMax: 2
ConditionNum: 1
ConditionLabels: "Out of Action"
---
# [[_Assets Index|Assets]] - [[_Companion Assets|Companion]]: Symbiote
> [!mechanics]- [[AST_Symbiote|Symbiote (asset)]]
> **Aspect:** You are physically bound to a being with 2 health.
> > [!warning] <input type=texbox value="CompanionNameHere"> | Health | <input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Out of Action
^Header
___
> [!note] Ability 1
> - [x] When you make aggressive moves while giving yourself to the symbiote’s power, add +its health. 
> - If you face physical harm, choose either the [[MV_Endure Harm|Endure Harm]] or [[MV_Companion Takes a Hit|Companion Takes a Hit]] move. 
> 	- To restore the symbiote’s health, you must [[MV_Endure Stress|Endure Stress]] and give the symbiote +health equal to the -spirit you face. 
> - If you make a move aided by the symbiote and roll a 1 on your action die, your fragile bond is broken for several hours.
> > [!faq]- Possible Moves
> > [[MV_Aid Your Ally|Aid Your Ally (move)]] - [[MV_Face Danger|Face Danger (move)]] - [[MV_Battle|Battle (move)]] - [[MV_Clash|Clash (move)]] - [[MV_Enter the Fray|Enter The Fray (move)]] - [[MV_Gain Ground|Gain Ground (move)]] - [[MV_React Under Fire|React Under Fire (move)]] - [[MV_Strike|Strike (move)]]
^Ability1
___
> [!info] Ability 2
> - [ ] When you make a move and heed the symbiote’s guidance (decide after rolling), you may reroll any dice. Then, [[MV_Endure Stress|Endure Stress]] (-2).
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ```
^Ability2
___
> [!todo] Ability 3
> - [ ] The symbiote gains power and has 3 health.
^Ability3
___

## Tags
| Previous Asset| Tags | Next Asset |
|:--- |:---:| ---:|
| **[[AST_Survey Bot\|SURVEY BOT]]** | #Pedia/Assets/Companion | **[[AST_Utility Bot\|UTILITY BOT]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>