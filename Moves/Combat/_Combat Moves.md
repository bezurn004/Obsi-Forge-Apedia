---
Alias: "Combat Moves"
PageType: MoveIndex
PageCategory: Combat
---
# [[_Moves Index|Moves]] Summary: Combat

```dataview
TABLE without ID
	link(file.link, alias) As "Move Name",
	InlineCmd As "Inline Command",
	RollType As "Roll Type"
WHERE contains(PageType, "Move") & contains(PageCategory, "Combat") & !contains(PageType, "Index")
SORT file.name asc
```


The Forge is a perilous galaxy. Factions fight for control. Pirates hunt the spaceways. Raiders prey on vulnerable settlements. Dangerous creatures and chaotic terrors stalk the unwary. Dreaded foes and powerful forces will oppose your sworn quests. Eventually, you’ll be forced to fight. 

When you face one or more foes in high-stakes, action-oriented conflict, use the combat moves. These moves encompass on-foot action and vehicle sorties, or both as part of the same challenge.

Before we dive into the combat moves, there are a few terms and concepts to keep in mind for managing combat challenges. See the following pages for details.

## Combat Objectives
Most combat challenges are driven by something other than simply inflicting physical violence against your foes. What are you trying to achieve? These are your objectives. For example: 
- Escape the swarm of pirate ships 
- Upload the stolen data 
- Repel the raiders 
- Cover the evacuation of the settlement 
- Shut down the main reactor 

Much like quests, connections, and expeditions, combat is managed through progress tracks and resolved with a progress move. You’ll set one or more objectives when you [[MV_Enter the Fray|Enter The Fray (move)]] by naming them and giving them a rank. Then, you accrue progress toward those objectives by making combat moves. When you are ready to resolve an objective, [[MV_Take Decisive Action|Take Decisive Action (move)]]. 

A combat challenge involves action-oriented conflict, but it is not necessarily lethal. You should envision the actions of your character and your foes as appropriate to their intent and capabilities. For example, a [[MV_Strike|Strike (move)]] can be framed as a bruising punch, a shot from a stun gun, or a hail of deadly gunfire. But if you have an objective and neither side is willing or in a position to fight for it, that challenge is probably best represented through other moves. Combat is dangerous, messy, and chaotic. It’s often a last resort.

## Combat Position
In a fight, your position is defined as one of two states: 
- When you are in control, you make proactive moves to gain advantage and inflict forceful damage or destruction. 
- When you are in a bad spot, you must make reactive moves to get in position, overcome hazards, and thwart attacks.

Some combat moves are inherently proactive or offensive and can only be made when you are in control. Others are reactive or defensive and are made when you are in a bad spot. The text of each combat move will describe the requirements (phrased as “when you are in control” or “when you are in a bad spot”), and the outcome for those moves will set your new position.

You may also make moves that aren’t specific to combat, such as when you [[MV_Endure Harm|Endure Harm (move)]] to resist injury or [[MV_Repair|Repair (move)]] your vehicle in the midst of a fight. To determine whether a move puts you in control or in a bad spot, follow these guidelines (unless a move tells you otherwise): 
- When you score a strong hit, you are in control. 
- When you score a weak hit or miss, you are in a bad spot.

### Position and Allies
You and your allies track position independently. Shift the focus between characters and make moves when they are triggered. A character who is in control makes proactive moves to cause damage or setup advantages. A character in a bad spot defends against attacks, attempts to overcome obstacles, and tries to get back into the fight. 

Combat is a fluid situation. Talk out what happens as if moving a virtual camera around your imagined scene. Bring the chaos of the fight to life. Use a dramatic moment to jump to a different character. Keep things moving to give everyone time in the spotlight

### Position and Foes
You do not track a position or make moves for your opponents. When you are in a bad spot, NPCs take actions in the fiction of the scene that force you to react. When you are in control, you make proactive moves to achieve your objectives and envision how your foes try to thwart you. 

When you’re not sure what an enemy does next, particularly when they have you in a bad spot, [[MV_Ask the Oracle|Ask the Oracle (move)]]. The foes in [[GNPC_Forging NPCs|Forging NPCs]] include traits and tactics to help envision their actions. The [[OCL_Combat Action|Combat Action Oracle]] offers prompts you can interpret as appropriate to the nature of the enemy and your objective.

## Combat Range
When you [[MV_Strike|Strike (move)]] or [[MV_Clash|Clash (move)]] the stat you roll is determined by your range relative to your foes: close quarters (+iron) or at a distance (+edge). This applies to vehicle and personal combat. Most exchanges of gunfire or vehicle-to-vehicle barrages are at a distance. When you are on foot at close quarters, you fight hand-to-hand or use ranged weapons at a brutally close range. In a vehicle, close quarters can mean point-blank strafing runs, short-range volleys, and ramming.

Changing your range might require a move to overcome obstacles, or is simply woven into the narrative of other actions. Enemy maneuvers can also change the range. For example, if you Strike a charging creature with gunfire and roll a miss, you’ll likely find yourself at close quarters.

Apart from that, there’s no need to track the geography of combatants in combat. Keep it chaotic and exciting. Envision a fight as a cinematic set piece with dynamic movement, complex terrain, environmental effects, unexpected dangers, and cunning foes. 

## Combat Resources
The gear, companions, and vehicles you bring to bear provide narrative detail for a combat challenge and frame your ability to make moves. When you act to achieve your objectives, take these resources into account. Some of your combat capabilities might be represented by assets. But most are simply an aspect of your character and the situation. How are you armed and armored? Who stands beside you? What tools of war or natural abilities does your foe wield? What hazards or advantages does the environment present? Weave these elements into the fiction of the scene to create a dramatic, dynamic challenge. 

