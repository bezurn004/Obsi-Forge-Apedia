---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Haunted (asset)"
  - "HAUNTED"
PageType: Asset
PageCategory: Path
PageOrder: 45

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
AssetName: "HAUNTED"
GameplayRole: Any
Aspect: "You are haunted by the spirit of someone whose death you caused or mourn (or both)."
PreReqCondiation: 
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
# [[_Assets Index|Assets]] - [[_Path Assets|Path]]: Haunted
> [!mechanics]- [[AST_Haunted|Haunted (asset)]]
> **Character Aspect: ** You are haunted by the spirit of someone whose death you caused or mourn (or both).
> > **Haunting Spirit: ** _Insert_Description_Here_
^Header
___
> [!note] Ability 1
> - [x]  When you make a move to call upon their insight, add +1.
> 	- On a strong hit with a match, mark 1 tick on your bonds legacy track.
> 	- On a weak hit, also Endure Stress (-1).
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ```
^Ability1
___
> [!info] Ability 2
> - [ ] When you [[MV_Face Death|Face Death]] guided by the spirit, add +1. 
> 	- On a strong hit, envision what you learn from them or about them, and mark 2 ticks on your bonds legacy track.
^Ability2
___
> [!todo] Ability 3
> - [ ] One time only, when you [[MV_Fullfill Your Vow|Fullfill Your Vow]] (extreme or greater) in service to the spirit, take this ability at no cost and choose one.
> 	- Let them go: Mark 2 ticks on your bonds legacy track for each marked ability, and discard this asset.
> 	- Bolster your link: When you use a HAUNTED ability, on a hit take +1 momentum.
^Ability3
___

## Tags
| Previous Asset| Tags | Next Asset |
|:--- |:---:| ---:|
| **[[AST_Gunslinger\|GUNSLINGER]]** | #Pedia/Assets/Path | **[[AST_Healer\|HEALER]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>