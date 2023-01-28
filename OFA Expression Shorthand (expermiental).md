# Asset Expression shorthand

### Logical Operators
| Expression | Meaning | Example |
| --- | --- | --- | --- |
| ? | If | ?(AD=3) : "If action dice equal 3" |  |
| : | Then | ?(AD=3):"win" : "If action dice equal 3 then win" |  |
| () | Group expressions | one or more values to evaluate |  |
| \| | Or | "This"\|"That" : "This or that" |
| & | And | "That"&"This" : "That and This" |

### Action Rolls
| Expression | Meaning | Example |
| --- | --- | --- |
| AD | Action Dice | example |
| AR | Action Roll | example |
| ARo | Action Roll outcome | -1=missMatch, 0=miss, 1=weakhit, 2=stronghit, 3=strongMatch |
| holdAD | Hold a rolled AD | holdAD="false" |
| heldAD | Value of a AD on hold | heldAD=AD.Value |
| MOM | Momentum |  |
| CD1 | Challeege Die 1 |  |
| CD2 | Challenge Die 2 |  |
| EDG | Edge |  |
| IRN | Iron |  |
| SDW | Shadow |  |
| HRT | Heart |  |
| WIT | Wits |  |
| HET | Health |  |
| SPR | Spirit |  |
| CTK | Companion Track |  |
| ITG | Integrity |  |
| Prog(TrackID) | Progress Track |  |




[Clash](z_Obsi-Forge-Apedia/Moves/Combat/Clash.md)
[Strike](z_Obsi-Forge-Apedia/Moves/Combat/Strike.md)
[Sojourn](z_Obsi-Forge-Apedia/Moves/Recover/Sojourn.md)
[Heal](z_Obsi-Forge-Apedia/Moves/Recover/Heal.md)
[Hearten](z_Obsi-Forge-Apedia/Moves/Recover/Hearten.md)
[Resupply](z_Obsi-Forge-Apedia/Moves/Recover/Resupply.md) 
[Compel](z_Obsi-Forge-Apedia/Moves/Adventure/Compel.md)
[Repair](z_Obsi-Forge-Apedia/Moves/Recover/Repair.md)