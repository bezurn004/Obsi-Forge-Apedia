---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 
AssetDeck: "Starsmith Assets"

## Page
aliases: 
  - "Rocketeer (asset)"
  - "ROCKETEER"
PageType: Asset
PageCategory: Path
PageOrder: 18

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
AssetName: "ROCKETEER"
GameplayRole: [Adventure, Exploration]
Aspect: "Your jet pack allows you to hover mid-air, make jet-assisted leaps, or fly over short distances. It has a max of 5 fuel and can be refueled on your command vehicle."
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
# [[_STRSM Assets Index|Starsmith Assets]] - [[_STRSM_Path Assets|Path]]: Rocketeer
Jet packs were always a dangerous means of locomotion. The flames shooting down toward the ground meant that the users inevitably caught on fire themselves. The most successful jet packs from the Old World were actually hydro-powered which limited their use to recreation on lakes and oceans. However, with the advent of technology that can produce and use localized gravity waves, the full power of the jet pack has finally been unlocked.

Since jet packs now run off of modified gravity waves, they can be sealed and used in almost any environment. Need to do some underwater exploration? Strap on a jet pack over your diving gear and let it gently propel you through the waters. Need to do some emergency hull repair? Use your jet pack to perform the maintenance without the need of a tether. Almost all jet packs are rated to maintain full functionality in air, water and space equally.

There are also multiple configurations of jet packs. Some are slim and no larger than a small book bag. These can provide modest thrust and are particularly useful when the user needs more mobility. Other models utilize a larger pulse generator for greater thrust as well as smaller stabilizers that extend in front of the user that give them the ultimate in fine control and maneuverability.

Many people assume that using a jet pack is as simple as strapping in and pressing the button, but that’s not true. Most first time users end up with bumps, bruises and broken bones because it is difficult to learn how to balance one’s body mid-flight. It takes long hours of training in safety facilities before a company will even sell you a jet pack and risk their reputation on your flight abilities.

> [!mechanics]- [[AST_Roketeer|Rocketeer (asset)]]
> **Aspect:** Your jet pack allows you to hover mid-air, make jet-assisted leaps, or fly over short distances. It has a max of 5 fuel and can be refueled on your command vehicle.
> > [!warning]  Fuel | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> | ^Header
___

> [!note] Ability 1
> - [x] When you make a move using your jet pack to overcome an obstacle or gain a better position...
> - add +2
> - suffer -1 fuel.
> > [!faq]- Possible Moves
> > [[MV_Face Danger|Face Danger (move)]] - [[MV_Secure an Advantage|Secure an Advantage (move)]] - [[MV_Gain Ground|Gain Ground (move)]] - [[MV_React Under Fire|React Under Fire (move)]] ^Ability1
___
> [!info] Ability 2
> - [ ] When you make a move reacting to an imminent threat by rapidly relocating using a burst from your jet pack...
> - [[HBC_Boost|Boost]]
> - suffer -1 fuel.
> > [!faq]- Possible Moves
> > [[MV_Face Danger|Face Danger (move)]] - [[MV_Gain Ground|Gain Ground (move)]] - [[MV_React Under Fire|React Under Fire (move)]] ^Ability2
___
> [!todo] Ability 3
> - [ ] When you [[MV_Undertake an Expedition|Undertake an Expedition (+edge)]] across difficult terrain assisted by your jet pack...
> - On a hit take +1 momentum and suffer -1 fuel. 
> - On a strong hit with a match, you surge ahead. Mark progress. ^Ability3
___

## Commentary
I went back and forth on whether this should be a support vehicle or path. I ultimately landed on a path because I felt like you would likely take your jet pack with you even on a support vehicle. The limited fuel of the jet pack lends itself to only being used in the most necessary of circumstances.

The first ability gives you some narrative framing and also a powerful add +2 at the cost of one fuel. I was imagining jumping across canyons or rivers, but you could equally use the jet pack out in open space as well.

For the second ability, I was imagining the Mandolorian getting knocked down by a big tough alien with an axe. As the blade falls towards Mando, he flips on his jet pack and shoots backwards out of the way of the axe. You may have to suspend disbelief a bit for the jet pack not to set you on fire in that case or modify your concept of a jet pack to actually be pulses of gravity rather than fiery jets.

The third ability should be seen as the jet pack helping you on a journey, not necessarily being your full-time vehicle as you journey. If you’re traveling across a jungle world, you may need jump assists to clear a particularly thick tangle of undergrowth or make it across the piranha-infested river. Also note that if you’re not making a move, you’re not burning fuel. That gives you the narrative license to use your jet pack for simple movements like flying to the top of a one-story building.

## Quest Starter
> Crater Valley is on the dark side of a rocky planet that is gravitationally locked to always face its sun. Due to a thick asteroid belt, meteors fall in this valley nearly constantly creating huge craters. A ship went down and is stranded in one such crater. What cargo were they carrying that you desperately need? ^QuestStarter

## Tags

| Previous Asset| Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Rebel\|REBEL]]** | #Starsmith/Assets/Path - #AssetDeck/Starsmith-Assets | **[[AST_Scientist\|SCIENTIST]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>