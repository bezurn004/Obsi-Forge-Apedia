---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 
AssetDeck: ["SF", "SI-Crossover"]

## Page
aliases:
  - "Fugitive (asset)"
  - "FUGITIVE"
PageType: Asset
PageCategory: Path
PageOrder: 41

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
AssetName: "FUGITIVE"
GameplayRole: Adventure
Aspect: "You are hunted by a power or authority."
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
# [[_Assets Index|Assets]] - [[_Path Assets|Path]]: Fugitive
> [!mechanics]- [[AST_Fugitive|Fugitive (asset)]]
> **Character Aspect: ** You are hunted by a power or authority...
> > [!warning] Hunted (4) | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> | ^Header
___
> [!note] Ability 1
> - [x] When you make a move, you may improve the result to a strong hit.
> 	- If you do, fill one segment of a four-segment clock to represent hunters closing in. 
> 	- When the clock is filled, a notable foe or force has tracked you down. 
> 		- If you overcome them or escape, reset the clock and mark 1 tick on your quests legacy track.
> > [!faq]- Possible Moves
> > Any roll type "Action"
> > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ``` ^Ability1
___
> [!info] Ability 2
> - [ ] When you make a move by hiding, concealing your identity, or fleeing from a pursuer, add +1 and take +1 momentum on a hit.
> > [!faq]- Possible Moves
> > [[MV_Gain Ground|Gain Ground (+edge, shadow)]] - [[MV_Compel|Compel (+shadow)]] - [[MV_Secure an Advantage|Secure an Advantage (+edge, shadow)]] - [[MV_Enter the Fray|Enter The Fray (+shadow)]] - [[MV_React Under Fire|React Under Fire (+edge, shadow)]] ^Ability2
___
> [!todo] Ability 3
> - [ ] When you [[MV_Fullfill Your Vow|Fullfill Your Vow]] (extreme or greater) by clearing your name or defeating the power or authority who marked you as a fugitive, gain this ability at no cost. 
> 	- You may then exchange this asset for another with the same number of marked abilities. ^Ability3
___

## Tags
| Previous Asset | Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Firebrand\|FIREBRAND]]** | #Starforged/Assets/Path - #AssetDeck/Starforged - #AssetDeck/SI-SFCrossover | **[[AST_Gearhead\|GEARHEAD]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>