---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Compel (move)"
PageType: Move
PageCategory: Adventure
PageOrder: 4

## Oracle
MoveName: Compel
InlineCmd: COMPEL
RollType: Action
RollStat: [Heart, Iron, Shadow]
Trigger: "When you try to persuade someone or make them an offer"
Approach: ["Charm","Encourage","Pacify","Barter","Threaten","Incite",Lie","Swindle"]
Strong Hit: "+1 Momentum"
Weak Hit: "+1 Momentum"
Miss: Move/Pay_the_Price
ReferencedMoves: 
  - [[MV_Ask the Oracle]]
  - [[MV_Pay the Price]]
  - [[MV_Test Your Relationship]]
---
# [[_Moves Index|Moves]] - [[_Adventure Moves|Adventure]]: Compel
## Compel: Move Card
>[!abstract]  Trigger and Preparation
>**When you try to persuade someone or make them an offer...** ^trigger

> [!error]- Improper Usage 
> Making the Compel move doesn’t give you free rein to control the actions of other characters in your world. Remember: fiction first. Consider their motivations. 
>- What is your leverage over them? 
>- What do they stand to gain or avoid? 
>- Do you have an existing relationship? 
> 
> If your argument has no merit, or your threat or promise carries no weight, you can’t make this move. You can’t intimidate your way out of a situation where you are at a clear disadvantage. You can’t barter when you offer nothing of value. If you are unsure, [[MV_Ask the Oracle|Ask the Oracle]], “Would they consider this?” If the answer is yes, make the move.
> 
> On the other hand, if their positive response is all but guaranteed, you are acting obviously in their best interest or offering a trade of good value, don’t make the move. Just make it happen. Save the move for times when the situation is uncertain and dramatic. ^improper

> [!warning] Action Roll
>- Charm, Pacify, Encourage, or Barter: Roll +heart
>- Threaten or Incite: Roll +iron
>- Lie or Swindle: Roll +shadow ^action-roll

> [!challenge-strong] On a strong hit
> Take +1 Momentum
> >[!cite]- Narrative prompt
> >They agree. Move forward with their cooperation.  What happens next? ^strong-hit

> [!challenge-weak] On a weak hit
> Take +1 Momentum
> 
> >[!cite]- Narrative prompt
> >They offer a counter-proposal or introduce a complicating factor. Look to the fiction to understand their response. What would they want? What would satisfy their concerns or motivate them to comply? If you’re not sure, [[MV_Ask the Oracle|Ask the Oracle]].
> >Then, if you accept their offer, you gain their (perhaps grudging) support. 
> >If not, you need to find another path. ^weak-hit

> [!challenge-miss] On a miss
> You must [[MV_Pay the Price|Pay the Price]]
> >[!cite]- Narrative prompt
> >They are insulted, angered, inflexible, see through your lies, or demand something with a dire cost. Their response should introduce new dangers or complications. ^miss

## Full Description
When you act to persuade someone to do as you ask, or to give you something of value, make this move. It might be through bargaining, charm, diplomacy, intimidation, or trickery. Use the appropriate stat based on your approach and roll to see what happens.

If you promise something as part of the Compel move, but then fail to do as you promised, others should respond accordingly. Perhaps it means a rude welcome when next you return to this community. If they are powerful, they may even act against you. If they are a connection, you would probably [[MV_Test Your Relationship|Test Your Relationship]]. Your actions, good or bad, should have ramifications for your story beyond the scope of the move.

> [!cite]-  Narrative example
> You are attempting to obtain a desperately needed part for your ship from a stingy equipment dealer. You know of their fondness for pre-cataclysm art; luckily you have a piece to offer in trade. But this relic is a fake. Do they fall for the con and agree to the deal? You roll +shadow to find out.

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
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[MV_Gather Information\|Gather Information (move)]]** | #Pedia/Moves/Adventure | **[[MV_Aid Your Ally\|Aid Your Ally (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>
