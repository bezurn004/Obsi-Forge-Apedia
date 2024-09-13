---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Begin the Scene (SF Moves)"
PageType: Move
PageCategory: "Scene Challenge"
PageOrder: 0

## Move
MoveName: "Begin the Scene"
InlineCMD:
Trigger: "When you face an extended or complex challenge"
RollType: None
ReferencedMoves: 
  - [[SF_CH3_Face Danger]]
  - [[SF_CH3_Secure an Advantage]]
  - [[SF_CH3_Aid Your Ally]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Scene Moves|Scene Challenge]]: Begin the scene
## Begin The Scene: Move Card
>[!abstract]  Trigger and Preparation
>**When you face an extended or complex challenge...**
>
>Creating a scene challenge
>Name your objective and choose a rank as appropriate to the situation. 
>- You have a clear advantage: Troublesome 
>- You are ready to act: Dangerous 
>- You are unprepared or outmatched: Formidable 
>
>Then, activate a 4-segment tension clock and [[SF_CH3_Face Danger|Face Danger]] or [[SF_CH3_Secure an Advantage|Secure an Advantage]] to take action. ^trigger

> [!tip] Group play
> The scene challenge progress track and tension clock are shared with your allies. Guided by the fiction, move the focus among the characters. Any allies involved in the scene can make the [[SF_CH3_Face Danger|Face Danger]] or [[SF_CH3_Secure an Advantage|Secure an Advantage]]. Any character can also [[SF_CH3_Aid Your Ally|Aid Your Ally]] to contribute to a move another character is about to make. ^group-play

## Full Description
A scene challenge is an optional structured approach for resolving an extended non-combat scene against a threat or other characters, particularly when a time limit or looming danger adds extra urgency. Examples of a scene challenge include disarming a timed explosive, hacking a system while evading digital countermeasures, participating in a formal debate, or competing in a hoverbike race. 

To start a scene challenge, make the Begin the Scene move. As part of this move, you’ll create a standard progress track (troublesome, dangerous, or formidable) to measure your headway towards an objective. You’ll also set a tension clock of four segments to represent the gains made by your opponents or the advancement of a looming threat or deadline.

When choosing the rank of the objective, consider the scope of the situation and your level of readiness. If unsure, make it dangerous

*239 CLOCKS*

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
| **[[_SF_CH3_Scene Moves\|Scene Challenges (SF In Depth)]]** | #Starforged/Moves/Scene_Challenge | **[[SF_CH3_Finish the Scene\|Finish the Scene (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>