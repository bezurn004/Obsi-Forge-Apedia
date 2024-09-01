---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 
AssetDeck: "Starsmith Assets"

## Page
aliases: 
  - "Flash Fox (asset)"
  - "FLASH FOX"
PageType: Asset
PageCategory: Companion
PageOrder: 25

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
AssetName: "FLASH FOX"
GameplayRole: Survival
Aspect: "Your flash fox uses its short-range teleportation to bypass obstacles."
PreReqCondition: 
NameNum: 1
NameLabels: Name
NameValues: InsertNameHere
TrackNum: 1
TrackLabels: Health
TrackMin: 0
TrackMax: 3
ConditionNum: 1 
ConditionLabels: "Out of Action"
---
# [[_STRSM Assets Index|Starsmith Assets]] - [[_STRSM_Companion Assets|Companion]]: Flash fox
The creature known as the flash fox is a native of the desert world Nizligi where the vast stretches of sand are only interrupted by rocky canyons made of pure obsidian. The instability of the planet’s core leads to frequent earthquakes where columns of obsidian will swiftly shoot upward or flat stretches of the rock will shatter to become a gaping hole. To traverse this ever-changing landscape, the flash fox evolved the ability teleport over short distances.

This ability may have also been an adaptation to hunting in the stifling hot deserts where the sand can scorch the feet of a creature who stands on it for too long. The flash foxes can teleport towards their prey, take it down, and teleport back to less hot areas of shade to feast.

When these wondrous creatures were first discovered, humanity attempted to exploit them as pets and attack dogs, but a group known as the Nine-Tailed Shepherds built a series of orbital space stations in order to protect the planet from poachers and those who would exploit its resources to the detriment of all life there. The Nine-Tailed Shepherds strive to work in harmony with the odd ecosystem of the planet to keep their own communities alive while still maintaining the natural environment of Nizligi.

Occasionally, a flash fox will take a liking to one of the shepherds and choose to stay with the human as a constant companion. The foxes who make this bond adapt quickly to life in space and learn to work with their companion human in many capacities from defending the planet against raiders to gathering scientific data in hard to reach places on the planet’s surface

> [!mechanics]- [[AST_Flash Fox|Flash Fox (asset)]]
> **Aspect:** Your flash fox uses its short-range teleportation to bypass obstacles.
> > [!warning] **Name: **<input type=texbox value="InputNameHere"> | Health | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Out of Action ^Header
___

> [!note] Ability 1
> - [x] When you make a move by directing your flash fox to teleport you a short distance away, roll +its health and [[HBC_Boost|Boost]].
> > [!faq]- Possible Moves
> > InputPossibleMovesHere #ambiguous ^Ability1
___
> [!info] Ability 2
> - [ ] **Aspect:** Your flash fox attempts to teleport you out of harm's way.
> When you [[MV_Endure Harm|Endure Harm]], you may roll +its health [[HBC_Roll with Advantage|with Advantage]].
> - If you do and score a hit, reduce the loss of health you suffered by 1.
> - On a miss, your [[MV_Companion Takes a Hit|Companion Takes a Hit]] as well. ^Ability2
___
> [!todo] Ability 3
> - [ ] **Aspect:** Your flash fox has learned to coordinate its teleporting attacks with your own.
> When you [[MV_Strike|Strike]] aided by the flash fox, add +1.
> If you [[MV_Clash|Clash]], take +1 momentum on a hit. ^Ability3
___

## Commentary
The first ability is similar to the Rockhorn asset’s first ability but for mobility instead of attacking. The rockhorn gets a roll of +1 to +5, so I gave the flash fox a boost on this since it has lower health in the first place. You might use this to Secure an Advantage, Gain Ground, React Under Fire, or any other move where you need to get to a hard to reach area that would otherwise be inaccessible.

The second ability represents your fox teleporting to you and then quickly teleporting again to turn a direct hit on you into a grazing wound. However, doing this puts your fox at risk as well.

The third ability is meant to emulate Nightcrawler’s quick BAMF attacks. The fox teleports in, bites, and teleports back out over and over again. I thought about making this give you more momentum instead of a bonus on the roll but ultimately settled on the same wording as the Combat Bot asset’s first ability

## Quest Starter
> The Nine-Tailed Shepherds have put out an emergency bulletin asking for help tracking and apprehending a raider group who captured several flash fox families from Nizligi and made a clean get away. They believe the raiders are intending to set-up a breeding program to sell pups to the highest bidder. An old fable from your youth always made you admire the fox. What was the tale, and who was it that told you this tale so often? Why would they want you to risk going after the raiders? ^QuestStarter

## Tags

| Previous Asset| Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_Crew Member\|CREW MEMBER]]** | #Starsmith/Assets/Companion - #AssetDeck/Starsmith-Assets | **[[AST_Furball\|FURBALL]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>
