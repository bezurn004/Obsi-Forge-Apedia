---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: ["SF", "SI-Crossover", "Remarkable"]

## Page
aliases:
  - "Augmented (asset)"
  - "AUGMENTED"
PageType: Asset
PageCategory: Path
PageOrder: 28

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
AssetName: "AUGMENTED"
GameplayRole: Any
Aspect: "You are equipped with an advanced prosthetic, implant, or mechanical enhancement."
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
# [[_Assets Index|Assets]] - [[_Path Assets|Path]]: Augmented
> [!mechanics]- [[AST_Augmented|Augmented (asset)]]
> **Character Aspect: ** You are equipped with an advanced prosthetic, implant, or mechanical enhancement. 
> > [!faq]- **Augment 1 ** 
> > - [ ] Broken
> > _Insert_Description_Here_
> 
> > [!faq]- **Augment 2**
> > - [ ] Broken
> > _Insert_Description_Here_ ^Header
___
> [!note] Ability 1
> - [x] When you make a move directly aided by the augment, envision how it gives you exceptional capabilities and add +1. 
> 	- On a strong hit with a match, your augment exceeds expectations; take +2 momentum. 
> 	- On a miss with a match, the augment is broken; you must [[SF_CH3_Repair|Repair]] and spend 3 repair points to bring it back to working condition. #ambiguous %%Need to determine appliable moves%%
> > [!faq]- Possible moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ``` ^Ability1
___
> [!info] Ability 2
> - [ ] You are equipped with a second augment. It functions as above, but the benefits of the two augments do not stack.  ^Ability2
___
> [!todo] Ability 3
> - [ ] When you must [[SF_CH3_Endure Harm|Endure Harm]] or [[SF_CH3_Face Death|Face Death]], you may instead mark an augment as broken. Repair it as detailed above. ^Ability3
___

## Tags
| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Artist\|ARTIST]]** | #Starforged/Assets/Path - #AssetDeck/Starforged - #AssetDeck/SI-SFCrossover - #AssetDeck/Remarkable-Tech | **[[AST_Bannersworn\|BANNERSWORN]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>