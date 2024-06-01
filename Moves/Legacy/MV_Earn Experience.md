---
Alias: "Earn Experience (move)"
PageType: Move
PageCategory: Legacy
InlineCmd: EE
Trigger: "When you fill a box (four ticks) on any legacy track"
RollType: None
RollStat: None
Trigger: [""] 
---
# [[_Moves Index|Moves]] - [[_Legacy Moves|Legacy]]: Earn Experience

## Earn Experience: Move Card
>[!abstract]  Context and Preparation
>When you fill a box (four ticks) on any legacy track...

> [!tip]- Spending Experience
> You can [[MV_Advance|Advance]]. to spend your experience points when they are earned, assuming you are properly positioned in the fiction to acquire those abilities. Or save them up for future use.

> [!warning] Move Action
> Take 2 experience. This experience may be spent when you [[MV_Advance|Advance (move)]].

> [!challenge-strong] Filled Legacy Track
> Once you completely fill the tenth box on any legacy track, clear that track. You may start again marking progress on the cleared track, but earn experience at a reduced rate of 1 experience (instead of 2) for each filled progress box. 
> If you make a progress roll against this track, resolve the outcome as if at 10 progress


## Full Description
Legacy tracks (page 44) are a special type of progress track that represent the challenges you’ve overcome, along with the resources, influence, reputation, and skills you can bring to bear. 

You have three legacy tracks: quests, bonds, and discoveries. As you complete quests, form bonds, and explore the Forge, you advance along these tracks by marking ticks and filling boxes. Some asset abilities may also prompt you to mark progress on a specific legacy track, or increase the rewards for marking progress. 

Each time you fill a box completely (four ticks) on any legacy track, you make this move and gain 2 experience. That experience can then be spent on new assets or asset upgrades when you [[MV_Advance|Advance]]. See [[GP_Tracks#Gaining Experience|Gaining Experience (gameplay)]] for details on managing unspent experience using your legacy tracks. 

As noted in the move text, you begin earning reduced experience on a legacy track once you completely fill that track. In the fiction, this represents the natural diminishing returns of character experience and expertise. From a gameplay perspective, it helps keep your abilities to a manageable number. If you reach a point where your character’s ambitions and obligations are waning, [[MV_Continue a Legacy|Continue a Legacy]] to end their story.

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

#Pedia/Moves/Legacy

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>