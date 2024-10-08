---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: ["SF", "SI-Crossover"]

## Page
aliases:
  - "Bonded (asset)"
  - "BONDED"
PageType: Asset
PageCategory: Deed
PageOrder: 81

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
AssetName: "BONDED"
GameplayRole: Any
Aspect:
PreReqCondition: "One time only, once you [[MV_Forge a Bond|Forge a Bound]] with a special individual."
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
# [[_Assets Index|Assets]] - [[_Deed Assets|Deed]]: Bonded
> [!mechanics]- [[AST_Bonded|Bonded (asset)]]
> **Deed Pre-Req:** One time only, once you [[SF_CH3_Forge a Bond|Forge a Bound]] with a special individual. This person is your bond-mate.
> 
> **Bond Mate:** _InsertBondMateLinkHere_ ^Header
___
> [!note] Ability 1
> - [x] When you [[SF_CH3_Sojourn|Sojourn]] at their home, [[SF_CH3_Hearten|Hearten]] in their presence, or [[SF_CH3_Test Your Relationship|Test Your Relationship]] or [[SF_CH3_Develop a Relationship|Develop a Relationship]] with them, reroll any dice. 
> 	- On a strong hit, take +1 momentum. ^Ability1
___
> [!info] Ability 2
> - [ ] When you [[SF_CH3_Set a Course|Set a Course]] back to your bond mate’s location, add +heart. 
> 	- On a strong hit with a match, envision a special reunion and mark 2 ticks on your bonds legacy track. ^Ability2
___
> [!todo] Ability 3
> - [ ] When you make a move in a crucial moment and score a miss, you may cling to thoughts of your bond-mate for support. If you do, reroll any dice. 
> 	- On another miss, in addition to the outcome of the move, you must mark shaken or traumatized. 
> 		- If both debilities are already marked, [[SF_CH3_Face Desolution|Face Desolution]].
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ``` ^Ability3
___

## Tags
| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Voidglider\|VOIDGLIDER]]** | #Starforged/Assets/Deed - #AssetDeck/Starforged - #AssetDeck/SI-SFCrossover - #AssetDeck/SI-SFCrossover | **[[AST_Homesteader\|HOMESTEADER]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>