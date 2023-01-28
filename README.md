# Readme
The Obsi-Forge-Apedia (OFA) is a project to enhance the source material from the Ironsworn: Starforged Table Top Role Playing Game. 

## Dependencies
* Obsidian (https://obsidian.md)
  This repository is created within Obsidian and the files are stored in mark-down, with some HTML tags as well.
- Forge In Obsidian (https://github.com/ericbright2002/Forged_in_Obsidian)
  Initial inspiration was working with Eric's great work with in-line scripts.  Some files share the same name, so full path links are needed.

## How to Use
1. Download the Obsidian app on your computer (so far only used on Windows).
2. Download the Forged-In-Obsidian vault 
	1. (https://github.com/ericbright2002/Forged_in_Obsidian)
	2. Extract the vault
	3. Launch Obsidian and open a vault based on the location of extracted content
3. Download this repository
	1. Extract to a temporary folder
	2. Move the extracted content within the location of the Forged-In-Obsidian vault 
4. Open Obsidian Forged-In-Obsidian and validate OFA content is functional.

## Project Mission
The goal of this work is to digitize the game's documentation into markdown and expand on the below goals:
### Refactor
  The layout and phrasing to be more visually appealing and clear.  Not bound by physical paper, the content should breath more openly.
  
### Refine 
  Add meta-data and dynamic queries and tables to provide enhanced functionality  for running games using Obsidian.
  
### Elaborate
  Answer questions that are ambiguous in the game's material that are open to interpretation or confusing.

The overall mission is to provide an alternative, easier to use, reference material for Ironsworn: Starforged.

## Project Roadmap
### Needed for completion
These are tasks that are core to completing the conversion of the source material into markdown.

#### Phase 1:
The focus on phase 1 is to import data.  During this process layout refactors and grammatical refinements will take place.
- [ ] Import and refine source data from...
	- [x] Rules sections
	- [ ] Campaign Creation sections
	- [ ] Character Creation sections
	- [x] Moves sections
	- [x] Assets sections
	- [ ] Oracles sections
- [ ] Ambiguous Clarification
	- [ ] Resolve ambiguous Rules
	- [ ] Resolve ambiguous Campaign Creation
	- [ ] Resolve ambiguous Character Creation
	- [ ] Resolve ambiguous Moves
	- [ ] Resolve ambiguous Assets
	- [ ] Resolve ambiguous Oracles

#### Phase 2:
The focus  on phase 2 is to evaluate the key terminologies used in the source material and translate them into YAML front-matter
 - [ ] Define meta data structure and values index for..
	 - [ ] Rules sections
	 - [ ] Campaign Creation sections
	 - [ ] Character Creation sections
	 - [ ] Moves sections
	 - [ ] Assets sections
	 - [ ] Oracles sections
 - [ ] Create data-view queries in various sections to enrich content to be more elaborate.

### Nice to haves
 - [ ] Create a new campaign creation wizard
 - [ ] Create a new player creation wizard
 - [ ] Expand on the in-line commands to use the meta-data defined.
 - [ ] Create visual templates for the following game aspects
	 - [ ] Quest flow charts
	 - [ ] Exploration flow charts
	 - [ ] Encounter flow charts

### Wish on a Star
- [ ] Create interface for running a fully featured Starforged session

## Change Log
### v0.11
High Level
- Added dataview tables to the Moves and Asset pages
- Added previous parent page as link in H1 and H2 page titles
- Complete Asset summary pages (custom summaries)
- Polish to Moves and Asset sections. Typos, formatting and layout adjustments.
- Created "Aspect" and "Gameplay Role" categories to help categorize Moves and Assets.
- First pass on import of gameplay guidelines


Detailed
- Added dataview queries to Move pages for related assets and related moves
- Added missing or adjusted front-matter to moves pages
- Added alias fields to the Summary and Index pages
- Refactored front-matter for "Type" and "Category" to "PageType" and "PageCategory"
- Added following front-mater fields to Moves pages
	- InlineCmd - Forged-In-Obsidian inline command shortcut
	- RollType - Type of roll that is being made (Action, Progress, Oracle, None)
	- RollStat - Stat(s) used for RollType = Action
	- ProgressTrack - The Track to be used for RollType = Progress
	- RollPreReq - Key with true value that is required to make an Action roll
	- RollTable - Target table to roll for Oracle RollTypes
- Refactored front-matter on AssetPages
	- Properties -> GameplayRole
- Added dataview queries to Moves and Asset pages
- Revised Moves summary pages.
- Added Asset Moves summary, with unique dataview lookup
- Add parent page as link in H1 and link to summary in H3  (breadcrumbs)
- Completed Asset summary pages
- Added Gameplay folder and subsequent pages
	- Getting Started
		- The Basics
		- Tone and Setting
		- Materials for Play
		- Principals of Play
		- Navigating the Forge
		- The Flow of Play (summary)
	- Fundamental
		- Player Characters
			- Moves
			- Action Roll
			- Momentum
			- Tracks
			- Condition Meters
			- Impacts
			- Assets
			- Equipment
			- Vehicles
		- NPCs
	- Oracles
	- Optional
		- Clocks

### v0.1
Initial import and refactor for 
 * Moves
 * Assets