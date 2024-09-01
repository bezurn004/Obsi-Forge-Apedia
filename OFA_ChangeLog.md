# OFA - Change Log

#### V0.4.1
- [x] Add Sundered Ilse material
      
This revision adds the full source of Sundered Isles. While importing this content the aim was to retain a more pure of the content with only slight alterations for formatting purposes. Page numbers are retained, though not sure what their purpose will be besides being references to the full source material

- [x] Assets - Adjusted dataview tables for 3 content types, SF, SI, Community Content
	- [x] Added look up tables for asset decks for various sources
- [x] Oracles
	- [x] Added look up rollers for community content
	- [x] Links to all source content in the page structure content
- [x] Moves
	- [x] Imported moves without braking the structure into component callouts.
	- [x] Links to these moves point to the Move Card for more focused peek ahead.
- [ ] Full Chapter content
	- [ ] Complete linking for whole chapter pages

## V0.4
- [x] Added community content folder along with the following source material
	- [x] Starsmith Assets
	- [x] Starsmith Oracles
- [x] Chapter 1 - closer alignment with source material
	- [x] Highlighted key terms, playing around with linking from Glossary
	- [x] Added diagrams as substitutes for missing art in most cases
	- [x] Corrected omissions and re-arrangement of pages to return to same order as the source
- [x] Chapter 2 - closer alignment with source material
	- [x] Truths
		- [x] Re-added quest-starters under each heading
		- [x] Added blocks to Truths for tables, heading, body, quesstarters
	- [x] Character / Sector / Incident Creation
		- [x] Added missing diagrams and art using native obsidian tools
- [x] Chapter 3: Moves - closer alignment with source material
	- [x] Added "PageOrder", "MoveName", and "ReferencedMoves" fields
	- [x] Added block ID's for each section of the move
	- [x] Altered "Related Moves" dataview query to use new fields
- [x] Chapter 4 Foes and Encounter
	- [x] Added an Index page for the chapter and each section
	- [x] Merged Denizen's section into this chapter's meta-data fields. Will retain Denizen link on Index for quick access.
	- [x] Transposed Sample NPC component table, added "this" meta-data inline scripts
	- [x] Tweaked Denizen meta-data fields and values
- [x] Chapter 5: Oracles pages to alignment with Starsmith additions
	- [x] Added Guidance call outs and positioned them under all headings rather than above the headings
	- [x] Added Oracle Description to meta data and the opening blurb before any sub-headings for combined oracles
	- [x] Added number of rolls per Oracle in the sub-heading with "{#-#}" notation
	- [x] For combined Oracle pages, each oracle on the page is now an alias to easily find when looking to link / import.
- [x] Chapter 6: Asset pages to align with Starsmith addition)
	- [x] Added AssetName to properties section of meta-data
	- [x] Add all CAPS aliases to the assets to match styling of book, retained original (asset) alias
	- [x] Reformat all references (may have missed some) of Assets in Guidelines / Moves to use ALL CAPS style
- [x] Refactored the "Tags" headings on all pages to provide a consistent previous / next page, allowing a sequential navigation method
- [x] Add or adjust missing core ruleset content from first pass of the PDF
- [x] Initial work on building a glossary
- [x] Tried to identify where # additions were made to elaborate. Most tags are hidden in comments, and the elaborated content is _itialisized_
- [x] Various corrections to spelling, grammar, formatting

##### Bug Fixes V0.4.0.x
- [x] Fixed many errors on Oracle Roller page due to changes in Oracle headings / possible file corruption (I blame one-drive)
- [x] Moved Starsmith Faction Influence Oracle to the Leadership page. Renamed page to "Sway"
- [x] Various typos, formatting, and style corrections

#### V0.4.2 #incomplete 
- [ ] Nail down templates prior to new content additions
- [ ] Oracle tables / rollers revamp
	- [ ] Change for full 1 - 100 results to use look up rollers
	- [ ] Build tables for community content
	- [ ] Build tables for any non-oracle overlooked content
	- [ ] Add rollers for new community content
	- [ ] Add oracle rollers to Oracle pages within the "Guidance" call out
	- [ ] Add oracle rollers to Moves and Source material tables
- [ ] Add community content
	- [ ] Starsmith Mecha
	- [ ] Starsmith Cultures


## v0.3
- Created roll tables as a hub for rolling oracles and linked to their source pages for reference.
- Restructured Asset from headings to callouts so that each has a heading and ability 1-3 section that can be linked into a character sheet
- Initial work on defining which moves are applicable to ambiguous assets
- Fixed various typos and formatting errors throughout.

## v0.2
- Completed import of core rules, campaign creation, denizens, and oracle sections
- Created meta data templates for Asset abilities. The contents of the meta-data are not yet populated'
- Graphs from the guide book were reimagined as Dolphin diagrams, where possible
- Refactored the index page and created back links in the headers so that all pages flow from Index to the branch.
- Dataview queries added to newly added sections as sub menu sections.
- Fixed various typos and formatting errors throughout.

## v0.11
High Level
- Added dataview tables to the Moves and Asset pages
- Added previous parent page as link in H1 and H2 page titles
- Complete Asset summary pages (custom summaries)
- Polish to Moves and Asset sections. Typos, formatting and layout adjustments.
- Created "Aspect" and "Gameplay Role" categories to help categorize Moves and Assets.
- First pass on import of gameplay guidelines

> [!example]- **Detailed**
> - Added dataview queries to Move pages for related assets and related moves
> - Added missing or adjusted front-matter to moves pages
> - Added alias fields to the Summary and Index pages- Refactored front-matter for "Type" and "Category" to "PageType" and "PageCategory"
> - Added following front-mater fields to Moves pages
> 	- InlineCmd - Forged-In-Obsidian inline command shortcut
> 	- RollType - Type of roll that is being made (Action, Progress, Oracle, None)
> 	- RollStat - Stat(s) used for RollType = Action
> 	- ProgressTrack - The Track to be used for RollType = Progress
> 	- RollPreReq - Key with true value that is required to make an Action roll
> 	- RollTable - Target table to roll for Oracle RollTypes
> 	- Properties -> GameplayRole
> - Added dataview queries to Moves and Asset pages
> - Revised Moves summary pages.
> - Added Asset Moves summary, with unique dataview lookup
> - Add parent page as link in H1 and link to summary in H3  (minimal bread crumbs)
> - Completed Asset summary pages
> - Added Gameplay folder and subsequent pages
> - Getting Started
> 	- The Basics | Tone and Setting | Materials for Play | Principals of Play | Navigating the Forge | The Flow of Play (summary)
> - Fundamental
> 	- Player Characters | Moves | Action Roll | Momentum | Tracks | Condition Meters | Impacts | Assets | Equipment | Vehicles | NPCs | Oracles | 
> - Optional
> 	- Clocks

## v0.1
Initial import and layout for 
 * Moves
 * Assets