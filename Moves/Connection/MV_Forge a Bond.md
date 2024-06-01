---
Alias: "Forge a Bond (move)"
PageType: Move
PageCategory: Connection
InlineCmd: FAB
Trigger: "When your relationship with a connection is ready to evolve"
RollType: Progress
ProgressTrack: ConnectionProgress
---
# [[_Moves Index|Moves]] - [[_Connection Moves|Connection]]: Forge a Bond
## Forge A Bond: Move Card

>[!abstract]  Trigger and Preparation
> When your relationship with a connection is ready to evolve...

> [!tip]- Shared Connection
> If this is a mutual connection with allies, you share a progress track. When it is time to Forge a Bond, one of you makes the move for the group. Each of you marks the legacy reward for your character. 

> [!progress] Progress Roll
>  Roll the challenge dice and compare to your progress track for this connection.

> [!challenge-strong] On strong hit
> You now share a bond. Mark a reward on your bonds legacy track per the connection's rank: troublesome=1 tick; dangerous=2 ticks; formidable=1 box; extreme=2 boxes; epic=3 boxes. Any allies who share this connection also mark the reward. Then, choose one.
>  1. Bolster their influence: When they aid you on a move closely associated with their role, add +2 instead of +1.
>  2. Expand their influence: Give them a second role. When they aid you on a move closely associated with either role, add +1 and take +1 momentum on a hit.
> >[!quote] Narrative prompt
> >Beyond the mechanical support of the bond, consider how the evolution of the relationship impacts your future interactions. What new responsibilities or opportunities does it introduce? 

> [!challenge-weak] On a weak hit
> As on a strong hit, but not without complication. To gain the bond and the legacy reward, decide if the connection requires a small favor, or a new quest.  If the latter, [[MV_Swear an Iron Vow|Swear an Iron Vow (move)]] and see it done.
> >[!quote] Narrative prompt
> >Envision the nature of their request to complete the bond for the connection.

> [!challenge-miss] On a miss
>  Your personalities, goals, or objectives are at odds. If you recommit to this relationship do the following.
>  1. Roll both challenge dice, take the lowest value, and clear that number of progress boxes.
>  2. Raise the connection's rank by one (if not already epic).
> >[!quote] Narrative prompt
> >They reveal a motivation or background that puts you at odds. How has the relationship taken a turn that tests your resolve?
> >If the circumstances are not in favor with retaining the relationship, then lose this connection.

## Full Description
A bond represents a deeper, more meaningful relationship with a connection. Building a bond reinforces your commitment, bolsters the connection’s aid, and provides experience through legacy rewards. When you have accrued progress on a connection’s progress track and are ready to take the relationship to the next level, make this move. 

Since this is a [[GP_Tracks#Progress Moves|Progress Move]], tally the number of filled boxes on your progress track for the connection. This is your progress score. Only add fully filled boxes (those with four ticks). Then, roll your challenge dice, compare to the progress score, and resolve a strong hit, weak hit, or miss as normal. You may not burn momentum, and you are not affected by negative momentum.

In the fiction of your story, forging a bond can be ceremonial. Perhaps you exchange gifts or share a promise. If so, envision what you do or say. This will add color and texture to the setting, and give the moment proper weight. Otherwise, the bond is a new phase that you (the player) are aware of, but is not formally recognized by the characters.

When you Forge a Bond and score a strong hit, you now share a bond. Mark progress on your bonds legacy track per the rank of the connection. Then, choose whether they are made more helpful under their existing role, or if they gain a new role. 

On a weak hit, they ask more of you. It might be a task, an item, a concession, or even a vow. Envision what they need or [[MV_Ask the Oracle|Ask the Oracle]] for insight. If you agree, gain the bond. If you refuse or fail to complete the request, the connection is not necessarily lost (although you may need to [[MV_Test Your Relationship|Test Your Relationship]]), but you cannot attempt to Forge a Bond again unless those circumstances change. 

On a miss, things are not as they seemed. The connection reveals something that fundamentally undermines or alters your relationship. Have they kept important information from you? Do they have an ulterior motive? Do you discover their ties to an enemy or rival? If you choose to maintain the relationship, you face a setback and must rebuild on these new terms. If there is no coming back after this revelation, simply clear the connection and envision how you move forward.

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