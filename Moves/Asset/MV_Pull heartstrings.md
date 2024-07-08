---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Pull heartstrings (move)"
PageType: Move
PageCategory: Asset
RollType: Action
RollStat: Heart
Trigger: [""]
AssociatedAsset: "Empath"
AssociatedAssetAbility: "Ability 2"
ReferencedMoves: 
  - INSERT
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Pull heartstrings

## Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Empath|EMPATH]].
>When you read the intent, emotions, or memories of a nearby being...

> [!warning] Action Roll
> Roll +heart

> [!challenge-strong] On strong hit
>  - Take +3 momentum
>  - Add +1 when you make moves to interact with them in this scene.
>  - If in an encounter, mark progress
>  
> > [!cite]- Narrative prompt
> > You glimpse a helpful aspect of their inner self. Envision what you learn.
> > You may also subtly influence their attitude or actions, such as making a hostile being hesitate. 

> [!challenge-weak] On a weak hit
> - Take +2 momentum
> - If in an encounter, mark progress
> 
> > [!cite]- Narrative prompt 
> > The visions are murky.
> > You may subtly influence their attitude or actions, such as making a hostile being hesitate. 

> [!challenge-miss] On a miss
> You must [[MV_Pay the Price|Pay the Price (move)]]
> 
> > [!cite]- Narrative prompt
> > You reveal a troubling motive or secret.

## Full Description
When you read the intent, emotions, or memories of a nearby being, roll +heart. 

On a strong hit, you glimpse a helpful aspect of their inner self. Envision what you learn, take +3 momentum, and add +1 when you make moves to interact with them in this scene. You may subtly influence their attitude or actions, such as making a hostile being hesitate.

On a weak hit, the visions are murky; take +2 momentum. You may subtly influence their attitude or actions, such as making a hostile being hesitate. 

On a miss, you reveal a troubling motive or secret; [[MV_Pay the Price|Pay the Price (move)]]

## Related Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index") & !contains(PageCategory, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
| Previous Page | Tags | Next Page |
|:--- |:---:| ---:|
| **LINK** |  | **LINK** |

#Pedia/Moves/Asset 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>

