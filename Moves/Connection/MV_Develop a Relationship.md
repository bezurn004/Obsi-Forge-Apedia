---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Develop a Relationship (move)"
PageType: Move
PageCategory: Connection
PageOrder: 2

## Oracle
MoveName: Develop a Relationship
InlineCmd: DYR
Trigger: "When you reinforce your relationship with a connection by doing one of the following"
Approach: 
- "Swearing a vow to undertake a perilous quesst in their service: Swear an Iron Vow"
- "Completing a quest to their benefit: Fullfill Your Vow"
- "Leveraging their help in desperate circumstances: Compel"
- "Giving them something of worth: Sacrifice Resources"
- "Sharing a profound moment:Hearten or Sojourn"
- "Standing with them against hardship: End the Scene or Take Decisive Action"
- "Overcoming a test of your relationship: Test Your Relationship"
RollPreReq: Bonded
RollType: ["None","Action"]
RollStat: ConnectionRank
ReferencedMoves: 
  - [[MV_Swear an Iron Vow]]
  - [[MV_Fullfill Your Vow]]
  - [[MV_Compel]]
  - [[MV_Sacrifice Resources]]
  - [[MV_Hearten]]
  - [[MV_Face Danger]]
  - [[MV_Take Decisive Action]]
  - [[MV_Test Your Relationship]]
---
# [[_Moves Index|Moves]] - [[_Connection Moves|Connection]]: Develop a Relationship
## Develop A Relationship: Move Card
>[!abstract]  Trigger and Preparation
>**When you reinforce your relationship with a connection** by doing any of the following...
> - swearing a vow to undertake a perilous quest in their service *[[MV_Swear an Iron Vow|Swear an Iron Vow]]*
 >- completing a quest to their benefit *[[MV_Fullfill Your Vow|Fullfill Your Vow]]*
 >- leveraging their help in desperate circumstances *[[MV_Compel|Compel]]*
 >- giving them something of worth *[[MV_Sacrifice Resources|Sacrafice Resources]]*
 >- sharing a profound moment *[[MV_Hearten|Hearten]] or [[MV_Sojourn|Sojourn]]*
 >- standing with them against hardship * [[MV_Face Danger|Face Danger]] or [[MV_Take Decisive Action|Take Decisive Action]]*
 >- overcoming a test of your relationship *[[MV_Test Your Relationship|Test Your Relationship]]*
 > 
 > ...you may mark progress per the rank of the connection. ^trigger

> [!success] Bonded Connection
> If you already share a bond with a connection, you no longer have a progress track associated with them. Instead of marking progress, make an action roll using the connection’s rank. A success on this roll offers immediate benefits, including legacy rewards on a strong hit. This is your incentive to nurture a relationship even after you [[MV_Forge a Bond|Forge a Bound]]. ^bond-connection

> [!warning] Action Roll
> The action roll is only made when the Connection has been Bonded.
> Roll + Connection Rank ^action-roll

> [!challenge-strong] On strong hit
> Mark 2 ticks on your bonds legacy track.
> On a **strong hit with a match**, Raise their rank +1 (if not already epic).
> >[!cite]- Narrative prompt
> >On a match, you may also envision how recent events bolstered your connection’s standing ^strong-hit

> [!challenge-weak] On a weak hit
> Take +2 Momentum ^weak-hit

> [!challenge-miss] On a miss
> Take no lasting benefit.
> >[!cite]- Narrative prompt
> >There are no consequences for a failure, other than the lost opportunity to increase standing with the connection. ^miss

## Full Description
When you build influence with a connection through a significant interaction, event, or deed, make this move.

There are several triggers to help define the bounds of what it means to evolve your relationship. But the pace is largely under your control. It’s a big galaxy, so any meaningful interaction with a connection is likely an opportunity to Develop a Relationship]]. 

Unbonded connections are managed through [[GB_Progress Tracks#Progress Tracks|progress tracks]]. When you make this move, mark progress on the connection’s progress track per their rank. Eventually, you can [[MV_Forge a Bond|Forge a Bound]] and make a progress roll against this progress track. 

> [!cite]- Narrative example
> You deliver a precursor artifact to one of your connections, a researcher studying alien technology. This unique gift enables you to Develop Your Relationship. 

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
| **[[MV_Make a Connection\|Make a Connection (move)]]** | #Pedia/Moves/Connection | **[[MV_Test Your Relationship\|Test Your Relationship (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>