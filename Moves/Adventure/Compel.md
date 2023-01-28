---
Name: "Compel"
PageType: Move
PageCategory: Adventure
InlineCmd: COMPEL
RollType: Action
RollStat: [Heart, Iron, Shadow]
Trigger: ["Charm","ENcourage","Pacify","Barter","Threaten","Incite","Incite","Lie","Swindle"]
Strong Hit: "+1 Momentum"
Weak Hit: "+1 Momentum"
Miss: Move/Pay_the_Price
---
# [[_Moves Index|Moves]]: Compel
### Categories: [[_Adventure Moves|Adventure Moves]]
>[!abstract]  Context and Preparation
>When you try to persuade someone or make them an offer...

> [!error]- Improper Usage 
> Making the Compel move doesn’t give you free rein to control the actions of other characters in your world. Remember: fiction first. Consider their motivations. 
> * What is your leverage over them? 
> * What do they stand to gain or avoid? 
> * Do you have an existing relationship? 
> 
> If your argument has no merit, or your threat or promise carries no weight, you can’t make this move. You can’t intimidate your way out of a situation where you are at a clear disadvantage. You can’t barter when you offer nothing of value. If you are unsure, Ask the Oracle, “Would they consider this?” If the answer is yes, make the move.
> 
> On the other hand, if their positive response is all but guaranteed, you are acting obviously in their best interest or offering a trade of good value, don’t make the move. Just make it happen. Save the move for times when the situation is uncertain and dramatic.

> [!warning] Challenge Roll
>- Charm, Pacify, Encourage, or Barter: Roll +heart
>- Threaten or Incite: Roll +iron
>- Lie or Swindle: Roll +shadow

> [!challenge-strong] On a strong hit
> Take +1 Momentum
> >[!quote] Narrative prompt
> >They agree. Move forward with their cooperation.  What happens next?
> 

> [!challenge-weak] On a weak hit
> Take +1 Momentum
> 
> >[!quote] Narrative prompt
> >They offer a counter-proposal or introduce a complicating factor. Look to the fiction to understand their response. What would they want? What would satisfy their concerns or motivate them to comply? If you’re not sure, Ask the Oracle.
> >Then, if you accept their offer, you gain their (perhaps grudging) support. 
> >If not, you need to find another path.

> [!challenge-miss] On a miss
> You must [[Pay the Price]]
> >[!quote] Narrative prompt
> >They are insulted, angered, inflexible, see through your lies, or demand something with a dire cost. Their response should introduce new dangers or complications.

## Full Description
When you act to persuade someone to do as you ask, or to give you something of value, make this move. It might be through bargaining, charm, diplomacy, intimidation, or trickery. Use the appropriate stat based on your approach and roll to see what happens.

If you promise something as part of the Compel move, but then fail to do as you promised, others should respond accordingly. Perhaps it means a rude welcome when next you return to this community. If they are powerful, they may even act against you. If they are a connection, you would probably Test Your Relationship. Your actions, good or bad, should have ramifications for your story beyond the scope of the move.

> [!quote]-  Narrative example
> You are attempting to obtain a desperately needed part for your ship from a stingy equipment dealer. You know of their fondness for pre-cataclysm art; luckily you have a piece to offer in trade. But this relic is a fake. Do they fall for the con and agree to the deal? You roll +shadow to find out.

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
