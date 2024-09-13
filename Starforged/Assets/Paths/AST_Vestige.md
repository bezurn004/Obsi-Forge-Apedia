---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: ["SF", "SI-Crossover"]

## Page
aliases:
  - "Vestige (asset)"
  - "VESTIGE"
PageType: Asset
PageCategory: Path
PageOrder: 66

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
AssetName: "VESTIGE"
GameplayRole: Survival
Aspect: "You are all that remains of a people, culture, or tradition."
PreReqCondition: 
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
# [[_Assets Index|Assets]] - [[_Path Assets|Path]]: Vestige
> [!mechanics]- [[AST_Vestige|Vestige (asset)]]
> **Character Aspect: ** You are all that remains of a people, culture, or tradition.** ^Header
___
> [!note] Ability 1
> - [x] When you [[SF_CH3_Face Death|Face Death]] or [[SF_CH3_Face Desolution|Face Desolution]], visions of your heritage give you the strength to carry on. Envision how this manifests, and reroll any dice. 
> 	- On a strong hit with a match, a surprising new aspect of your heritage is revealed; take +2 momentum and mark 2 ticks on your bonds legacy track. ^Ability1
___
> [!info] Ability 2
> - [ ] When you [[SF_CH3_Secure an Advantage|Secure an Advantage]] or [[SF_CH3_Compel|Compel]] through a tale, performance, or ceremony, envision what you reveal of your heritage and +1 
> 	- On a hit take +1 momentum ^Ability2
___
> [!todo] Ability 3
> - [ ] You carry a physical relic of your heritage. Envision its powers or nature. 
> - When you make a move directly aided by the relic and score a miss, you may reroll your action die.
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ``` ^Ability3
___

## Tags
| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Trader\|TRADER]]** | #Starforged/Assets/Path - #AssetDeck/Starforged - #AssetDeck/SI-SFCrossover | **[[AST_Veteran\|VETERAN]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>