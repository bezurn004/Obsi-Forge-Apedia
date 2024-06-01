---
Alias: "Combat Bot (asset)"
PageType: Asset
PageCategory: Companion

Ability1:
Abil1_Aspect:
Abil1_MovesTrigger:
Abil1_MoveTriggerSE:
Abil1_MovesTake:
Abil1_TriggerNarrative:
Abil1_ActionResultSE:

Ability2:
Abil2_Aspect:
Abil2_MovesTrigger:
Abil2_MoveTriggerSE:
Abil2_TriggerNarrative:
Abil2_MovesTake:
Abil2_ActionResultSE:

Ability3:
Abil3_Aspect:
Abil3_MovesTrigger:
Abil3_MoveTriggerSE:
Abil3_TriggerNarrative:
Abil3_MovesTake:
Abil3_Narrative:
Abil3_ActionResultSE:

GameplayRole: Combat
Aspect: "Your combat bot companion fights at your side."
PreReqCondition: 
NameNum: 1
NameLabels: "Companion Name"
NameValues: 
TrackNum: 1
TrackLabels: Health
TrackMin: 0
TrackMax: 5
ConditionNum: 1
ConditionLabels: "Out of Action"
---
# [[_Assets Index|Assets]] - [[_Companion Assets|Companion]]: Combat Bot

> [!mechanics]- [[AST_Combat Bot|Combat Bot (asset)]]
> **Aspect:** Your combat bot companion fights at your side.
> > [!warning] <input type=texbox value="CompanionNameHere"> | Health | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> >  - [ ] Out of Action

^Header

___
> [!note] Ability 1
> - [x] When you [[MV_Strike|Strike]] aided by the bot, add +1
> - When you [[MV_Clash|Clash]], on a hit take +1 momentum.

^Ability1

___
> [!info] Ability 2
> - [ ] When you use the threat of violence to [[MV_Compel|Compel]] or [[MV_Gain Ground|Gain Ground]] while the bot brings its weapons to bear, you may roll +its health.  If you do...
> 	- On a hit take +1 momentum. 
> 	- On a strong hit with a match, the bot’s display is especially persuasive; take another +1 momentum.

^Ability2

___
> [!todo] Ability 3
> - [ ] Once per fight, when you [[MV_React Under Fire|React Under Fire]] by using the bot to draw fire or create a diversion, roll +its health. 
> 	- On a strong hit, mark progress. 
> 	- On a weak hit, face the cost as normal, but then you are in control.
> 
> > [!error] Combat Bot Diversion
> > - [ ] Used

^Ability3

___

#Pedia/Assets/Companion 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>