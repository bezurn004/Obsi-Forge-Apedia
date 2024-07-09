---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Ask the Oracle (move)"
PageType: Move
PageCategory: Fate
PageOrder: 1

## Move
MoveName: "Ask the Oracle"
InlineCmd: ATO
Trigger: "When you seek to resolve questions, discover details, reveal locations, determine how other characters respond, or trigger encounters or events"
RollType: Oracle
RollTable: Oracle/YesNo
ReferencedMoves: 
  - None
---
# [[_Moves Index|Moves]] - [[_Fate Moves|Fate]]: Ask the Oracle
## Ask The Oracle: Move Card
>[!abstract]  Trigger and Preparation
>**When you seek to resolve questions, discover details, reveal locations, determine how other characters respond, or trigger encounters or events,** you may... ^trigger

> [!tip]- Oracles and Guided Play
> In guided play, the guide is the oracle. When the players pose a question or a situation creates uncertainty, the guide can simply decide an answer, Ask the Oracle for inspiration, or turn the question back to the players. ^group-play

> [!oracle] Oracle Roll
>  You may… 
>- Draw a conclusion: Decide the answer based on the most interesting and obvious result. 
>- Spark an idea: Use an oracle table or other random prompt. 
>- Ask a yes/no question: Decide the odds of a yes, and roll on the table below to check the answer.
>- Pick two: Envision two options. Rate one as likely, and roll on the table below to see if it is true. If not, it is the other.
> > ![[#^table-ask-the-oracle]]^oracle-roll

## Full Description
In solo or co-op play, use this move when you have a question about the outcome of an action, an aspect of your setting, or a narrative event. In guided play, the guide can Ask the Oracle to gain inspiration or respond to player questions. 

### Ask the Oracle Table
| Chance | is yes |
| --- | --- |
| Small | 10 or less |
| Unlikely | 25 or less |
| 50/50 | 50 or less |
| Likely | 75 or less |
| Almost Certain | 90 or less |
^table-ask-the-oracle

### Draw Conclusion
The most basic use of this move, and a fundamental approach when you are filling the gaps of your story or world, is to simply decide the answer. Think it over for a moment (or talk it out), and go with what seems most appropriate or introduces the most potential for drama and excitement.  

Your first instinct is often the right one. If it leapt to mind, it’s probably a good fit for the current situation. But if your initial impulse doesn’t excite or interest you, give it more thought. Wait for an “aha” moment. 

If you’re still not sure of the answer, or want to put it in the hands of fate, you have some other options. See below for details.

> [!cite]- Narrative example
> You face a peril on the surface of a furnace world. What do you encounter? Since you already established that this planet is fraught with ash storms, you envision dark clouds gathering…

### Spark an Idea
The next option is to ask a question and use an oracle table or other random generator to reveal the answer.

See [[_OCL_Index|Oracles Summary]] for an array of oracle tables suited to playing _Starforged_. This includes generators for locations, people, creatures, and starships, along with abstract oracles that you interpret as appropriate to your question and the current situation. 

You can also use your own preferred tools to help spark ideas, such as online generators for character names, or tarot cards for visual inspiration.

> [!cite]- Narrative example
> You roll a weak hit as you attempt to Compel an informant to give up the location of a fugitive. Per the move, your contact makes a demand or counteroffer. What do they want? You roll on the [[OCL_Core_Action-Theme|Action/Theme Oracle]] oracle tables for inspiration. The oracle answers “Preserve Life.” You envision the contact revealing a personal connection to the fugitive, and asking for a promise that you’ll bring them in unharmed 

### Ask a Yes/No Question
You can ask a binary yes/no question and leave the answer open to fate. 

Decide the likeliness of a yes answer, and roll your oracle dice to get the result. For ex[](OCL_Core.md#Action%20and%20Theme)kely, you must roll 25 or less for a yes. Otherwise, the answer is no. 

> [!cite]- Narrative example
> You reach an orbital station at the end of a long expedition, but the outpost is unresponsive. You envision making a close flyby in your ship, and Ask the Oracle, “are there any signs of damage?” You set the odds to 50/50. 

### Pick Two
The final option is to ask a question as a choice between two viable results. 

Rate one of your choices as likely, and roll on the table. If it’s a yes, the likely pick is your answer. If not, it’s the other. Use this approach when the question is more open-ended than a simple yes/no, but you have a couple of alternatives in mind. 

> [!cite]- Narrative example
> You are ambushed on the outskirts of planetside settlement. But by whom? You’ve had run-ins with both the local authorities and a band of territorial scavengers, so you Ask the Oracle to reveal the answer. You set the scavengers as the likely culprit

### Rolling a Match
A match on your oracle dice when rolling on the yes/no table should trigger an extreme result or narrative surprise. This can mean an all-caps “HELL YES!” or “HELL NO!” or a yes or no but with an interesting twist or dramatic complication.

When you’re unsure what a match might mean, you can roll on another oracle table for inspiration. If you’re still left scratching your head, just move on. Resolving a match is never a requirement. It’s just a way to introduce narrative turning points that lead you along unexpected paths. Head down the rabbit hole, but don’t get stuck in it. 

### Questions Upon Questions
You can come back to the yes/no table and ask a follow-up question to clarify or affirm a result. However, don’t let one question snowball into a series of more specific questions. Even when playing solo, oracles should be the spice of your game, not the main course. Ask a question or two, decide what it means, and move on. When in doubt, follow your gut. Your first instinct is probably the right one. Go with it. 

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
| **[[_Fate Moves\|Fate Moves]]** | #Pedia/Moves/Fate | **[[MV_Pay the Price\|Pay the Price (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>