---
Name: "Swear an Iron Vow"
PageType: Move
PageCategory: Quest
InlineCmd: SAIV
RollType: Action
RollStat: Heart
Trigger: [""] 
Track: Progress(Encounter Objective[])
Strong Hit: ""
Weak Hit: []
Miss: ""
---
# [[_Moves Index|Moves]]: Swear an Iron Vow
### Categories: [[_Quest Moves|Quest Moves]]
>[!abstract]  Context and Preparation
>When you swear upon iron to complete a quest, write your vow and give it a [[Rank Vow]]...

> [!tip]- Group Play
> When allies join together to Swear an Iron Vow, this is a shared quest. One of you speaks for the group and makes the move. If you score a hit and take +momentum, only the character making the move takes that bonus. Others benefit narratively from your success or face the consequences of your failure. Once the quest is underway, you share a single progress track and mark progress together as you Reach a Milestone.

> [!warning] Action Roll
> Roll +heart. If you swear this vow to a connection, add +1; if you share a bond, add +2.

> [!challenge-strong] On strong hit
> Take +2 Momentum
> 
> > [!quote] Narrative prompt
> > Your path is clear, and you may envision how you begin the quest. 

> [!challenge-weak] On a weak hit
> Take +1 Momentum
> 
> > [!quote] Narrative prompt
> > The way forward is uncertain or complicated; investigation may be required to identify your next steps.

> [!challenge-miss] On a miss
> Do not mark progress to make the move [[Reach a Milestone]] until this set back has been resolved
> > [!quote] Narrative prompt
> > - You face a serious obstacle at the very start. It might be an unexpected event, someone working against you, or a personal conviction holding you back. 
> > - If unsure, [[Ask the Oracle]]. Your quest cannot properly begin until you deal with this complication, which means you do not [[Reach a Milestone]] and mark progress when overcoming it.

## Full Description
When you give your word to serve someone, resolve to undo a wrong, or undertake a personal ambition, make this move. 

First, give the vow a name and set the rank of your quest: troublesome, dangerous, formidable, extreme, or epic. Higher ranked vows require more effort and more focus in your story, but offer greater legacy rewards. An epic quest could be the endeavor of a lifetime, while a troublesome quest might be resolved in a few scenes. 

Then, envision how your character enacts the vow. Is this a moment of grudging acceptance or one of fiery determination? 

> [!quote]- Narrative example
> An agricultural settlement is preyed upon by raiders, and you Swear an Iron Vow to help them fight back. You hold the iron and speak the vow in the central square, witnessed by the hopeful farmers. 

## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, title) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Quest 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>