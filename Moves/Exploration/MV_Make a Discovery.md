---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Make a Discovery (move)"
PageType: Move
PageCategory: Exploration
PageOrder: 3

## Oracle
MoveName: "Make a Discovery"
InlineCmd: MAD
Trigger: "When your exploration of a waypoint uncovers something wondrous"
RollType: Oracle
RollTable: Oracle/MakeDiscovery
ReferencedMoves: 
  - [[MV_Explore a Waypoint]]
---
# [[_Moves Index|Moves]] - [[_Exploration Moves|Exploration]]:  Make a Discovery
## Make A Discovery: Move Card
>[!abstract]  Trigger and Preparation
>When your exploration of a waypoint uncovers something wondrous.  
>This move can only be made after rolling a **Match on a Strong Hit** on the move [[MV_Explore a Waypoint|Explore a Waypoint]]... ^trigger

> [!oracle] Create a positive encounter
> 1. Roll or choose one from the table below
> 2. Envision its nature and interact with how it relates to the setting
> 3. You and your allies mark +2 ticks on your discoveries legacy track
> > ![[#^table-make-a-discovery]]
>
> >[!cite]- Narrative
> Envision how this discovery deepen your understanding of the setting, introduce revelations that may contradict accepted truths, or reveal a rare and valuable treasure. ^oracle-roll

## Full Description
You may make this move only when you [[MV_Explore a Waypoint|Explore a Waypoint]] and roll a strong hit with a match. This represents uncovering something extraordinary, the nature of which you’ll define by choosing or rolling on the table. This is a dramatic, rare event, worthy of focus in your story. Take a moment to envision the result or talk it through with others at your table. The discovery should deepen your understanding of the setting, introduce revelations that may contradict accepted truths, or reveal a rare and valuable treasure. 

Once you’ve established the nature of the discovery and interacted with it in the fiction, you and your allies may mark two ticks on your ==discoveries legacy track==.

### Make a Discovery Table
| Roll | Result |
| --- | --- |
| 1-4 | Advanced technology waiting to be harnessed or salvaged |
| 5-8 | Ancient archive or message |
| 9-10 | Artificial consciousness evolved to a higher state |
| 11-12 | Clues to a crucial resource or uncharted domain |
| 13-14 | Envoy from another time or reality |
| 15-22 | Extraordinary natural phenomenon |
| 23-24 | First contact with intelligent life |
| 25-26 | Gateway to another time or alternate reality |
| 27-28 | Key to unlocking a language or method of communication |
| 29-34 | Lost or hidden people |
| 35-42 | Majestic or unusual lifeforms |
| 43-46 | Marvel of ancient engineering |
| 47-50 | Miraculously preserved artifact or specimen |
| 51-56 | Monumental architecture or artistry of an ancient civilization |
| 57-62 | Mysterious device or artifact of potential value |
| 63-66 | New understanding of an enduring mystery |
| 67-68 | Pathway or means of travel to a distant location |
| 69-70 | Person or lifeform with phenomenal abilities |
| 71-78 | Place of awe-inspiring beauty |
| 79-86 | Rare and valuable resource |
| 87-88 | Safeguarded or idyllic location |
| 89-90 | Visions or prophesies of the future |
| 91-100 | Roll twice |
^table-make-a-discovery

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
| **[[MV_Explore a Waypoint\|Explore a Waypoint (move)]]** | #Pedia/Moves/Exploration | **[[MV_Confront Chaos\|Confront Chaos (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>