---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 
AssetDeck: "Starsmith Assets"

## Page
aliases: 
  - "Holodeck (asset)"
  - "HOLODECK"
PageType: Asset
PageCategory: Module
PageOrder: 5

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
AssetName: "HOLODECK"
GameplayRole: Adventure
Aspect: "Your holodeck helps you practice and prepare. Declare a path asset you are training for, and set your training cycle to 0."
PreReqCondition: 
NameNum: 1
NameLabels: "Path Asset"
NameValues: 
TrackNum: 1
TrackLabels: "Training"
TrackMin: 0
TrackMax: 4
ConditionNum: 1
ConditionLabels: "Broken"
---
# [[_STRSM Assets Index|Starsmith Assets]] - [[_STRSM_Module Assets|Module]]: Holodeck
Holodecks started as a pet project of a single engineer in order to stave off boredom aboard one of the original iron home vessels. Once the first fully functioning holodeck was up and running, work spread quickly throughout the scattered fleet. Everyone wanted their own personal hologram that they could physically and mentally interact with.

Despite this more recreational beginning, holodecks soon became a staple for the more practical purpose of expert consultation on deep space voyages. Those who could afford the installation and computer core upgrades necessary to run a full personality matrix in effect were adding to their crew rosters both experts and diagnosticians who didn’t take up food, air, water or other resources required by flesh and blood.

In addition, users could load training simulations from a multitude of topics ranging from combat tactics to medical procedures to patching tears in ablative hull armor. One person could truly become a jack of all trades by continually adding to their skill set.

On top of all this, the original recreational purposes served to help keep up the spirits of travelers. Whether walking into their favorite bar or playing out a character in their favorite novel, crew members with access to a holodeck were able to capitalize on their leisure like never before.

Unfortunately, the personality matrices are notorious for getting out of control. It seems like every third starbase and starship has a horror story of a holodeck trying to kill them. The worst part is that sometimes it succeeds in doing so.

> [!mechanics]- [[AST_Holodeck|Holodeck (asset)]]
> **Aspect:** Your holodeck helps you practice and prepare. Declare a path asset you are training for, and set your training cycle to 0.
> > [!warning] Module Status
> > **Declared Path:** <input type=texbox value="DecalaredPathAsset"> | **Training** | <input type="checkbox" /><input type="checkbox" /><input type="checkbox" /><input type="checkbox" /> |
> > - [ ] Broken ^Header
___

> [!note] Ability 1
> - [x] Once per journey when you [[SF_CH3_Undertake an Expedition|Undertake an Expedition]], you may train in the holodeck.
> - If you do, roll +integrity or +an appropriate stat. #ambiguous _what move are we making here, Expedition? Or is this an Asset move?_
> 	- On a hit, take +1 training cycle. 
> - When your training cycle is at 4 and you [[SF_CH3_Advance|Advance]] to gain or upgrade the declared asset, it costs -1 XP.
> - Then, set your training cycle to zero and declare a new path asset.
> > [!warning] Training Cycle Complete | <input type="checkbox"/> ^Ability1
___
> [!info] Ability 2
> - [ ] When you [[SF_CH3_Gather Information|Gather Information]] or [[SF_CH3_Secure an Advantage|Secure an Advantage]] by talking to a holographic facsimile of an expert, add +1. ^Ability2
___
> [!todo] Ability 3
> - [ ] When you take time for yourself and [[SF_CH3_Hearten|Hearten]] using a favorite recreational program, add +1. ^Ability3
___

## Comentary
The first ability here is a way to lower the XP cost of an asset. The reason you can roll +integrity or +an appropriate stat is to give you room to frame it in the narrative as you like. If it’s a really good training program, you might consider rolling +integrity. If it’s a run of the mill training program, but you’re pouring your heart and soul into, roll one of your stats that makes sense.

However, note at the end that you must declare a “new” asset. That means you can’t get the benefit of a lower XP cost on the same asset multiple times.

Additionally, when you max out your training cycle to 4 and mark complete, you can’t start a new training cycle until you have advanced and acquired or upgraded the asset you were working towards. In other words, you can’t bank or “overcharge” your training. One at a time only! The second and third ability are fairly normal uses of holodecks in scifi, so you’re likely familiar with them. Don’t forget to have the holodeck run wild when you get a miss!

## Quest Starter
> A trusted friend convinced you to blow off some steam in the holodeck by running their favorite Dickson Tracey holonovel, a story about a detective taking on the mob. Unfortunately, while inside the program, something went wrong and the safety protocols shut down trapping you in the program. The only way out is to see the story through to the end. Was this a random accident, or was there nefarious code hidden in the holonovel your friend sent? If if was nefarious, were you betrayed, or was your friend used by an enemy? Are there clues in the story itself? ^QuestStarter

## Tags

| Previous Asset| Tags | Next Asset |
| :--- | :---: | ---: |
| **[[AST_External Refit\|EXTERNAL REFIT]]** | #Starsmith/Assets/Modules - #AssetDeck/Starsmith-Assets | **[[AST_Stabilizers\|STABILIZERS]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>