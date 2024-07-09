---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Gather Information (move)"
PageType: Move
PageCategory: Adventure
PageOrder: 3

## Move
MoveName: "Gather Information"
InlineCmd: GI
Trigger: "When you search for clues, conduct an investigation, analyze evidence, or do research"
Approach: 
RollStat: Wits
RollType: Action
ReferencedMoves: 
  - [[MV_Face Danger]]
  - [[MV_Secure an Advantage]]
  - [[MV_Gain Ground]]
  - [[MV_React Under Fire]]
  - [[MV_Ask the Oracle]]
  - [[MV_Pay the Price]]
---
# [[_Moves Index|Moves]] - [[_Adventure Moves|Adventure]]: Gather Information
## Gather Information: Move Card
>[!abstract]  Trigger and Preparation
>**When you search for clues, conduct an investigation, analyze evidence, or do research...** ^trigger

> [!error]- Improper Usage
> How does this differ from other moves using insight or observation? 
> * When you’re forced to react with awareness or knowledge to deal with an immediate threat or complicated activity, that’s [[MV_Face Danger|Face Danger]].
> * When you size up your options or use expertise to bolster your position, that’s [[MV_Secure an Advantage|Secure an Advantage]].
> * If you’re in a fight, use [[MV_Gain Ground|Gain Ground (move)]] and [[MV_React Under Fire|React Under Fire]] to devise clever strategies or overcome dangers. 
> * If you learn the nature of something without taking direct action, [[MV_Ask the Oracle|Ask the Oracle]]. ^improper

> [!warning] Action Roll
> Roll +Wits ^action-roll

> [!challenge-strong] On a strong hit
>  Take +2 Momentum
> > [!cite]- Narrative prompt
> > You gain valuable new information. You know what you need to do next. Envision what you learn.  If unsure, [[MV_Ask the Oracle|Ask the Oracle]] to provide inspiration. ^strong-hit

> [!challenge-weak] On a weak hit
> Take +1 Momentum
> > [!cite]- Narrative prompt
> > You’ve learned something important, but it makes your quest more complicated or dangerous. 
> > Your character’s position is improved through the discovery of this information, but it’s unwelcome news all the same. ^weak-hit

> [!challenge-miss] On a miss
> This is a dreadful turn, and you must [[MV_Pay the Price|Pay the Price]].
> > [!cite]- Narrative prompt
> > A harrowing new threat is revealed
> > You learn of something that contradicts previous information, or severely complicates your quest. ^miss

## Full Description
Use this move when you make a careful search or do fact-finding. What you uncover may reveal the best path forward, or introduce new twists and turns in your quest.

But if you’re spending time searching, investigating, analyzing, interrogating, especially related to a quest, that’s when you Gather Information. Think of it this way: Gather Information is focused on story, tending to introduce new complications. Those other moves are focused on situations. Use the move most appropriate to the circumstances and your intent.

> [!cite]- Narrative example
> You are sworn to capture an infamous fugitive who is rumored to be hiding out at an outpost. You envision making discreet inquiries among the locals, and Gather Information to see what you learn.

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
| **[[MV_Secure an Advantage\|Secure an Advantage (move)]]** | #Pedia/Moves/Adventure - #Pedia/Moves/Scene_Challenge | **[[MV_Compel\|Compel (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>