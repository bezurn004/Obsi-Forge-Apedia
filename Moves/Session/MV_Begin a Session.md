---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Begin a Session (move)"
PageType: Move
PageCategory: Session
PageOrder: 1

## Oracle
MoveName: Begin a Session
InlineCmd: BAS
Trigger: "When you begin a significant session or chapter of play"
RollType: Oracle
RollStat: Oracle/BeginSession
Automatic Hit: "+1 Momentum"
ReferencedMoves: 
  - [[MV_Set a Flag]]
---
# [[_Moves Index|Moves]] - [[_Session Moves|Session]]: Begin a Session

## Begin a Session: Move Card
>[!abstract]  Trigger and Preparation
>**When you begin a significant session or chapter of play**, do all of the following. ^trigger

> [!question] Action
> 1. Identify or adjust flagged content and [[MV_Set a Flag|Set a Flag]]
>2. Review or recap what happened last session.
>3. Set the scene by envisioning your character’s current situation and intent.
> - In addition, you may spotlight a new danger, opportunity, or insight. This can include a scene hidden from your character’s perspective.
> 	- If you do, envision a brief vignette (you may roll or choose on the table below for inspiration).
> 	- All players take +1 momentum
> > ![[#^table-vignette]]
> 
> > [!cite]- Narrative prompt
> > Envision as you return to play from the viewpoint of your characters. ^action

## Full Description
Make this move as a checkpoint at the start of a session. Take a few moments to set or adjust any flagged content, reflect on recent events in your story, and frame the current situation. 

You may also use the optional prompt to introduce a brief vignette. This purely narrative scene can enrich your setting, reveal aspects of your character, add details to people and factions, or introduce “off-screen” complications and opportunities. If you are playing with others, work together to envision the scene, or take turns from one session to the next. 

If you are playing solo, you may often play for only a few minutes a time, picking up the game and leaving it again as casually as you would when reading a novel. If you are playing co-op, you might participate in an online game using asynchronous chat. If your game isn’t organized into discrete sessions, you should use this move to mark a new chapter. The beginning of a new chapter can come after a dramatic cliffhanger, or when a meaningful narrative thread has been resolved. Emphasizing those transitions will add structure create moments to recap and reflect.

### Begin a Session Table

| 1d100 | Result |
|:---:| --- |
| 1-10 | Flashback reveals an aspect of your background or nature |
| 11-20 | Flashback reveals an aspect of another character, place, or faction |
| 21-30 | Influential character or faction is introduced or given new detail |
| 31-40 | Seemingly unrelated situations are shown to be connected |
| 41-50 | External factors create new danger, urgency, or importance for a quest |
| 51-60 | Important character is put in danger or suffers a misadventure |
| 61-70 | Key location is made unsafe or becomes mired in conflict |
| 71-80 | Unexpected return of an enemy or threat |
| 81-90 | Peril lies ahead or lurks just out of view |
| 91-100 | Unforeseen aid is on the way or within reach |
^table-vignette

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
| **[[_Session Moves\|Session Moves]]** | #Pedia/Moves/Session | **[[MV_Set a Flag\|Set a Flag (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>