## Combat Scale and Difficulty
Take the relative scale and power of the combatants into account when setting the rank of objectives. If you are well-prepared and in a strong position to achieve an objective, set its rank appropriately low. If you are outmatched, make it higher. A rank of formidable is a good default. When you [[MV_Enter the Fray|Enter The Fray (move)]], adjust it from there to reflect situational advantages or drawbacks. Or use multiple objectives to ramp up the complexity and danger of the fight, especially when playing with allies. Then, when you must [[MV_Pay the Price|Pay the Price (move)]] during combat, the cost should reinforce the danger of the situation and the relative power of your foes. 

In some cases, the scale of a foe will make direct assaults or defenses impossible. Your pistol is harmless against a titanic beast. Your [[AST_Snub Fighter|Snub Fighter (asset)]] is a minor nuisance against a massive dreadnought. Remember: fiction first. If you aren’t in a position to take an action, envision another approach. If all else fails, you may need to [[MV_Face Defeat|Face Defeat (move)]].

## Battle Stations!
The combat moves can depict any scale of action-oriented conflict—even the clash of mighty starships. If you are playing solo and at the helm of your [[AST_Starship|Starship (asset)]] or a support vehicle, you fly and fight independently. In co-op and guided play, you and your allies work together to survive. 

There are no strict shipboard combat roles in Starforged. You’ll react to threats and take action as appropriate to your character’s nature and capabilities. But this doesn’t mean a character who serves as a [[AST_Healer|Healer (asset)]] is stuck waiting for a patient in the medical bay. On a ship with a small crew, everyone is expected to lend a hand in a crisis. Get in a gun turret. Operate the sensor console. Rush through smoke-filled corridors to put out a fire. You are broadly capable and can assist outside your specialties. 

To create a more exciting and involving shipboard combat challenge, let the narrative twists and turns of the fight create predicaments and opportunities for the crew. Here are some examples of shipboard combat tasks for co-op and guided play. In solo play, you may need to jump between or prioritize actions. 
- Command: Coordinate, make plans, provide motivation or comfort 
- Countermeasures: Deploy electronic countermeasures, defend against incoming missiles 
- Damage Control: Resist damage, suppress fires, patch hull breaches, fix systems, tend to mechanical companions 
- Engineering: Tune engines, manage power, bypass failing systems 
- Escort: Operate a support vehicle 
- Gunnery: Energize or ready weapons, lock on targets, fire weapons 
- Infantry: Repel boarders, launch raids against enemy vessels 
- Medical: Tend to the wounded 
- Piloting: Maneuver to get in position, line up a shot, evade incoming fire, avoid obstacles, pursue or escape targets 
- Sensors: Survey surroundings, scan foes, track and identify targets, plot navigation paths 
- Systems: Manage communications, jam or hack enemy systems, defend against electronic threats 
 
Characters who are in control will envision their actions through proactive moves such as [[MV_Gain Ground|Gain Ground (move)]] or [[MV_Strike|Strike (move)]]. Characters in a bad spot need to get in position, overcome obstacles, avoid threats, and fight back using moves such as [[MV_React Under Fire|React Under Fire (move)]] and [[MV_Clash|Clash (move)]]. If you are in control and directly supporting another character, you can [[MV_Aid Your Ally|Aid Your Ally (move)]]. In addition, [[_Suffer Moves|Suffer Moves]] and [[_Recover Moves|Recover Moves]] will come into play as the crew deals with harm, stress, and damage.

> [!quote]- Narrative example
> Archer and Luna are playing Starforged in co-op mode. They are aboard their STARSHIP, flying through an asteroid field, on the run from a pack of pirate ships. Their objective: escape the pirates. 
> 
> Both of them are in a bad spot. Luna is in a gun turret. Archer is in the pilot’s seat, weaving through spaceborne rocks. 
> 
> “A big asteroid tumbles right into our path,” Archer says. “I’m going to React Under Fire to avoid it.” He rolls +edge, and scores a strong hit. He is now in control. 
> 
> “Can you fly in a straight line, maybe?” Luna says. She is envisioning her character struggling to aim at the pursuing ships in the midst of Archer’s frantic maneuvering. 
> 
> “Since I’m in control now,” Archer says, “let me see if I can get you lined up for a shot. I’m going to make the Aid Your Ally move with Gain Ground.” 
> 
> Archer rolls +edge again, and scores a weak hit. Per the Aid Your Ally move, this outcome puts Luna in control, but Archer is now in a bad spot. “I get us in perfect position,” he says, “but I’ve sacrificed some speed and the pirates are gaining.” 
> 
> Luna takes the momentum bonus from Archer’s Gain Ground outcome, lines up a shot on the lead pursuer, and rolls to Strike. Unfortunately, it’s a miss. Things have gone from bad to worse. 
> 
> “I take the shot,” she says, “but the lead ship dodges and all I manage to do is knock a chunk out of a space rock. The pirates are firing back. Since I need to Pay the Price, let’s say we take a hit?” 
> 
> “Yeah, the ship buckles as they rake gunfire across the hull. Should we roll to Withstand Damage?” 
> 
> “Actually,” Luna says, “let’s hold onto our ship integrity for now and throw a new complication into the mix. Maybe there’s a blown panel and a fire breaks out. If we don’t manage to deal with it, then we need to Withstand Damage.” 
> 
> “Yeah, so the ship rocks from the gunfire. An alarm buzzes in the cockpit. I holler over comms, ‘we’ve got a fire in the engine room!’” 
> 
> “I’m on it!” Luna says. “I drop out of the turret, climb down the ladder, and head for the engine room. I’ll React Under Fire when I get there. Meanwhile, those pirates are closing in. What are you doing in the cockpit? 
> 
> “You mean besides praying?” Archer says.

#Pedia/Moves/Combat 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>