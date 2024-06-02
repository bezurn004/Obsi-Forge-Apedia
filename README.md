# Readme
The Obsi-Forge-Apedia (OFA) is a project to enhance the source material from the Ironsworn Starforged Table Top Role-Playing Game. This vault can be used independently for Starforged campaigns as a reference guide. It was initially created as a supplement to the Forged in Obsidian.

## Highlights of This Work
- Full source material from Ironsworn Starforged digestibable in Obsidian mark down format.
- Data view queries and dolphin diagrams to enhance functionality of source material.
- Oracle roll tables for use during play sessions
- Slight elaborations and editorial additions with the aim of making the source material more easily understood.

## Dependencies
* Obsidian (https://obsidian.md)
  This repository is created within Obsidian and the files are stored in mark-down, with some HTML tags as well.
- (optional) Forge In Obsidian (https://github.com/ericbright2002/Forged_in_Obsidian)
  
### Plugins used for this vault
- Admonition
- Advanced Tables
- Dataview
- Dice Roller
- Forged-in-Obsidian import
	- Inline Scripts
	- Templater

## Installation Instructions

### Stand alone
1. Download the Obsidian app to your device - https://obsidian.md/download
3. Download this repository as a zip file (or by other means)
4. Extract the vault to your desired location on your device.
5. Open Obsidian 
6. Open vault from folder location, pointing to where the zip was extracted.

*There will be references to Forged In Obsidian in-line scripts that will not be applicable to a standalone usage*

### Import into Forged In Obsidian
1. Download the Obsidian app to your device - https://obsidian.md/download
2. Download the Forged-In-Obsidian repository as a zip file (or by other means) - https://github.com/ericbright2002/Forged_in_Obsidian
3. Download this OFA repository as a zip file (or by other means)
4. Extract the Forged In Obsidian zip to a desired location on your device
5. Extract the OFA repository within the top level folder of the extracted Forged In Obsidian vault
	1. Within the extracted folder for OFA, delete the .obsidian folder. This will ensure there are no conflicts with Forged In Obsidian holding the .obsidian folder
6. Open Obsidian
7. Open vault from folder location, pointing to the folder where Forged In Obsidian was extracted.

## Project Mission
The goal of this work is to digitize the game's documentation into markdown and expand on the below goals:

  - Add meta-data and dynamic queries to generate tables for game play rules and resources.
  - Use info boxes to break down key aspects of game play that can be collapsed and imported using linked block references.
  - Answer linger questions that are ambiguous from the game's source rules
  - Create templates that can be used for new campaign creation and gameplay functionality
 
The overall mission is to provide an alternative, easier to use, reference material for Ironsworn Starforged.

## Project Roadmap
### Needed for completion
These are tasks that are core to completing the conversion of the source material into markdown.

#### Phase 1:
The focus on phase 1 is to import data.  During this process layout refactors and grammatical refinements will take place.
- [ ] Import and refine source data from...
	- [x] Rules sections
	- [x] Campaign Creation sections
	- [x] Character Creation sections
	- [x] Moves sections
	- [x] Assets sections
	- [x] Oracles sections
	- [ ] Optional Rules and Extra Content
- [x] Ambiguous Clarification
	- [x] Resolve ambiguous Rules
	- [x] Resolve ambiguous Campaign Creation
	- [x] Resolve ambiguous Character Creation
	- [x] Resolve ambiguous Moves
	- [x] Resolve ambiguous Assets
	- [x] Resolve ambiguous Oracles

#### Phase 2:
The focus  on phase 2 is to evaluate the key terminologies used in the source material and translate them into YAML front-matter
 - [ ] Define meta data structure and values index for...
	 - [x] Rules sections
	 - [x] Campaign Creation sections
	 - [x] Character Creation sections
	 - [x] Moves sections
	 - [ ] Assets sections
	 - [ ] Oracles sections
 - [x] Create data-view queries in various sections to enrich content

### Phase 3
 - [ ] Create a new campaign creation guided templates
 - [ ] Create a new player creation guided templates
 - [ ] Expand on the in-line commands to use the meta-data defined.
 - [ ] Create visual templates for the following game aspects
	 - [ ] Quest flow charts
	 - [ ] Exploration flow charts
	 - [ ] Encounter flow charts

