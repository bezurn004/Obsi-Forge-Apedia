---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Swear an Iron Vow (SF Moves)"
PageType: Move
PageCategory: Quest
PageOrder: 1

## Move
MoveName: "Swear an Iron Vow"
InlineCmd: SAIV
Trigger: "When you swear upon iron to complete a quest"
RollType: Action
RollStat: Heart
Track: Progress(Encounter Objective[])
Strong Hit:
Weak Hit:
Miss:
ReferencedMoves: 
  - [[SF_CH3_Reach a Milestone]]
  - [[SF_CH3_Ask the Oracle]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Quest Moves|Quest]]: Swear an Iron Vow
## Swear An Iron Vow: Move Card
>[!abstract]  Trigger and Preparation
>**When you swear upon iron to complete a quest**, write your vow and give it a rank... ^trigger

> [!tip]- Group Play
> When allies join together to Swear an Iron Vow, this is a shared quest. One of you speaks for the group and makes the move. If you score a hit and take +momentum, only the character making the move takes that bonus. Others benefit narratively from your success or face the consequences of your failure. Once the quest is underway, you share a single progress track and mark progress together as you Reach a Milestone. ^group-play

> [!warning] Action Roll
> Roll +heart. If you swear this vow to a connection, add +1; if you share a bond, add +2. ^action-roll

> [!challenge-strong] On strong hit
> Take +2 Momentum
> > [!cite]- Narrative prompt
> > Your path is clear, and you may envision how you begin the quest. ^strong-hit

> [!challenge-weak] On a weak hit
> Take +1 Momentum
> > [!cite]- Narrative prompt
> > The way forward is uncertain or complicated; investigation may be required to identify your next steps. ^weak-hit

> [!challenge-miss] On a miss
> Do not mark progress to make the move [[SF_CH3_Reach a Milestone|Reach a Milestone]] until this set back has been resolved
> > [!cite]- Narrative prompt
> > - You face a serious obstacle at the very start. It might be an unexpected event, someone working against you, or a personal conviction holding you back. 
> > - If unsure, [[SF_CH3_Ask the Oracle|Ask the Oracle]]. Your quest cannot properly begin until you deal with this complication, which means you do not [[SF_CH3_Reach a Milestone|Reach a Milestone]] and mark progress when overcoming it. ^miss

## Full Description
When you give your word to serve someone, resolve to undo a wrong, or undertake a personal ambition, make this move. 

First, give the vow a name and set the rank of your quest: troublesome, dangerous, formidable, extreme, or epic. Higher ranked vows require more effort and more focus in your story, but offer greater legacy rewards. An epic quest could be the endeavor of a lifetime, while a troublesome quest might be resolved in a few scenes. 

Then, envision how your character enacts the vow. Is this a moment of grudging acceptance or one of fiery determination? 

> [!cite]- Narrative example
> An agricultural settlement is preyed upon by raiders, and you Swear an Iron Vow to help them fight back. You hold the iron and speak the vow in the central square, witnessed by the hopeful farmers. 

*156 CHAPTER 3: GAMEPLAY IN DEPTH*

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, MoveName) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(ReferencedMoves, this.file.name) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Section Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[_SF_CH3_Quest Moves\|Quest Moves (SF)]]** | #Starforged/Moves/Quest | **[[SF_CH3_Reach a Milestone\|Reach a Milestone (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>