---
Alias: "Finish the Scene (move)"
PageType: Move
PageCategory: "Scene Challenge"
InlineCMD:
Trigger: "When the scene challenge tension clock or progress track is filled, or when events lead to the scene’s conclusion"
RollType: None
---
# [[_Moves Index|Moves]] - [[_Scene Moves|Scene Challenge]]: Finish The Scene

## Finish The Scene: Move Card
>[!abstract]  Trigger and Preparation
>When the scene challenge tension clock or progress track is filled, or when events lead to the scene’s conclusion...

> [!todo] Progress Move
> Roll the challenge dice and compare to your progress for the scene challenge.

> [!challenge-strong] On strong hit
> On a strong hit, you achieve your objective unconditionally. 
> > [!quote] Narrative prompt
> > Envision how the scene ends and what your success has achieved.

> [!challenge-weak] On a weak hit
> On a weak hit, you succeed, but not without cost. You must [[MV_Pay the Price|Pay the Price]]. Make this a minor cost relative to the scope of the scene.
> > [!quote] Narrative prompt
> > Envision how the scene ends and the minor setback faced while achieving success.

> [!challenge-miss] On a miss
> On a miss, you fail or are undermined by a dire turn of events. [[MV_Pay the Price|Pay the Price]]
> > [!quote] Narrative prompt
> > How has the scene ended with a substantial loss?

## Full Description
When the scene challenge tension clock or progress track is filled, or when events lead to the scene’s conclusion, roll the challenge dice and compare to your progress. 

On a strong hit, you achieve your objective unconditionally. 

On a weak hit, you succeed, but not without cost. You must Pay the Price. Make this a minor cost relative to the scope of the scene.

On a miss, you fail or are undermined by a dire turn of events. [[MV_Pay the Price|Pay the Price]].

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
#Pedia/Moves/Scene_Challenge 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>

