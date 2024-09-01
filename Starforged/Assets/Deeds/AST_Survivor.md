---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: ["SF", "SI-Crossover"]

## Page
aliases:
  - "Survivor (asset)"
  - "SURVIVOR"
PageType: Asset
PageCategory: Deed
PageOrder: 86

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
AssetName: "SURVIVOR"
GameplayRole: Survival
Aspect:
PreReqCondition: "Once you mark traumatized or permanently harmed."
NameNum:
NameLabels:
NameValues:
TrackNum:
TrackLabels:
TrackMin:
TrackMax:
ConditionNum:
ConditionLabels:
---
# [[_Assets Index|Assets]] - [[_Deed Assets|Deed]]: Survivor
> [!mechanics]- [[AST_Survivor|Survivor (asset)]]
> **Deed Pre-Req:** Once you mark traumatized or permanently harmed… ^Header
___
> [!note] Ability 1
> - [x] When you are haunted by past experiences and must [[MV_Endure Stress|Endure Stress]], you may [[MV_Lose Momentum|Lose Momentum]] (-1) before rolling as you attempt to find focus or calm. If you do...
> 	- Reroll any dice. 
> 	- On a strong hit, take +1 momentum.  ^Ability1
___
> [!info] Ability 2
> - [ ] When you make a move where a lasting effect (traumatized or permanently harmed) has a narrative impact on the scene or your approach, and burn momentum to improve your result, you may envision what sustains or motivates you in this moment. If you do...
> 	- Mark 1 tick on your quests or bonds legacy track.
> 	- On a strong hit with a match, mark 2 ticks.
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ``` ^Ability2
___
> [!todo] Ability 3
> - [ ] You are learning to live with this impact. The lasting effect (traumatized or permanently harmed, but not both) remains marked, but no longer reduces your max momentum or reset. ^Ability3
___

## Tags
| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Revenant\|REVENANT]]** | #Starforged/Assets/Deed - #AssetDeck/Starforged - #AssetDeck/SI-SFCrossover - #AssetDeck/SI-SFCrossover | **[[AST_Vanguard\|VANGUARD]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>