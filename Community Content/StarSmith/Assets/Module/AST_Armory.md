---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases: 
  - "Armory (asset)"
  - "ARMORY"
PageType: Asset
PageCategory: Module
PageOrder: 2

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
AssetName: "ARMORY"
GameplayRole: Combat
Aspect: 
PreReqCondition: 
NameNum: 
NameLabels: 
NameValues: 
TrackNum: 
TrackLabels: 
TrackMin: 
TrackMax: 
ConditionNum: 1
ConditionLabels: Broken
---
# [[_STRSM Assets Index|Starsmith Assets]] - [[_STRSM_Module Assets|Module]]: Armory
No one heads out in the blackness of space without being prepared for a raider attack, corrupt faction checkpoint, or a hostile encounter with spaceborne lifeforms. However, some vessels are more prepared than others.

A fully loaded armory has weapons that are DNA-coded to the ship’s occupants, specialized boarding gear for breaching another vessel’s hull, and high efficiency weapons such as rifles that simultaneously fire a kinetic bullet and a directed energy blast. As the kinetic bullets leave the chamber, it recharges the energy cell which allows the rifle to continue functioning as an energy weapon long after the physical bullets run out. The armory even has a recycling unit to turn spent casings into fresh ammunition.

One of the most sought after tech upgrades to the armory is the opposition coded ammunition. When these kinetic bullets are fired, they are programmed to learn the patterns of an enemy and adjust trajectory mid-flight through AI-powered probabilistic matrices embedded in the bullet.

So why doesn’t every starship have its own armory? Simple: cost. Keeping the armory stocked costs cash, the armory itself costs space on a ship, and the swiftly evolving security systems to keep the armory under lock and key costs a lot of computing power from the core processor. However, for those who can afford the investment, the payoff is worthwhile.

> [!mechanics]- [[AST_Armory|Armory (asset)]]
> > [!warning] Module Status
> > - [ ] Broken ^Header
___

> [!note] Ability 1
> - [x] When you [[MV_Enter the Fray|Enter The Fray (move)]] to oppose an invader within your vehicle, [[HBC_Boost|Boost]].
> On a strong hit, they were unprepared for your firepower. Add +1 to all moves until you roll a one on your action die.
> > [!warning] | Available | <input type="checkbox" /> | ^Ability1
___
> [!info] Ability 2
> - [ ] **Aspect** You may prepare for engaging in combat by taking limited-use armaments from your armory.
> If you do, one time only, when you [[MV_Enter the Fray|Enter The Fray]], choose your approach.
> - **Going in hot:** On a hit, take +2 momentum.
> 	- On a strong hit with a match, also mark progress.
> - **Gain the upper hand:** Add +2.
> > [!warning] | Available | <input type="checkbox" /> | ^Ability2
___
> [!todo] Ability 3
> - [ ] **Aspect** You may prepare for a drawn-out battle by taking specialized ammunition.
> If you do, during a single combat scene only, you may reroll any action die showing a one when you [[MV_Strike|Strike]] or [[MV_Clash|Clash]].
> > [!warning] | Available | <input type="checkbox" /> | ^Ability3

___

## Commentary
The first ability here is meant to be in the same vein as the third ability of the Internal Refit module, but I wanted the abilities to stack and complement each other. You get a boost for the weapons, and if that goes well, you get to press the advantage with a continuous add +1 until your action die abandons you.

The second ability is meant to represent a shock and awe show of force style weapon. You can use this to either overwhelm the enemy with damage or to make sure you are positioned well as the fight continues.

The third ability is your AI-enhanced ammo that seeks out the enemy giving you a “no 1s here” battle. This is mathematically equivalent to a constant add +0.5 for the battle. However, the ammo only lasts a single fight scene.

## Quest Starter
> The raiders aboard the vessel known as the Fang of the Forge are known to have some of the fiercest weapons around. If you can’t outrun them, there is no way to defeat them in battle. Surrender is the only option. What specialized weapon do they have that you desperately need? What do you hope to accomplish with this weapon if you can secure it? What inherent dangers are involved with using this weapon? ^QuestStarter

## Tags

| Previous Asset| Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Aeroponics\|AEROPONICS]]** | #Starsmith/Assets/Modules | **[[AST_Drones\|DRONES]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>
