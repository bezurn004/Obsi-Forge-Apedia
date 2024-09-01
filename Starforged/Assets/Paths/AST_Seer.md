---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: ["SF", "SI-Crossover", "Supernatural"]

## Page
aliases:
  - "Seer (asset)"
  - "SEER"
PageType: Asset
PageCategory: Path
PageOrder: 59

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
AssetName: "SEER"
GameplayRole: Any
Aspect:
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
# [[_Assets Index|Assets]] - [[_Path Assets|Path]]: Seer
> [!mechanics]- [[AST_Seer|Seer (asset)]]
> **Prophecy: ** _Insert_Description_Here_ ^Header
___
> [!note] Ability 1
> - [x] When you envision experiencing a prophetic dream, you may [[MV_Ask the Oracle|Ask the Oracle]] for details using an interpretive oracle such as Action/Them or Descriptor/Focus.
> 	- If you record the answer, and later face a situation which gives truth to the vision.
> 		- Take an automatic strong hit (one time only) when making a move to act on your foresight. 
> 		- Then, clear the prophecy. 
> 
> Only one prophecy can be active at a time.
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ``` ^Ability1
___
> [!info] Ability 2
> - [ ] When you focus or meditate to [[MV_Gather Information|Gather Information]] about a place, being, or situation (in person or remotely), roll +spirit.
> 	- On a hit take +1 momentum. ^Ability2
___
> [!todo] Ability 3
> - [ ] When you or an ally roll a match as you [[MV_Sojourn|Sojourn]] in a community or [[MV_Undertake an Expedition|Undertake an Expedition]] within a site, you may envision gaining sudden and unbidden insight about the location. If you do...
> 	- Take +2 momentum. ^Ability3
___

## Tags
| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Scoundrel\|SCOUNDREL]]** | #Starforged/Assets/Path - #AssetDeck/Starforged - #AssetDeck/SI-SFCrossover - #AssetDeck/Supernatural-Mythic | **[[AST_Shade\|SHADE]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>