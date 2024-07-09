---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Read Heart (move)"
PageType: Move
PageCategory: Asset
PageOrder: 

## Move
MoveName: "Read Heart"
RollType: Action
RollStat: Heart
Trigger: ["When you read the intent, emotions, or memories of a nearby being"]
AssetPage: AST_Empath
AssociatedAsset: EMPATH
AssociatedAssetAbility: "Ability 1"
ReferencedMoves: 
  - [[MV_Pay the Price]]
---
# [[_Moves Index|Moves]] - [[_Asset Moves|Asset]]: Read Heart
## Read Heart: Move Card
>[!abstract]  Trigger and Preparation
>This move is enabled by the [[AST_Empath|EMPATH]].
>**When you read the intent, emotions, or memories of a nearby being...** ^trigger

> [!warning] Action Roll
> Roll +heart ^action-roll

> [!challenge-strong] On strong hit
>  - Take +2 momentum
>  - Add +1 when you make moves to interact with them in this scene.
> > [!cite]- Narrative prompt
> > You glimpse a helpful aspect of their inner self. Envision what you learn. ^strong-hit

> [!challenge-weak] On a weak hit
> Take +1 momentum
> > [!cite]- Narrative prompt 
> > The visions are murky ^weak-hit

> [!challenge-miss] On a miss
> You must [[MV_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > You reveal a troubling motive or secret. ^miss

## Full Description
When you read the intent, emotions, or memories of a nearby being, roll +heart. 

On a strong hit, you glimpse a helpful aspect of their inner self. Envision what you learn, take +2 momentum, and add +1 when you make moves to interact with them in this scene. 

On a weak hit, the visions are murky; take +1 momentum. 

On a miss, you reveal a troubling motive or secret; [[MV_Pay the Price|Pay the Price]]

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
| **[[MV_Raise Shields\|Raise Shields (move)]]** | #Pedia/Moves/Asset | **[[MV_Ready Grappler\|Ready Grappler (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>

