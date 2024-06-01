---
Alias: "Make a Connection (move)"
PageType: Move
PageCategory: Connection
InlineCmd: MAC
Trigger: "When you search out a new relationship or give focus to an existing relationship (not an ally or companion)"
RollType: Action
RollStat: Heart
---
# [[_Moves Index|Moves]] - [[_Connection Moves|Connection]]: Make a Connection

## Make A Connection: Move Card
>[!abstract]  Trigger and Preparation
>When you search out a new relationship or give focus to an existing relationship (not an ally or companion)...

> [!tip]- Shared Connection
> When you are playing with others players, you can all create a shared connection.  Whether through introductions or collective interactions, each of you has a link to this person. Consider how they fit into the background for your team.

> [!warning] Action Roll
> Roll +heart

> [!challenge-strong] On strong hit
>  Once you successfully Make a Connection, you may thereafter add +1 and take +1 momentum on a hit if they support you as you make a move.  
> * On a hit, you establish the connection. 
> * Give them a role to represent their duty, expertise, or background [[CSG_Create Local Connection#Give the Connection A Role|see details on connection Roles here]].
> * Set the connection’s rank: troublesome, dangerous, formidable, extreme, or epic.
> * Finally, make note of their name, location, and any other characteristics worth recording. You can use [[_OCL_Characters|Characters Oracle]] to flesh out their look and nature.
> 
> >[!quote] Narrative prompt
> >Envision how the connection is made and what happens next.

> [!challenge-weak] On a weak hit
> As above on a strong hit
> >[!quote] Narrative prompt
> >This connection comes with a complication or cost. Envision what they reveal or demand.

> [!challenge-miss] On a miss
> You must [[MV_Pay the Price|Pay the Price]]
> >[!quote] Narrative prompt
> >You don't make a connection and the situation worsens.

## Full Description
If you’ve established a meaningful relationship with an NPC and want to give that person an ongoing presence in your story, make this move. You can also Make a Connection with an entirely new NPC by searching them out when you’re in need of someone who fits a specific role or capability. 

The rank should be appropriate to their stature in the setting and the level of involvement you want them to have in your story:  The higher their rank, the greater the narrative focus and time required to eventually [[MV_Forge a Bond|Forge a Bound]] with them, and the greater the legacy rewards when you do so. As you interact, you can find opportunities to [[MV_Develop a Relationship|Develop a Relationship]] and eventually [[MV_Forge a Bond|Forge a Bound]] with them.

> [!quote]- Narrative Example
> You arrive at a planetside settlement in desperate need of provisioning. You want to find a merchant who can provide ongoing support at this outpost, and envision exploring the local market. You roll +heart to see if you encounter any candidates. 

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

#Pedia/Moves/Connection 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>