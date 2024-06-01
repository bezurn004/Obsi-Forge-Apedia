---
Alias: "Face Death (move)"
PageType: Move
PageCategory: Threshold
InlineCmd: FDEATH
Trigger: ["When you encounter a situation where death is an immediate and unavoidable outcome","When you are instead brought to the brink of death with a chance for recovery or redemption"]
RollType: Action
RollStat: Heart
---
# [[_Moves Index|Moves]] - [[_Threshold Moves|Threshold]]: Face Death

## Face Death: Move Card
>[!abstract]  Trigger and Preparation
>When you encounter a situation where death is an immediate and unavoidable outcome, you are dead.
>When you are instead brought to the brink of death with a chance for recovery or redemption, make the Action Roll

> [!error]- Death is not the end
>  This is the end of your character’s story, but not their legacy. You can [[MV_Continue a Legacy|Continue a Legacy]] to learn the mark they made upon the Forge and their influence on your new character.

> [!warning] Action Roll
> Envision how you steel yourself from the beyond and roll +heart

> [!challenge-strong] On strong hit
> You are cast back into the mortal world.
> > [!quote] Narrative prompt
> > Envision what power or source has provided you another chance.

> [!challenge-weak] On a weak hit
> Choose one
>- You die, but not before making a noble sacrifice. Envision your final moments.
>- There is more to be done. Envision what is revealed or asked of you at death’s door, and [[MV_Swear an Iron Vow|Swear an Iron Vow]] to complete an extreme quest. 
>- You return to the mortal world and must mark [[GP_Impacts#Burdens|doomed]].
>- When you [[MV_Fullfill Your Vow|Fullfill Your Vow]] to complete the death-bound quest, clear the impact.
> > [!quote] Narrative prompt
> > Envision the noble deed and the end of their life. Then if you wish, [[MV_Continue a Legacy|Continue a Legacy]]
> > If this is not the end, then what quest must be seen done until the end?

> [!challenge-miss] On a miss
> You are dead
> > [!quote] Narrative prompt
> > Envision the end of your character's life.  Then if you wish, [[MV_Continue a Legacy|Continue a Legacy]]

## Full Description
Make this move when prompted by another move such as [[MV_Endure Harm|Endure Harm]] or [[MV_Withstand Damage|Withstand Damage]], or when you face a physical trauma so dire that death (or a strong chance of death) is the most likely and dramatic outcome. 

If the current situation means certain death for your character, make this move as an automatic miss. You are dead. If there is a chance to return from the brink, you should instead make an action roll. 

On a strong hit, you are alive. Consider what happens next. How did you survive? Do you return to consciousness minutes, hours, or even days later? Or was this the briefest glimpse of an averted fate? 

On a weak hit, make a choice: Is this a final, heroic sacrifice, or are you driven to accept a quest at the boundary of life and death? If you take the quest, envision how the nature of the vow is revealed through a personal epiphany or strange visitation. Then, [[MV_Swear an Iron Vow|Swear an Iron Vow]] and mark the [[GP_Impacts#Burdens|doomed impact]]. This impact can only be cleared if you successfully [[MV_Fullfill Your Vow|Fullfill Your Vow]] on the quest. 

On a miss, you are dead. This is the end of your character’s story, but not their legacy. You can [[MV_Continue a Legacy|Continue a Legacy]] to learn the mark they made upon the Forge and their influence on your new character.

> [!quote]- Narrative example
> You take a hit in a gunfight, fail to [[MV_Endure Harm|Endure Harm]] with your health at 0, and trigger the Face Death move. You envision slumping behind cover, one hand clutching your injury. Your heartbeat fades. Blackness fills your vision. You make the roll. A strong hit! A moment later, adrenaline surges and you are gasping for breath… 

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
#Pedia/Moves/Threshold

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>