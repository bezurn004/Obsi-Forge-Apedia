---
Alias: "Face Desolution (move)"
PageType: Move
PageCategory: Threshold
InlineCmd: FDESOLATION
Trigger: "When you are brought to the brink of desolation"
RollType: Action
RollStat: Heart
---
# [[_Moves Index|Moves]] - [[_Threshold Moves|Threshold]]: Face Desolution

## Face Desolution: Move Card
>[!abstract]  Trigger and Preparation
>When you are brought to the brink of desolation...

> [!error]- Madness is not the end
> If this is the end of your character’s story, you can [[MV_Continue a Legacy|Continue a Legacy]] to carry on with a new character in the same setting.

> [!warning] Action Roll
> Roll +heart

> [!challenge-strong] On strong hit
>  You resist and press on
> > [!quote] Narrative prompt
> > Envision how you are able to steel yourself away from the brink of madness or despair.

> [!challenge-weak] On a weak hit
> Choose one:
>- Your spirit breaks, but not before you make a noble sacrifice. Envision your final moments.
>- You see a vision of a dreaded event coming to pass. Envision that dark future, and [[MV_Swear an Iron Vow|Swear an Iron Vow]] to prevent it through an extreme quest. 
>- You return to your senses and must mark [[GP_Impacts#Burdens|tormented]]. 
>- When you [[MV_Fullfill Your Vow|Fullfill Your Vow]] to complete the soul-bound quest, clear the impact.
> > [!quote] Narrative prompt
> > 
> > If instead you see a vision, what quest will prevent this from coming to pass?

> [!challenge-miss] On a miss
> You succumb to despair or horror and are lost.
> > [!quote] Narrative prompt
> > Envision how you succumb to madness or despair.

## Full Description
Make this move when prompted by another move such as [[MV_Endure Harm|Endure Harm]]. You are at the breaking point for your character. Do you push on in spite of all you have experienced, all you have done, or do you surrender to hopelessness or darkness? Roll to find out. 

On a strong hit, you come to your senses or find renewed hope. 

On a weak hit, you must make a choice. Will you make a final, heroic stand before leaving your life as Ironsworn behind? Or will you find meaning in a soul-bound quest? If you take the quest, envision a prophetic and fearful dream or vision. Then, [[MV_Swear an Iron Vow|Swear an Iron Vow]] and mark the  [[GP_Impacts#Burdens|tormented impact]]. This impact can only be cleared if you successfully [[MV_Fullfill Your Vow|Fullfill Your Vow]] to see the dreaded future undone. 

On a miss, you are broken. Your time as Ironsworn is done. If this is the end of your character’s story, you can [[MV_Continue a Legacy|Continue a Legacy]] to carry on with a new character in the same setting.

> [!quote]- Narrative example
> You are on an expedition deep in the bowels of a precursor vault. When you [[MV_Undertake an Expedition|Undertake an Expedition]] and roll a miss, you envision yourself lost in the vast labyrinthine passages. You hear the whirring and humming of ancient mechanical guardians closing in around you. It is too much to bear. You [[MV_Endure Stress|Endure Stress]], reduce your spirit to 0, roll a miss, and trigger the Face Desolation move. The next roll will decide your fate… 

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