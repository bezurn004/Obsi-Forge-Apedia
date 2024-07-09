---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Continue a Legacy (move)"
PageType: Move
PageCategory: Legacy
PageOrder: 3

## Move
MoveName: "Continue a Legacy"
InlineCmd: CAL
Trigger: "When you retire from your life as Ironsworn, or succumb to death or desolation, you may create a new character in your established setting"
RollType: Progress
RollStat: [Quests, Bonds, Discovery]
ReferencedMoves: 
  - [[MV_Swear an Iron Vow]]
  - [[MV_Make a Connection]]
---
# [[_Moves Index|Moves]] - [[_Legacy Moves|Legacy]]: Continue a Legacy

## Continue A Legacy: Move Card
>[!abstract]  Trigger and Preparation
>**When you retire from your life as Ironsworn, or succumb to death or desolation**, you may create a new character in your established setting.... ^trigger

> [!tip]- Group Play
> If you are playing with allies, and everyone is making this move at once, the number of results can be a bit overwhelming. You may instead divide the progress rolls among players so that you are only choosing three results in total, one for each legacy track. If your character is the only one who retired or succumbed, make the move as normal; then, work with the other players to bring your new character into the story ^group-play

> [!progress] Progress Roll
>  If you do, roll the challenge dice and compare to each of the former character’s legacy tracks: quests, bonds, and discoveries (one roll per track).
>  For each roll, refer to the move result options below. ^progress-roll

> [!challenge-strong] On strong hit
>  Choose one option below, or one from the weak hit or miss options.
> -  Follow their path: Take one path or companion asset from the former character (at no cost), including any marked abilities.
> -  Share a connection: Take one connection from the former character, including any accrued progress or bond benefits.
> - Accept an inheritance: Take the former character’s command vehicle and one module or support vehicle (at no cost), including any marked abilities.
> > [!cite]- Narrative prompt
> > Envision the chosen option and how it will impact the new character. ^strong-hit

> [!challenge-weak] On a weak hit
> Choose one option below, or one from the miss options.
>-  See it through: Choose one of the former character’s unfinished quests, and [[MV_Swear an Iron Vow|Swear an Iron Vow]] (with an automatic strong hit) to see it done. You may immediately mark up to half their earned progress (round down) on this quest.
>- Rebuild a connection: Name one of the former character’s connections, and envision how time or circumstances have changed them in a dramatic way. When you [[MV_Make a Connection|Make a Connection]] with them, take an automatic strong hit and mark two ticks on your bonds legacy track.
>- Explore familiar ground: Name a location that was meaningful to the former character. When you first visit that place, envision how it has changed or is endangered. Then, mark two ticks on your discoveries legacy track.
> > [!cite]- Narrative prompt
> > Envision the chosen option and how it will impact the new character. ^weak-hit

> [!challenge-miss] On a miss
> Choose one option:
>- Deal with the aftermath: Envision how one of your former character’s foes has gained power or influence.
>- Switch loyalties: Envision how you begin in opposition to your former character’s beliefs, goals, or allegiances.
>-  Open Pandora’s Box: Envision how an advancement or discovery has unleashed unexpectedly dire consequences.
> > [!cite]- Narrative prompt
> > Envision the chosen option and how it will impact the new character. ^miss

## Full Description
How have you left your mark upon the Forge? What do you leave for those who follow in your footsteps? If your character chooses to leave the path of the Ironsworn or suffers a premature end through death or desolation, make this move to discover their legacy. 

First, make a separate progress roll against each of your ==legacy tracks==: quests, bonds, and discoveries. Tally the progress score for each track by counting the number of filled boxes. Only add fully filled boxes (those with four ticks). You may not burn momentum on these rolls, and you are not affected by negative momentum. 

Once you resolve the number of strong hits, weak hits, and misses among the three rolls, choose your options from the move. You can pick any outcome at or below your level of success, but cannot choose a specific result more than once.

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
| Previous Page | Tags | Next Section |
|:--- |:---:| ---:|
| **[[MV_Advance\|Advance (move)]]** | #Pedia/Moves/Legacy | **[[_Fate Moves\|Fate Moves]]** |


<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>