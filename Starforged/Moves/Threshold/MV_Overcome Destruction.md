---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Overcome Destruction (move)"
PageType: Move
PageCategory: Threshold
PargeOrder: 3

## Move
MoveName: "Overcome Destruction"
InlineCmd: OD
Trigger: "When your command vehicle is destroyed or irrevocably lost"
RollType: Progress
ProgressTrack: Bonds
ReferencedMoves: 
  - [[MV_Withstand Damage]]
  - [[MV_Advance]]
  - [[MV_Swear an Iron Vow]]
  - [[MV_Fullfill Your Vow]]
  - [[MV_Forsake Your Vow]]
---
# [[_Moves Index|Moves]] - [[_Threshold Moves|Threshold]]: Overcome Destruction
## Overcome Destruction: Move Card
>[!abstract]  Trigger and Preparation
>**When your command vehicle is destroyed or irrevocably lost,** you must discard the asset, along with any modules and docked support vehicles. If you survive, you may use your connections to replace some of what was lost.  ^trigger

> [!error]- Narrative Replacement
> If your command vehicle is destroyed and you secure a replacement through narrative events, that ship is an [[GP_Vehicles#Incidental Vehicles|incidental vehicle]] until you [[MV_Advance|Advance]] and spend experience to secure it as an asset. ^narrative-replacement

> [!tip]- Group Play
> If you are playing with allies, one of you represents the group to make the Overcome Destruction progress roll. You can envision this as reaching out to a unique connection or shared connection. If you must mark indebted, decide if that impact is tied to a single character (likely the one making the move), or the group. If everyone is affected by this liability, you should each mark the impact ^group-play

> [!progress] Progress Roll
> To learn the cost, roll the challenge dice and compar[](GB_Vehicles.md#Incidental%20Vehicles)rack.  ^progress-roll

> [!challenge-strong] On strong hit
> You may call in a favor. This comes without conditions.
>![[#^replacement-cost]]
> > [!cite]- Narrative Prompt
> > Who comes to aid you in restoring your Starship? ^strong-hit

> [!challenge-weak] On a weak hit
> You owe someone. You must do the following...
>-  Mark **[[GB_Impacts#Burdens|indebted]]**
>- [[MV_Swear an Iron Vow|Swear an Iron Vow]] to complete an extreme _ranked_ quest in their service.
>	- When you complete the duty-bound quest _with [[MV_Fullfill Your Vow|Fullfill Your Vow]]_, clear the impact.
> ![[#^replacement-cost]]
> > [!cite]- Narrative prompt
> > Who do you owe, and what quest must be taken before the debt is clear? ^weak-hit

> [!challenge-miss] On a miss
> As with a weak hit, but this quest is one of the following...
>- Against your nature
>- Forces you to [[MV_Forsake Your Vow|Forsake Your Vow]] on another quest.
>- It is in the service of an enemy.
>![[#^replacement-cost]]
> > [!cite]- Narrative prompt
> > Who do you owe, and what painful  quest is to be undertaken? ^miss

> [!mechanics]- Replacement Cost
> If you accept the cost, take 1 experience for every marked ability on the discarded assets (minimum 3 experience). Spend this experience only on a new command vehicle, modules, and support vehicles. ^replacement-cost

## Full Description
Make this move when your ==[[GB_Vehicles#Command Vehicle|command vehicle]]== is demolished, damaged beyond repair, or irrevocably lost. You may be prompted to Overcome Destruction when you [[MV_Withstand Damage|Withstand Damage]] and fail, or in response to a dramatic narrative circumstance that makes the loss of your command vehicle inescapable.

First, discard the command vehicle asset along with any modules and docked support vehicles. Then, envision how you survive and what you do next. If you are stranded on a remote planet, drifting through space in an escape pod, or captured by an enemy, finding your way back to your life as an independent spacer can be an adventure of its own.

When you are in a position to reach out to your connections, you may make a ==[[GB_Progress Tracks#Progress Rolls|progress roll]]== against your ==[[GB_Legacy Tracks|bonds legacy track]]==. Your progress score is the number of filled boxes on that track. Only add fully filled boxes (those with four ticks). Then, roll your challenge dice, compare to your progress score, and resolve a strong hit, weak hit, or miss. You may not burn momentum on this roll, and you are not affected by negative momentum. 

The result determines the narrative cost as you lean on the support of your connections. Envision who you reach out to, and the cost you must bear, as appropriate to the result of your progress roll. This may mean that you (the player) are ahead of your character’s understanding of what happens next. Pull some narrative strings to put your character in touch with (or on a collision course with) a connection that fits the move’s outcome.

A strong hit as you Overcome Destruction finds you in the good graces of a connection who owes you a favor. Envision who among your connections offers help. 

A weak hit forces you to take on a quest as repayment. Envision the nature of this quest as appropriate to the connection’s role and goals. You must mark the [[GB_Impacts#Burdens|indebted impact]] to represent the burden of this obligation, and cannot clear the impact until you successfully [[MV_Fullfill Your Vow|Fullfill Your Vow]] on that quest. 

On a miss, you must accept a quest and mark indebted to gain the help of a connection. In addition, the vow fundamentally undermines your own objectives or nature. To regain what was lost, what promises will you break? What vows will you forsake? What ideals will you sacrifice? 

If you move forward under those conditions, take the experience as defined by the move, and [[MV_Advance|Advance]] to spend it. This experience is not tied to your legacy tracks and can only be spent to purchase and upgrade a new command vehicle, modules, and support vehicles. If you are holding this experience in reserve until you are in a position to obtain those assets through the course of your story, make note of it. 

If you score a weak hit or miss and don’t accept the quest and the indebted impact, you don’t gain the consolation experience. You must instead use experience accrued through your legacy tracks to replace what was lost. 

> [!cite]- Narrative example
> Following the disastrous loss of your [[AST_Starship|Starship (asset)]] and a fraught escape from the hold of a pirate ship, you find your way back to populated space. What will a fresh start cost? You make the Overcome Destruction progress roll to find out. Unfortunately, you score a miss. You envision receiving a communication from one of your less reputable connections, a notorious weapons dealer. They offer to serve as your patron and fund a new ship, but only if you swear to transport a cache of deadly weapons into the heart of a warring sector. 

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
| **[[MV_Face Desolution\|Face Desolution (move)]]** | #Pedia/Moves/Threshold | **[[_Legacy Moves\|Legacy Moves]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>