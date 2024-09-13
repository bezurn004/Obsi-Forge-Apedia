---
Alias: "NPCAliasHere"

## Overview
npc_rank: "Dangerous"
npc_rankvalue: 2
npc_progress: 0
npc_progressimage: "![[progress-track-0.svg]]"
npc_bond: "false"
npc_location: "EnterLocation"

## Characteristics
npc_role1: "NPC Role Here"
npc_role2: "NPC Role Here"
npc_firstLook: "When first encountering this character, choose or roll 1-2 times on the [[OCL_Character-Approach#Oracle: Character First Look|First Look Oracle]]"
npc_goal: "Discover goal during play > [[OCL_Character-Drives#Oracle: Character Goal|Character Goal Oracle]]"
npc_revealedAspect: "Discover aspect during play > [[OCL_Character-Drives#Oracle: Character Revealed Aspect|Character Revealed Aspect Oracle]]"
---
# `=this.Alias`
Rank: **`=this.npc_rank` (`=this.npc_rankvalue`)** | Location: **`=this.npc_location`**
%% Make the Rank description a lookup of the rankValue %%

## Relationship
 
 `=choice(this.npc_bond = "true", "Bonded Relationship", "Developing Relationship Progress")`
 ```dataview
LIST without id embed(link(meta(npc_progressimage).path, "350"))
WHERE contains(file.path, this.file.path)
```

## Character Roles
 **Benefit:** `=choice(this.npc_bond = "true", "Take +2 when making a move aided by either of the character's Roles", "Take +1 when making a move aided by this character's Role")`

| Role 1 | `=choice(this.npc_bond = "true", "Role 2", "" )` |
| --- | --- |
|  |  |

%% Insert button to roll or select from the Character Roles Oracle %%

## Characteristics
| Name | Entry |
| --- | --- |
| Given Name: |  |
| Family Name: |  |
| Call Sign: |  |


### First Look
`=this.npc_firstLook`

### Character Goal
`=this.npc_goal`

### Revealed Aspect
`=this.npc_revealedAspect`


## Affiliations
List the relationship this character has with factions or other characters here.


## Bio
Enter bio here


