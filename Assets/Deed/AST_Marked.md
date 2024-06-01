---
Alias: "Marked (asset)"
PageType: Asset
PageCategory: Deed

Ability1:
Abil1_MovesTrigger:
Abil1_MoveTriggerSE:
Abil1_MovesTake:
Abil1_TriggerNarrative:
Abil1_ActionResultSE:
Ability2:

Abil2_MovesTrigger:
Abil2_MoveTriggerSE:
Abil2_TriggerNarrative:
Abil2_MovesTake:
Abil2_ActionResultSE:

Ability3:
Abil3_MovesTrigger:
Abil3_MoveTriggerSE:
Abil3_TriggerNarrative:
Abil3_MovesTake:
Abil3_Narrative:
Abil3_ActionResultSE:

GameplayRole: Adventure
Aspect: "Envision the title, sigil, uniform, or tattoo you bear in recognition of your achievements."
PreReqCondition: "Once you fill 5 boxes on your quests legacy track"
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
# [[_Assets Index|Assets]] - [[_Deed Assets|Deed]]: Marked

> [!mechanics]- [[AST_Marked|Marked (asset)]]
> **Deed Pre-Req:** Once you fill 5 boxes on your quests legacy track. Envision the title, sigil, uniform, or tattoo you bear in recognition of your achievements.
>
> **Marked Description: ** _Marked Description_

^Header

___
> [!note] Ability 1
> - [x] When you [[MV_Compel|Compel]] or [[MV_Make a Connection|Make a Connection]] among those who would know your reputation, add +1. 
> 		- On a strong hit with a match, your notoriety grows; mark 2 ticks on your bonds legacy track.

^Ability1

___
> [!info] Ability 2
> - [ ] When you risk your reputation to overcome a miss, reroll any dice. 
> 		- If you score a miss again, fill one segment of a six-segment clock to represent the stain on your reputation.
> 			- When the clock is filled, discard this asset.
> > [!warning] Stained Mark
> > Clock Progress: <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" />
> 
> > [!faq]- Possible Moves
> > Can this asset be used any time to overcome a miss?  Once the asset is discarded, can it be earned again with different narrative context, along with another clock to fill? #ambiguous
> > > > ```dataview 
> > TABLE without ID	link(file.link, alias) As "Move Name", InlineCmd As "Inline Command", PageCategory As "Move Category", RollType As "Roll Type" WHERE contains(PageType, "Move") & contains(RollType, "Action") & !contains(PageType, "Index") & !contains(file.path, "Template") SORT PageCategory asc, file.name asc
> > ```


Need to determine appliable moves*

^Ability2

___
> [!todo] Ability 3
> - [ ] Once per fight, when you [[MV_Gain Ground|Gain Ground]] through intimidation or command, reroll any dice.  
> 	- On a hit mark progress.
> > [!warning] Ability Status
> > - [ ] Used

^Ability3

___

#Pedia/Assets/Deeds 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>