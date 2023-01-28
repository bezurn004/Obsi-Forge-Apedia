# OFA - Change Log

## v0.11
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
