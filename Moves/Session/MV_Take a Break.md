---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Take a Break (move)"
PageType: Move
PageCategory: Session
PageOrder: 4

## Oracle
MoveName: "Take a Break"
InlineCmd: TAB
Trigger: "When you resolve a progress move or complete an intense scenario"
RollType: None
ReferencedMoves: 
  - [[MV_End a Session]]
---
# [[_Moves Index|Moves]] - [[_Session Moves|Session]]: Take a Break

## Take A Break: Move Card
>[!abstract]  Trigger and Preparation
>**When you resolve a progress move or complete an intense scenario**, take a few deep breaths and take some time to attend to the needs of your body. Reflect on what just happened and how it made you feel. ^trigger

> [!question] After you Take a Break
> Choose one of the following
>1. Move on: Continue the session. You or an ally may add +1 on the next move (not a progress move), bolstered by your reflection and past experiences.
>2. Stop for now: [[MV_End a Session|End a Session]] ^action

## Full Description
Use this move to introduce a point in the game flow where you pause and reflect on the events of the story. When gameplay gets immersive or intense, it can be easy to ignore physical cues like hunger, fatigue, or muscle stiffness. Also, if the pace is moving quickly, you might not have time to process your feelings about what just happened. 

This move triggers after you resolve any progress move, hit or miss. This can include progress moves for quests, connections, expeditions, and combat. Ideally, this triggers at least once for any significant session of play. Even if the resolution of this particular challenge is not noteworthy or you feel it doesn’t require much reflection, the break is an opportunity to get a glass of water, go to the bathroom, or even just check your posture before moving on. 

The second trigger for this move is intentionally flexible to fit the needs of each player, and allow them to define what level of intensity would require the need to stop and take a break. This move can and should be triggered by anyone who feels they need it. 


> [!cite]- Example Usage
> It has just been revealed that a connection you trusted to guide you safely through a perilous asteroid field was an enemy spy, leading you into an ambush where you suffer heavy losses. At the end of the scene, you Take a Break, stopping to stretch and reflect on how you feel about the betrayal and the ensuing battle. You decide you need some time to think about what to do going forward, so you [[MV_End a Session|End a Session]] for the day.

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
| **[[MV_Change Your Fate\|Change Your Fate (move)]]** | #Pedia/Moves/Session | **[[MV_End a Session\|End a Session (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>