---
Name: "Develop a Relationship"
PageType: Move
PageCategory: Connection
InlineCmd: DYR
RollPreReq: Bonded
RollType: Action
RollStat: ConnectionRank
---
# [[_Moves Index|Moves]]: Develop a Relationship
### Categories: [[_Connection Moves|Connection Moves]]
>[!abstract]  Context and Preparation
>**When you reinforce your relationship with a connection** by doing any of the following...
> - swearing a vow to undertake a perilous quest in their service *[[Swear an Iron Vow]]*
 >-  completing a quest to their benefit *[[Fullfill Your Vow]]*
 >- leveraging their help in desperate circumstances *[Compel](z_Obsi-Forge-Apedia/Moves/Adventure/Compel.md)*
 >- giving them something of worth *[[Sacrifice Resources]]*
 >- sharing a profound moment *[Hearten](z_Obsi-Forge-Apedia/Moves/Recover/Hearten.md) or [Sojourn](z_Obsi-Forge-Apedia/Moves/Recover/Sojourn.md)*
 >- standing with them against hardship *[[Face Danger]] or [[Take Decisive Action]]*
 >- overcoming a test of your relationship *[[Test Your Relationship]]*
 > 
 > ...you may mark progress per the rank of the connection.

> [!success] Bonded Connection
> If you already share a bond with a connection, you no longer have a progress track associated with them. Instead of marking progress, make an action roll using the connection’s rank. A success on this roll offers immediate benefits, including legacy rewards on a strong hit. This is your incentive to nurture a relationship even after you [[Forge a Bond]].

> [!warning] Action Roll
> The action roll is only made when the Connection has been Bonded.
> Roll + Connection Rank

> [!challenge-strong] On strong hit
> Mark 2 ticks on your bonds legacy track.
> On a **strong hit with a match**, Raise their rank +1 (if not already epic).
> >[!quote] Narrative prompt
> >On a match, you may also envision how recent events bolstered your connection’s standing

> [!challenge-weak] On a weak hit
> Take +2 Momentum

> [!challenge-miss] On a miss
> Take no lasting benefit.
> >[!quote] Narrative prompt
> >There are no consequences for a failure, other than the lost opportunity to increase standing with the connection.
## Full Description
When you build influence with a connection through a significant interaction, event, or deed, make this move.

There are several triggers to help define the bounds of what it means to evolve your relationship. But the pace is largely under your control. It’s a big galaxy, so any meaningful interaction with a connection is likely an opportunity to [[Develop a Relationship]]. 

Unbonded connections are managed through progress tracks (page 39). When you make this move, mark progress on the connection’s progress track per their rank. Eventually, you can [[Forge a Bond]] and make a progress roll against this progress track. 


> [!quote]- Narrative example
> You deliver a precursor artifact to one of your connections, a researcher studying alien technology. This unique gift enables you to Develop Your Relationship. 

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
#Pedia/Moves/Connection

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>