---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases: 
  - "Drones (asset)"
  - "DRONES"
PageType: Asset
PageCategory: Module
PageOrder: 3

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
AssetName: "DRONES"
GameplayRole: [Combat, Exploration]
Aspect: "Your set of hoverbike-sized drones are equipped with combat analytics to fight at your side."
PreReqCondition: 
NameNum: 
NameLabels: 
NameValues: 
TrackNum: 1
TrackLabels: Integrity
TrackMin: 0
TrackMax: 3
ConditionNum: 1
ConditionLabels: Broken
---
# [[_STRSM Assets Index|Starsmith Assets]] - [[_STRSM_Module Assets|Module]]: Drones
Drones have long been a useful addition to planetside exploration and combat, but starship sized drones are a different beast entirely. Not only are they expensive to build and maintain, but they require a computing system that can process multiple vectors at once with near instantaneous communication. While crew members can take manual control in extreme circumstances, these drones operate best as their own extension of the core computer system of a starship usually under AI guidance.

While combat was the first application of these large drones, navigating FTL travel with the Eidolon drive was a swiftly discovered secondary purpose. Releasing the drones before a jump allows the Eidolon drives to more accurately triangulate positions, account for red light shift, and create a stable gravity fold. After the command vehicle jumps, the drones are able to ride the gravity wave mere light milliseconds after the main vessel.

Additionally, some drones are affixed with stealth tech that can produce large ghost echoes on enemy radars. This can buy the main vessel the critical time it needs to prepare for battle, hide, or even jump away. Of course, jumping away can mean leaving the drones behind, but they can always be rebuilt from an onboard printer specially adapted for drones or picked up at a later time after being given an order to hide from enemy vessels.

> [!mechanics]- [[AST_Drones|Drones (asset)]]
> **Aspect:** Your set of hoverbike-sized drones are equipped with combat analytics to fight at your side.
> > [!warning] | Integrity | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Broken ^Header
___

> [!note] Ability 1
> - [x] When you [[MV_Strike|Strike]] aided by the drones, add +1. 
> When you [[MV_Clash|Clash]], take +1 momentum on a hit. ^Ability1
___
> [!info] Ability 2
> - [ ] **Aspect:** Your drones are equipped with triangulating astronavigation sensors.
> When you [[MV_Undertake an Expedition|Undertake an Expedition (+wits)]] using the drones to help guide your command vehicle on a journey, 
> - [[HBC_Boost|Boost]]  and suffer -1 integrity to the drones. ^Ability2
___
> [!todo] Ability 3
> - [ ] **Aspect:** Your drones are equipped with stealth plating, false signal projectors and sensor jamming systems.
> When you make a move against a specific foe or threat to avoid detection with their help,
> - [[HBC_Boost|Boost]] and suffer -1 integrity to the drones.
> > [!faq]- Possible Moves
> > [[MV_Secure an Advantage|Secure an Advantage (move)]] - [[MV_Gain Ground|Gain Ground (move)]] - [[MV_React Under Fire|React Under Fire (move)]] ^Ability3

___

## Commentary
The first ability comes directly from the [[AST_Combat Bot|Combat Bot (asset)]] companion asset. However, since this module has much more utility, the integrity is lower than the [[AST_Combat Bot|Combat Bot (asset)]]. 

The second ability lets the drones guide you on journeys, but it is difficult to travel at FTL speeds and have the drones all catch up. I felt the loss of integrity represented them following along in the command vehicle’s wake and getting banged up along the way. 

The third ability is meant to be the drones going out and leading enemies away on a wild goose chase. Narratively, this could be that the three drones stick close to each and mimic the signals of your command vehicle so the enemy doesn’t know which one to follow, or they could separate and throw out multiple sensor ghosts, radar blinders, etc. No matter how you flavor it, they let your command vehicle have a better chance of escaping notice hiding behind that moon over there. In my mind, each point of integrity represents a separate small drone, and all of them work in concert when they attack or assist.

## Quest Starter
>A capital vessel for an influential faction left one of its drones behind on the last Eidolon jump they made. If recovered intact, this drone could provide valuable intelligence on the factions movements, locations, and other navigational data. Unfortunately, the drone was last seen headed into the Terragon Nebula. What are the rumors surrounding the Terragon Nebula that make it a dangerous place to approach? What other faction may try to beat you to the drone? ^QuestStarter

## Tags

| Previous Asset| Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Armory\|ARMORY]]** | #Starsmith/Assets/Modules | **[[AST_External Refit\|EXTERNAL REFIT]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>