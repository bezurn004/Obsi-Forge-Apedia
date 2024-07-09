---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"
SourceLink: 

## Page
aliases:
  - "Repair (move)"
PageType: Move
PageCategory: Recover
PageOrder: 5

## Move
MoveName: Repair
InlineCmd: REPAIR
Trigger: ["When you make repairs to your vehicles, modules, mechanical companions, or other devices"]
Apprach: ["Make your own repairs","Obtain repairs from someone (not an ally)"]
RollType: Action
RollStat: [Wits, Supply]
ReferencedMoves: 
  - [[MV_Sacrifice Resources]]
  - [[MV_Pay the Price]]
  - [[MV_Ask the Oracle]]
---
# [[_Moves Index|Moves]] - [[_Recover Moves|Recover]]: Repair
## Repair: Move Card
>[!abstract]  Trigger and Preparation
>**When you make repairs to your vehicles, modules, mechanical companions, or other devices...** ^trigger

> [!warning] Action Roll
> Envision the situation and roll. If you… 
>- Make your own repairs, or direct a companion to make repairs: Roll +wits
>- Obtain repairs from someone (not an ally): Roll +supply ^action-roll

> [!challenge-strong] On strong hit
> You gain repair points as appropriate to the situation, per the table below.
> Points gained per situation
>- **At a facility:** 5 points
>- **In the field:** 3 points
>- **Under fire:** 2 points
>
> Additionally, you may [[MV_Sacrifice Resources|Sacrafice Resources]] and exchange each -1 of supply for 1 extra repair point (up to 3 points).
> Spend repair points as follows. Unused points are discarded.
> > [!mechanics]- Repair Cost Table
> > ![[#^table-repair-costs]]
> 
> > [!cite]- Narrative prompt
> > Envision how you are able to repair the object within the context of the situation. ^strong-hit

> [!challenge-weak] On a weak hit
> You gain repair points as appropriate to the situation, per the table below.
> Points gained per situation
>- **At a facility:** 3 points
>- **In the field:** 1 points
>- **Under fire:** 0 points
>
> Additionally, you may [[MV_Sacrifice Resources|Sacrafice Resources]] and exchange each -1 of supply for 1 extra repair point (up to 3 points).
> Spend repair points as follows. Unused points are discarded.
> > [!mechanics]- Repair Cost Table
> > ![[#^table-repair-costs]]
> 
> > [!cite]- Narrative prompt
> > Envision how you are able to repair the object within the context of the situation. ^weak-hit

> [!challenge-miss] On a miss
> The repairs are not made and the situation worsens. [[MV_Pay the Price|Pay the Price]]
> > [!cite]- Narrative prompt
> > Envision how circumstances have thwarted your attempt to repair the object. ^miss



## Full Description
The life of a spacer is a dangerous one, and sometimes the machines you rely on bear the brunt of those perils. When your vehicles, modules, robotic companions, or other devices need mending, make this move. 

If you’re making your own repairs, or if you assign the task to a companion, roll +wits. If you are instead relying on the skill and good graces of another character, such as a shipwright at a planetside docking bay, or a mechanic in some remote outpost, roll +supply. Making this move +supply represents using goods, funds, or materials to subsidize the work of a skilled NPC. 

When you Repair and score a hit, you gain repair points. This is a limited resource used only within the scope of the move to prioritize and make repairs. The amount of repair points you earn varies according to the situation and the outcome of the move, per the included table. Here’s a summary of those situations: 
- **At a facility:** You have access to a well-equipped location suited to conducting repairs, such as a settlement dockyard or repair shop. 
- **In the field:** You are on your own in the depths of space, on a remote planet, or in a community that lacks equipment and infrastructure. 
- **Under fire:** You are in the midst of a crisis, such as in combat, navigating a hazardous environment, under extreme time pressure, or dealing with life-and-death mechanical failures. 

If you’re unsure whether a particular location has the infrastructure needed to count as a “facility,” [[MV_Ask the Oracle|Ask the Oracle]]. But feel free to give it the benefit of the doubt. Even the most far-flung settlements often have the skills and resources to keep their machines running. 

If you roll a hit and want to bolster your available repair points, you can [[MV_Sacrifice Resources|Sacrafice Resources]] and trade supply for repair points, one for one. 

Then, use the list of costs in the Repair move to allocate repair points to specific tasks, including clearing vehicle impacts, raising vehicle integrity, fixing broken modules, and bolstering the health of mechanical companions. If you are playing with allies, repair points can be applied to their assets if it’s reasonable under the circumstances. 

The “repair any other device” options are used to deal with narrative complications for equipment, machines, and components. For example, you might deal with a faulty shipboard gravity generator, fix a broken weapon, or aid a settlement by repairing their water processor. If you spend 3 repair points, it is fully repaired. If you spend only 2 points, envision a lingering issue for the device that may cause future trouble. ^other-device

If you roll a miss, the repairs are ineffective, and things get worse. Perhaps you are interrupted by a greater peril, unintentionally cause more damage, or are fleeced by a fraudulent mechanic. 

Repair might require seconds, minutes, hours, or days as appropriate to the situation and the scope of the damage. Unused repair points cannot be saved for future use.

> [!cite]- Narrative example
> One of your connections is a tinkerer living alone amid the blasted wastes of a desert world. When your [[AST_Combat Bot|COMBAT BOT]] companion suffers severe damage in a firefight, you visit the tinkerer and roll to Repair +supply to see what can be done.
> 
> Your environment suit malfunctions while exploring a planet with a toxic atmosphere. Running out of air, you hastily Repair and roll +wits. You score a strong hit, which gives 2 repair points for being “under fire.” That’s enough to get the air flowing again, but you envision a faulty battery that leaves your headlamp flickering ominously. It is nighttime, and the darkness closes in… 

### Repair Table
Spend repair points as follows. Unused points are discarded. 

| Repair Cost | Repair Description |
| :---: | --- |
| 2 | Clear the battered impact on a vehicle |
| 2 | Fix one broken module |
| 1 | Take +1 integrity on a vehicle |
| 1 | Take +1 health for a mechanical companion |
| 3 | [[#^other-device\|Repair any other device]] |
| 2 | [[#^other-device\|Repair any other device]], but with a complication or malfunction |
^table-repair-costs

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
| Previous Page | Tags | Next Section |
|:--- |:---:| ---:|
| **[[MV_Resupply\|Resupply (move)]]** | #Pedia/Moves/Recover | **[[_Threshold Moves\|Threshold Moves]]** |

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>