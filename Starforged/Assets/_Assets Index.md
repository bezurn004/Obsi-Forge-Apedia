---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Assets"
PageType: AssetIndex
PageCategory: Index
PageOrder: 0
---

# [[_INDEX|Index]]: Assets
> **A Note about assets and progress moves**
> Some assets include abilities which might be applied to a variety of moves. This is usually phrased as “when you make a move to [blank].” However, most asset abilities apply only to action rolls. Unless an asset specifically defines a benefit for a progress move, you may not leverage an asset ability when making a progress roll.

## Asset Categories

> **[[_Companion Assets|Companion Assets]]**
> _NPC's who accompany the character._

> **[[_Deed Assets|Deed Assets]]**
> _Accomplishments or misfortunes available when the character reaches certain ranks._

> **[[_Module Assets|Module Assets]]**
> _Add-ons that can be applied to vehicles, usually only the Starship._

> **[[_Path Assets|Path Assets]]**
> _Professions or areas of study that provide abilities to the character based on their background._

> **[[_Vehicle Assets|Vehicle Assets]]**
> _Provide transportation, saftey, and abilities while undertaking explorations in the Forge._

## Asset Decks
_In the Sundered Isles guidebook, the concept of Asset decks are introduced as a way to distinguish the various abilities that would be available in a given setting.  See (cite reference] of the Sundered Isles guidebook for full details on how to use Asset decks_
> [!info]- Starforged + Sundered Isles Crossover
> These are all Starforged assets, plus those from Sundered Isles that are suitable to play within the settings for Starforged.
> > ```dataview
> TABLE without ID link(file.link, AssetName) As "Asset Name", PageCategory As "Asset Category", GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]" WHERE contains(file.tags, "#AssetDeck/Starforged") or contains(file.tags, "#AssetDeck/SI-SFCrossover") SORT PageCategory, asc & AssetName, asc
> ```


> [!info]- Sundered Isles + Starforged Crossover
> These are all Sundered Isles assets, plus those from Starforged that are suitable to play within the settings for Sundered Isles.
> ```dataview
> TABLE without ID link(file.link, AssetName) As "Asset Name", PageCategory As "Asset Category", GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]" WHERE contains(file.tags, "#AssetDeck/SunderedIsles") or contains(file.tags, "#AssetDeck/SI-SFCrossover") SORT PageCategory, asc & AssetName, asc
> ```

## All Ironsworn: Starforged Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]"
WHERE contains(PageType, "Asset") & !contains(PageType, "Index") & !contains(file.path, "Template") & contains(SourceMaterial, "Starforged")
SORT PageOrder asc
```

## All Ironsworn: Sundered Isles Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]"
WHERE contains(PageType, "Asset") & !contains(PageType, "Index") & !contains(file.path, "Template") & contains(SourceMaterial, "Sundered Isles")
SORT PageOrder asc
```


## Community Content Assets
```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Category",
	SourceMaterial As "Source",
	GameplayRole As "[[HBC_Gameplay Role|Gameplay Role]]"
WHERE contains(PageType, "Asset") & !contains(PageType, "Index") & !contains(file.path, "Template") & !contains(SourceMaterial, "Starforged") & !contains(SourceMaterial, "Sundered Isles")
SORT PageOrder asc
```

## Tags
| Previous Chapter | Tags | Next Chapter |
|:--- |:---:| ---:|
| **[[_GNPC_Foes-Encounters\|Foes and Encounters]]** | #Pedia/Assets | **[[GSRY_Definitions]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>