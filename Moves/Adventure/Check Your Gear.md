---
Name: "Check Your Gear"
PageType: Move
PageCategory: Adventure
InlineCmd: CYG
RollType: Action
RollStat: Supply
---
# [[_Moves Index|Moves]]: Check your gear
### Categories: [[_Adventure Moves|Adventure Moves]]
>[!abstract]  Context and Preparation
>When you check to see if you have a specific helpful item or resource...

> [!error]- Improper Usage
> Do not check your gear when the item is mundane to the context of the narrative.  If an item is extraordinary for the narrative situation then it is impossible to have.  If the item relates to something in the environment around you, instead Ask the Oracle to see if fate is on your side.

> [!warning] Action Roll
> Roll + supply

> [!challenge-strong] On strong hit
> Take +1 Momentum
> >[!quote] Narrative prompt
> >You’ve got it. Envision your character leveraging this item or resource. 

> [!challenge-weak] On a weak hit
> Choose one of the following reductions to your meters
> 1. Your supply is reduced: Sacrifice Resources (-1)
> 2. You must make do with something that’s not a perfect fit for the situation: Lose Momentum (-2)
>    
> >[!quote] Narrative prompt
> >You have whats needed for the situation, but it is not ideal.  What happens next?

> [!challenge-miss] On a miss
> You must [[Pay the Price]]
> >[!quote] Narrative prompt
> >You don’t have what you need, and things get worse.
> >This may mean turning the peril of the current situation up a notch or inflicting an immediate negative outcome.. 

## Full Description
In Starforged, you don’t track a detailed inventory of items and resources. Instead, you are equipped as appropriate to the situation and your vision for your character. This may lead to circumstances where you aren’t sure if you are prepared for an unexpected challenge. When you check to see if you have a particular item or resource on-hand, make this move. 

> [!quote]- Narrative example
> You are bitten by a snake-like creature on a jungle world, and suffer an intense reaction from its venom. Do you have an appropriate antitoxin in your medkit? You Check Your Gear to find out, and roll a strong hit. You take the momentum bonus, and are now in a position to Heal using the antitoxin to recover your lost health. 

### Move Categories
[[_Adventure Moves|Adventure Moves]]

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
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Adventure 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>