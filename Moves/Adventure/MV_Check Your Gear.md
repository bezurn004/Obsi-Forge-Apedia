---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Check Your Gear (move)"
PageType: Move
PageCategory: Adventure
PageOrder: 6

## Oracle
MoveName: "Check Your Gear"
InlineCmd: CYG
RollType: Action
RollStat: Supply
Trigger: "When you check to see if you have a specific helpful item or resource"
Approach:
Stat: supply
ReferencedMoves: 
  - [[MV_Ask the Oracle]]
  - [[MV_Sacrifice Resources]]
  - [[MV_Lose Momentum]]
  - [[MV_Pay the Price]]
---
# [[_Moves Index|Moves]] - [[_Adventure Moves|Adventure]]: Check your gear
## Check Your Gear: Move Card
>[!abstract]  Trigger and Preparation
>**When you check to see if you have a specific helpful item or resource...** ^trigger

> [!error]- Improper Usage
> Do not check your gear when the item is mundane to the context of the narrative.  If an item is extraordinary for the narrative situation then it is impossible to have.  If the item relates to something in the environment around you, instead [[MV_Ask the Oracle|Ask the Oracle]] to see if fate is on your side. ^improper

> [!warning] Action Roll
> Roll + supply ^action-roll

> [!challenge-strong] On strong hit
> Take +1 Momentum
> >[!cite]- Narrative prompt
> >You’ve got it. Envision your character leveraging this item or resource. ^strong-hit

> [!challenge-weak] On a weak hit
> Choose one of the following reductions to your meters
> 1. Your supply is reduced: [[MV_Sacrifice Resources|Sacrifice Resources]] (-1)
> 2. You must make do with something that’s not a perfect fit for the situation: [[MV_Lose Momentum|Lose Momentum]] (-2)
> >[!cite]- Narrative prompt
> >You have what's needed for the situation, but it is not ideal.  What happens next? ^weak-hit

> [!challenge-miss] On a miss
> You must [[MV_Pay the Price|Pay the Price]]
> >[!cite]- Narrative prompt
> >You don’t have what you need, and things get worse.
> >This may mean turning the peril of the current situation up a notch or inflicting an immediate negative outcome..  ^miss

## Full Description
In Starforged, you don’t track a detailed inventory of items and resources. Instead, you are equipped as appropriate to the situation and your vision for your character. This may lead to circumstances where you aren’t sure if you are prepared for an unexpected challenge. When you check to see if you have a particular item or resource on-hand, make this move. 

> [!cite]- Narrative example
> You are bitten by a snake-like creature on a jungle world, and suffer an intense reaction from its venom. Do you have an appropriate antitoxin in your medkit? You Check Your Gear to find out, and roll a strong hit. You take the momentum bonus, and are now in a position to Heal using the antitoxin to recover your lost health. 

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
WHERE contains(PageType, "Move") & contains(ReferencedMoves, this.file.name) & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Previous Page | Tags | Next Section |
|:--- |:---:| ---:|
| **[[MV_Aid Your Ally\|Aid Your Ally (move)]]** | #Pedia/Moves/Adventure  | **[[_Quest Moves\|Quest Moves]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>