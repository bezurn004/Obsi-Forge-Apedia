---
Name: "Set a Flag"
PageType: Move
PageCategory: Session
InlineCmd: SAF
RollType: None
Trigger: [""] 
Stats: []
---
# [[_Moves Index|Moves]: Set a Flag
### Categories: [[_Session Moves|Session Moves]]
>[!abstract]  Context and Preparation
>**When you identify situations or topics you don’t want to include, don’t want to envision in detail, or otherwise may need mindfulness when approaching**, that content is now flagged.

>[!tip] Usage Notes
>While Set a Flag is usually used when starting a new campaign or when you Begin a Session, you can also flag content in the middle of a session. Once content has been flagged, it should remain flagged for every session going forward.

## Full Description
When you establish content boundaries for everyone at the table or create mindfulness for what content is included in your game, make this move. 

Set a Flag allows you to define expectations for what content can appear in your story. You can flag content that you don’t want to include at all, content that you might be okay with including “off-screen,” or content that warrants a check-in before it is included. 

Whether you have personal comfort levels on what you want to explore in a game, or you want to be consistent with the campaign truths, there are many reasons why you may want to Set a Flag for certain subject matter, events, and actions. By identifying that content you don’t want to include in the game, you can dive deeper into all the other possibilities that are still on the table. 


## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, title) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags

#Pedia/Moves/Session 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>