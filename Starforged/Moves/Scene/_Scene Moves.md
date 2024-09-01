---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Scene Challenge Moves"
PageType: ["Move Index", "Gameplay in Depth"]
PageCategory: "Scene Challanges"
PageOrder: 13
---
# [[_Moves Index|Moves]] Summary: Scene Challenge
A ==scene challenge== is an optional structured approach for resolving an extended non-combat scene against a threat or other characters, particularly when a time limit or looming danger adds extra urgency. Examples of a scene challenge include disarming a timed explosive, hacking a system while evading digital countermeasures, participating in a formal debate, or competing in a hoverbike race. 

To start a scene challenge, make the [[MV_Begin the Scene|Begin the Scene]]. As part of this move, you’ll create a standard progress track (troublesome, dangerous, or formidable) to measure your headway towards an objective. You’ll also set a tension clock of four segments to represent the gains made by your opponents or the advancement of a looming threat or deadline.

> [!example]- Begin the Scene Move
> ![[MV_Begin the Scene#Begin The Scene Move Card]]

When choosing the rank of the objective, consider the scope of the situation and your level of readiness. If unsure, make it dangerous.

```dataview
TABLE without ID
	link(file.link, MoveName) As "Move Name",
	InlineCmd As "Inline Command",
	RollType As "Roll Type"
WHERE contains(PageType, "Move") & contains(PageCategory, "Scene Challenge") & !contains(PageType, "Index")
SORT PageOrder, asc
```

## Make your moves
Once the scene is underway, [[MV_Face Danger|Face Danger]] or [[MV_Secure an Advantage|Secure an Advantage]] to take action. Scene challenges use a variation of these moves, %% #addition Explain why moves are consolidated%% _but these variations are integrated into the normal moves to avoid duplication of names and content._

The choice between the two moves is a narrative and mechanical decision. [[MV_Face Danger|Face Danger]] is reactive, used to avoid threats or overcome obstacles. [[MV_Secure an Advantage|Secure an Advantage]] is proactive for when you are using resources, abilities, or expertise to prepare or gain leverage. But there will be situations where either move is valid. In that case, consider your intended result. [[MV_Face Danger|Face Danger]] is focused on building progress and pushing the scene to a conclusion, while [[MV_Secure an Advantage|Secure an Advantage]] builds momentum and extends the scene. [[MV_Face Danger|Face Danger]] is riskier, since a weak hit means dialing up the tension by filling a clock segment.

Even if you take an action that would trigger another move, resolve that action using these versions of [[MV_Face Danger|Face Danger]] or Secure an Advantage. For example, if you are participating in a debate, do not make the Compel move to convince the audience of your argument. Instead, [[MV_Face Danger|Face Danger]] or [[MV_Secure an Advantage|Secure an Advantage]] with a stat appropriate to your approach.

## Working with allies
The scene challenge progress track and tension clock are shared with your allies. Guided by the fiction, move the focus among the characters. Any allies involved in the scene can make the [[MV_Face Danger|Face Danger]] or [[MV_Secure an Advantage|Secure an Advantage]]. Any character can also [[MV_Aid Your Ally|Aid Your Ally]] to contribute to a move another character is about to make.

## Ending the scene Challenge
Continue to [[MV_Face Danger|Face Danger]] and [[MV_Secure an Advantage|Secure an Advantage]] as appropriate to your approach. Apply the outcome of each move to the current situation and envision how you take action or what happens next. 

When the tension clock is filled, time is up. You must [[MV_Finish the Scene|Finish the Scene]] by making a progress roll against your objective. You will also [[MV_Finish the Scene|Finish the Scene]] when the progress track is filled, or if the narrative and your accumulated progress is guiding the challenge to a conclusion.

> [!example]- Finish the Scene Move
> ![[MV_Finish the Scene#Finish The Scene Move Card]] 

## Mass combat using a scene challange
Scene challenges are intended for use in non-combat conflicts. But what if you find yourself in command of a large force of NPCs? You can use a scene challenge to resolve the clash of mighty armies and fleets. When you [[MV_Begin the Scene|Begin the Scene]], envision the nature of the battle and consider the makeup of the opposing forces. Based on that starting situation, set the challenge rank.

- You have superior numbers, position, or firepower: Troublesome 
- Neither side has a clear advantage: Dangerous 
- You are facing a superior force or are badly positioned: Formidable 

Then, envision your approach as you lead your force into battle. [[MV_Face Danger|Face Danger]] or [[MV_Secure an Advantage|Secure an Advantage]] as appropriate, choosing a stat that represents the current situation and your tactics. Resolve the outcome of each move and mark the progress track and clock as normal.

During the battle, you and your allies may [[MV_Enter the Fray|Enter The Fray]] to zoom in and give focus to a fight against an important foe or key objective. Use the combat moves to resolve your objective in that fight. If you are successful, mark progress on your scene challenge progress track. If you lose the fight, fill a segment on the tension clock. 

When you [[MV_Finish the Scene|Finish the Scene]] to end the battle, envision the extent of your victory or cost of your defeat.

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[GID_Clocks\|Clocks (guidelines)]]** | #Pedia/Moves/Scene_Challenge | **[[GID_Allies_Conflict\|Conflict Between Allies (guidelines)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>