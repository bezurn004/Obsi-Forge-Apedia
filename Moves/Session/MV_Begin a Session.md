---
Alias: "Begin a Session (move)"
PageType: Move
PageCategory: Session
InlineCmd: BAS
Trigger: "When you begin a significant session or chapter of play"
RollType: Oracle
RollStat: Oracle/BeginSession
Automatic Hit: "+1 Momentum"
---
# [[_Moves Index|Moves]] - [[_Session Moves|Session]]: Begin a Session

## Move Card
>[!abstract]  Trigger and Preparation
>When you begin a significant session or chapter of play, do all of the following.
>- Identify or adjust flagged content and [[MV_Set a Flag|Set a Flag]]
>- Review or recap what happened last session.
>- Set the scene by envisioning your character’s current situation and intent.

> [!oracle] Oracle Roll
> In addition, you may spotlight a new danger, opportunity, or insight. This can include a scene hidden from your character’s perspective. If you do, envision a brief vignette (you may roll or choose on the table below for inspiration). 

> [!challenge-strong] Return to Play
> All players take +1 momentum
> > [!quote] Narrative prompt
> > Envision as you return to play from the viewpoint of your characters.

### Begin a Session Table
| 1d100 | Result |
| :---: | --- |
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

## Full Description
Make this move as a checkpoint at the start of a session. Take a few moments to set or adjust any flagged content, reflect on recent events in your story, and frame the current situation. 

You may also use the optional prompt to introduce a brief vignette. This purely narrative scene can enrich your setting, reveal aspects of your character, add details to people and factions, or introduce “off-screen” complications and opportunities. If you are playing with others, work together to envision the scene, or take turns from one session to the next. 

If you are playing solo, you may often play for only a few minutes a time, picking up the game and leaving it again as casually as you would when reading a novel. If you are playing co-op, you might participate in an online game using asynchronous chat. If your game isn’t organized into discrete sessions, you should use this move to mark a new chapter. The beginning of a new chapter can come after a dramatic cliffhanger, or when a meaningful narrative thread has been resolved. Emphasizing those transitions will add structure create moments to recap and reflect.

## Related Assets
```dataview
TABLE without ID
	link(file.link, alias) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, alias) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags

#Pedia/Moves/Session

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>