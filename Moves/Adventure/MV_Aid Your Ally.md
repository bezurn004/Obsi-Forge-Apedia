---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Aid Your Ally (move)"
PageType: Move
PageCategory: [Adventure, Combat, Exploration, Recover, "Scene Challenge"]
PageOrder: 5

## Move
MoveName: "Aid Your Ally"
InlineCmd: AYA
RollType: Transferal
RollStat: None
ReferencedMoves: 
  - [[MV_Gain Ground]]
  - [[MV_Secure an Advantage]]
  - [[MV_Pay the Price]]]
---
# [[_Moves Index|Moves]] | [[_Adventure Moves|Adventure]]  | [[_Combat Moves|Combat]] | [[_Exploration Moves|Exploration]] | [[_Recover Moves|Recover]] | [[_Scene Moves|Scene Challenge]]: Aid your ally
## Aid Your Ally: Move Card
>[!abstract]  Trigger and Preparation
>**When you act in direct support of an ally**, envision how you aid them. If you score a hit, they (instead of you) take the benefits of the move... ^trigger

> [!error]- Improper Usage
> Don’t ping pong this move back and forth between two characters in an attempt to build momentum. Envision what you are doing to Aid Your Ally, make the move, resolve it, and hand the reins over to your ally as they leverage the advantage. Keep it moving. Make things happen. ^improper

> [!warning] Action Roll
>- Combat:  Use the move [[MV_Gain Ground|Gain Ground]]
>- Non-Combat: Use the move [[MV_Secure an Advantage|Secure an Advantage]]

> [!challenge-strong] On a strong hit
> * **Combat:** You and your ally are both in control. And your ally gains the benefit when making the [[MV_Gain Ground|Gain Ground]].
> * **Non-Combat:** Your ally takes the mechanical and narrative benefit from the result of the [[MV_Secure an Advantage|Secure an Advantage]]. ^strong-hit

> [!challenge-weak] On a weak hit
> * **Combat:** Your ally is in control, but you are in a bad spot as you sacrifice your position for their benefit. Your ally takes the outcome from the [[MV_Gain Ground|Gain Ground]].
> * **Non-Combat:** Your ally takes the mechanical and narrative benefit when they making the [[MV_Secure an Advantage|Secure an Advantage]]. ^weak-hit

> [!challenge-miss] On a miss
> * **Combat:** If you are in a fight, both of you are now in a bad spot.  You and/or your ally takes the outcome from the [[MV_Gain Ground|Gain Ground]].
> * **Non-Combat:** One or both of you should [[MV_Pay the Price|Pay the Price]] as appropriate to the circumstances and your intent from the [[MV_Secure an Advantage|Secure an Advantage]]. ^miss

## Full Description
Make this move when you are helping an ally (a protagonist played by another player) by taking a supporting action. You might be distracting a foe in combat, using the ship’s scanners to scout the path for your pilot on an expedition, or giving an ally encouragement as you stand against a dire threat.

Outside of a fight, your effort is resolved using the Secure an Advantage, move. If you are in combat, use [[MV_Gain Ground|Gain Ground (move)]]. If you score a hit, your ally takes the mechanical and narrative benefit of your success.

In combat, this is a proactive move, made when you are in control.

If you Aid an Ally and have an asset that gives you any additional benefits on the outcome of your [[MV_Secure an Advantage|Secure an Advantage]] or [[MV_Gain Ground|Gain Ground]], your ally also takes those benefits (instead of you).

> [!cite]- Narrative example
> Your ship must find a way through a dense asteroid field. “Can you plot a path for me?” the pilot asks. This is an opportunity for you to Aid Your Ally. You envision using the ship’s scanners to find the safest course through the chaos, and roll Secure an Advantage +wits. If successful, you will pass along the benefits of the outcome to the pilot.

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
| **[[MV_Compel\|Compel (move)]]** | #Pedia/Moves/Adventure - #Pedia/Moves/Combat - #Pedia/Moves/Exploration -  #Pedia/Moves/Recover - #Pedia/Moves/Scene_Challenge | **[[MV_Check Your Gear\|Check Your Gear (move)]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>