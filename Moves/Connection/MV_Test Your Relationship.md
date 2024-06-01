---
Alias: "Test Your Relationship (move)"
PageType: Move
PageCategory: Connection
InlineCmd: TYR
Trigger: "When your relationship with a connection is tested through conflict, betrayal, or circumstance"
RollType: Action
RollStat: Heart
---
# [[_Moves Index|Moves]] - [[_Connection Moves|Connection]]: Test Your Relationship

## Test Your Relationship: Move Card
>[!abstract]  Trigger and Preparation
>When your relationship with a connection is tested through conflict, betrayal, or circumstance...

> [!error]- Distant Connections
> If an incident forces this test, but you aren’t in a position to resolve it, make a note. Then, make this move when you next come in contact. If extended time passes without making the test, it may be appropriate to simply clear the connection and be done with it.

> [!warning] Action Roll
> Roll + heart. If you share a Bond, add +1

> [!challenge-strong] On strong hit
> [[MV_Develop a Relationship|Develop a Relationship]]
> >[!quote] Narrative prompt
> >In spite of everything, this test strengthens your relationship. Envision how you emerge from the trial with a renewed pact, respect, or rapport. 

> [!challenge-weak] On a weak hit
> [[MV_Develop a Relationship]]
> >[!quote] Narrative prompt
> >The relationship evolves, but you must deal with an ongoing complication or concession. Things may remain fraught or tense. 

> [!challenge-miss] On a miss
> Or if you have no interest in maintaining this relationship, choose one.
> 1. Lose the connection: Envision how this impacts you and [[MV_Pay the Price|Pay the Price]].
> 2. Prove your loyalty: [[MV_Swear an Iron Vow|Swear an Iron Vow]] (formidable or greater) to see it done. Until you complete the quest, take no benefit for the connection.
> >[!quote] Narrative prompt
> >Envision what you offer or what they demand
> >If you refuse or fail the quest, the connection is permanently undone.

## Full Description
The paths you pursue or events in your story may force a reckoning for your relationships. How strong is the commitment? If you try to maintain this connection, at what cost? When you act against a connection, face a significant disagreement or misunderstanding, or refuse or fail a crucial assignment, make this move to see what becomes of the relationship. 

> [!quote]- Narrative Example
> After learning the true identity of your target, you renounce a bounty contract. Now, you must face your patron, the head of a powerful hunter’s guild. You envision how you make your case, then Test Your Relationship to learn their response. 

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