---
## Source
SourceMaterial: "Ironsworn: Sundered Isles"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: SI

## Page
aliases:
  - "MONKEY"
  - "Monkey (asset)"
PageType: Asset
PageCategory: Companion
PageOrder: 52

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
AssetName: "MONKEY"
GameplayRole: 
Aspect: "Your monkey companion finds its own trouble."
PreReqCondition: 
NameNum: 1
NameLabels: Name
NameValues: 
TrackNum: 1
TrackLabels: Health
TrackMin: 0
TrackMax: 3
ConditionNum: 1
ConditionLabels: "Out of Action"
---
# [[_Assets Index|Assets]] - [[_Companion Assets|Companion]]: Monkey

> [!mechanics]- [[AST_Monkey|MONKEY]]
> **Aspect:** Your monkey companion finds its own trouble.
> > [!warning] <input type=texbox value="Name"> | Health | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Out of Action ^Header
 ___
> [!note] Ability 1
> - [x] Once per situation, when you score a **miss,** you may suffer the cost by envisioning the monkey causing mischief or getting into danger.
> - If you do, roll +its health.
> 	- On a **strong hit,** the monkey unwittingly turns the situation in your favor; take +2 momentum.
> 	- On a **weak hit,** it provides a distraction or mild boon; take +1 momentum.
> 	- On a **miss,** it faces its own cost or makes the situation worse. #ConvertAbilityToMove ^Ability1
___
> [!info] Ability 2
> - [ ] When you make a move by sending the monkey to complete a task involving theft, infiltration, or sabotage, roll +its health.
> - On **a hit,** take +1 momentum. 
> > [!faq]- Possible Moves
> > #ambiguous _InputPossibleMovesHere_ ^Ability2
___
> [!todo] Ability 3
> - [ ] When you [[SF_CH3_Resupply|Resupply]] by asking the monkey to search or scavenge, add +1. ^Ability3
___
## Tags

| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Jungle Cat\|JUNGLE CAT]]** | #SunderedIsles/Assets/Companion - #AssetDeck/SunderedIsles | **[[AST_Parrot\|PARROT]]** |

<font size=-2>Copyright ©2024 Shawn Tomkin. The text of this work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license. For license details, visit ironswornrpg.com. Updated June 2024 MUH051V200-PDF</font>