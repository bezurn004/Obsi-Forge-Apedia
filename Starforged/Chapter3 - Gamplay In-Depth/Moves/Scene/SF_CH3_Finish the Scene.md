---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Finish the Scene (SF Moves)"
PageType: Move
PageCategory: "Scene Challenge"
PageOrder: 5

MoveName: "Finish the Scene"
InlineCMD:
Trigger: "When the scene challenge tension clock or progress track is filled, or when events lead to the scene’s conclusion"
RollType: None
ReferencedMoves: 
  - [[SF_CH3_Pay the Price]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Scene Moves|Scene Challenge]]: Finish The Scene
## Finish The Scene: Move Card
>[!abstract]  Trigger and Preparation
>**When the scene challenge tension clock or progress track is filled, or when events lead to the scene’s conclusion...** ^trigger

> [!todo] Progress Move
> Roll the challenge dice and compare to your progress for the scene challenge. ^progress-move

> [!challenge-strong] On strong hit
> On a strong hit, you achieve your objective unconditionally. 
> > [!cite]- Narrative prompt
> > Envision how the scene ends and what your success has achieved. ^strong-hit

> [!challenge-weak] On a weak hit
> On a weak hit, you succeed, but not without cost. You must [[SF_CH3_Pay the Price|Pay the Price]]. Make this a minor cost relative to the scope of the scene.
> > [!cite]- Narrative prompt
> > Envision how the scene ends and the minor setback faced while achieving success. ^weak-hit

> [!challenge-miss] On a miss
> On a miss, you fail or are undermined by a dire turn of events. [[SF_CH3_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > How has the scene ended with a substantial loss? ^miss

## Full Description
When the scene challenge tension clock or progress track is filled, or when events lead to the scene’s conclusion, roll the challenge dice and compare to your progress. 

On a strong hit, you achieve your objective unconditionally. 

On a weak hit, you succeed, but not without cost. You must Pay the Price. Make this a minor cost relative to the scope of the scene.

On a miss, you fail or are undermined by a dire turn of events. [[SF_CH3_Pay the Price|Pay the Price]].

*241 CLOCKS*

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
| Previous Page | Tags | Next Section |
|:--- |:---:| ---:|
| **[[SF_CH3_Begin the Scene\|Begin the Scene (SF Moves)]]** | #Starforged/Moves/Scene_Challenge | **[[SF_CH3_Conflict Between Allies\|Conflict Between Allies (SF In Depth)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>