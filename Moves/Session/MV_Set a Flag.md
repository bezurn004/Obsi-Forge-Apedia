---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Set a Flag (move)"
PageType: Move
PageCategory: Session
PageOrder: 2

## Oracle
MoveName: "Set a Flag"
InlineCmd: SAF
Trigger: "When you identify situations or topics you don’t want to include, don’t want to envision in detail, or otherwise may need mindfulness when approaching"
RollType: None
ReferencedMoves: 
  - [[MV_Change Your Fate]]
  - [[MV_Begin a Session]]
---
# [[_Moves Index|Moves]] - [[_Session Moves|Session]]: Set a Flag

## Set A Flag: Move Card
>[!abstract]  Trigger and Preparation
>**When you identify situations or topics you don’t want to include, don’t want to envision in detail, or otherwise may need mindfulness when approaching**, that content is now flagged. ^trigger

> [!question] Action
> When you encounter content flagged as something to approach mindfully, pause to consider or discuss its role in your story. When you come across flagged content that you would rather adjust or omit, [[MV_Change Your Fate|Change Your Fate]] ^action

## Full Description
When you establish content boundaries for everyone at the table or create mindfulness for what content is included in your game, make this move. 

Set a Flag allows you to define expectations for what content can appear in your story. You can flag content that you don’t want to include at all, content that you might be okay with including “off-screen,” or content that warrants a check-in before it is included. 

Whether you have personal comfort levels on what you want to explore in a game, or you want to be consistent with the campaign truths, there are many reasons why you may want to Set a Flag for certain subject matter, events, and actions. By identifying that content you don’t want to include in the game, you can dive deeper into all the other possibilities that are still on the table.

>While Set a Flag is usually used when starting a new campaign or when you [[MV_Begin a Session|Begin a Session]], you can also flag content in the middle of a session. Once content has been flagged, it should remain flagged for every session going forward.


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
| **[[MV_Begin a Session\|Begin a Session (move)]]** | #Pedia/Moves/Session | **[[MV_Change Your Fate\|Change Your Fate (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>