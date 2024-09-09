---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Make a Connection (SF Moves)"
PageType: Move
PageCategory: Connection
PageOrder: 1

## Move
MoveName: "Make a Connection"
InlineCmd: MAC
Trigger: "When you search out a new relationship or give focus to an existing relationship (not an ally or companion)"
RollType: Action
RollStat: Heart
ReferencedMoves: 
  - [[SF_CH3_Pay the Price]]
  - [[SF_CH3_MV_Develop a Relationship]]
  - [[SF_CH3_MV_Forge a Bond]]
---
# [[_Starforged|Starforged]] - [[_SF_CH3_Gameplay In Depth|Moves]] - [[_SF_CH3_Connection Moves|Connection]]: Make a Connection
## Make A Connection: Move Card
>[!abstract]  Trigger and Preparation
>When you search out a new relationship or give focus to an existing relationship (not an ally or companion)... ^trigger

> [!tip]- Shared Connection
> When you are playing with others players, you can all create a shared connection.  Whether through introductions or collective interactions, each of you has a link to this person. Consider how they fit into the background for your team. ^group-play

> [!warning] Action Roll
> Roll +heart ^action-roll

> [!challenge-strong] On strong hit
>  Once you successfully Make a Connection, you may thereafter add +1 and take +1 momentum on a hit if they support you as you make a move.  
> * On a hit, you establish the connection. 
> * Give them a role to represent their duty, expertise, or background [[SF_CH2_Create Local Connection#Give the Connection A Role|see details on connection Roles here]].
> * Set the connection’s rank: troublesome, dangerous, formidable, extreme, or epic.
> * Finally, make note of their name, location, and any other characteristics worth recording. You can use [[_SF_CH5_Characters|Characters Oracle]] to flesh out their look and nature.
> 
> >[!cite]- Narrative prompt
> >Envision how the connection is made and what happens next. ^strong-hit

> [!challenge-weak] On a weak hit
> As above on a strong hit
> >[!cite]- Narrative prompt
> >This connection comes with a complication or cost. Envision what they reveal or demand. ^weak-hit

> [!challenge-miss] On a miss
> You must [[SF_CH3_Pay the Price|Pay the Price]]
> >[!cite]- Narrative prompt
> >You don't make a connection and the situation worsens. ^miss

## Full Description
If you’ve established a meaningful relationship with an NPC and want to give that person an ongoing presence in your story, make this move. You can also Make a Connection with an entirely new NPC by searching them out when you’re in need of someone who fits a specific role or capability. 

The rank should be appropriate to their stature in the setting and the level of involvement you want them to have in your story:  The higher their rank, the greater the narrative focus and time required to eventually [[SF_CH3_Forge a Bond|Forge a Bound]] with them, and the greater the legacy rewards when you do so. As you interact, you can find opportunities to [[SF_CH3_Develop a Relationship|Develop a Relationship]] and eventually [[SF_CH3_Forge a Bond|Forge a Bound]] with them.

> [!cite]- Narrative Example
> You arrive at a planetside settlement in desperate need of provisioning. You want to find a merchant who can provide ongoing support at this outpost, and envision exploring the local market. You roll +heart to see if you encounter any candidates. 

*163 CONNECTION MOVES*

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
| Section Page | Tags | Next Page |
|:--- |:---:| ---:|
| **[[_SF_CH3_Connection Moves\|Connection Moves (SF)]]** | #Starforged/Moves/Connection | **[[SF_CH3_Develop a Relationship\|Develop a Relationship (SF Moves)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>