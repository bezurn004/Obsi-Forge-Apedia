---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Confront Chaos (move)"
PageType: Move
PageCategory: Exploration
PageOrder: 4

## Oracle
MoveName: "Confront Chaos"
InlineCmd: CC
Trigger: "After a Miss with a Match on the move Explore a Waypoint"
RollType: Oracle
RollTable: Oracle/ConfrontChaos
ReferencedMoves: 
  - [[MV_Explore a Waypoint]]
---
# [[_Moves Index|Moves]] - [[_Exploration Moves|Exploration]]: Confront Chaos

## Confront Chaos: Move Card
>[!abstract]  Context and Preparation
>**When your your exploration uncovers something dreadful**; after a Miss with a Match on the move [[MV_Explore a Waypoint|Explore a Waypoint]] move... ^trigger

> [!oracle] Create a negative encounter
> 1. Choose the number of aspects (1-3)
> 2. Pick or roll that number of times from the [[MV_Confront Chaos#Confront Chaos Table|Confront Chaos Oracle]]
> 3. Confront each aspect for the encounter
> 4. For each aspect of the encounter confronted, you and your allies may Mark +1 ticks on your discoveries legacy track
> > ![[#^table-confront-chaos]]
> 
> > [!cite]- Narrative prompt
> > Envision how the encounter begins and unfolds.  Will you overcome it or retreat? ^oracle-roll

## Full Description
You may make this move only after you [[MV_Explore a Waypoint|Explore a Waypoint]] and roll a **Miss with a Match**. You have stumbled across a dire discovery or inadvertently unleashed something horrific, the nature of which may have campaign shaking ramifications. 

Choose a number of aspects (one, two, or three), and pick or roll that number of times on the table. Then, envision how this threat manifests. The good news? Even chaos offers knowledge; you and your allies may mark one tick on your discoveries legacy track for each aspect you encounter.

### Confront Chaos Table

| 1d100 | Chaos Aspect |
| :---: | --- |
| 1-4 | Baneful weapon of mass destruction |
| 5-9 | Cataclysmic environmental effects |
| 10-12 | Dead given unnatural life |
| 13-17 | Destructive lifeform of monstrous proportion |
| 18-20 | Dread hallucinations or illusions |
| 21-24 | Harbingers of an imminent invasion |
| 25-27 | Horde of insatiable hunger or fury |
| 28-32 | Horrific lifeforms of inscrutable purpose |
| 33-36 | Impostors in human form |
| 37-41 | Machines made enemy |
| 42-45 | Malignant contagion or parasite |
| 46-50 | Messenger or signal with a dire warning |
| 51-53 | Passage to a grim alternate reality |
| 54-58 | People corrupted by chaos |
| 59-63 | Powerful distortions of time or space |
| 64-68 | Signs of an impending catastrophe |
| 69-72 | Site of a baffling disappearance |
| 73-77 | Site of a horrible disaster |
| 78-82 | Site of terrible carnage |
| 83-87 | Technology nullified or made unstable |
| 88-92 | Technology warped for dark purpose |
| 93-96 | Vault of dread technology or power |
| 97-100 | Worshipers of great and malevolent powers |
^table-confront-chaos

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
| **[[MV_Make a Discovery\|Make a Discovery (move)]]** | #Pedia/Moves/Exploration | **[[MV_Finish an Expedition\|Finish an Expedition (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>