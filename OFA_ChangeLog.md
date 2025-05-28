# OFA - Change Log
Number of Current Files
`$=dv.pages().length`

## Planned Changes

### The Distant Buckets
- [ ] Nail down templates
- [ ] Add community content
	- [ ] Starsmith Mecha
	- [ ] Starsmith Cultures
- [ ] Full Chapter contents
	- [ ] Complete SI linking
	- [ ] Begin import of SF source
- [ ] Oracle results that create an object will trigger a template creation wizard (using Buttons I hope)
- [ ] Add move category to meta data for SF (maybe SI?)

### V0.4.3.4
- [ ] Oracle Rollers
	- [ ] Forge Horizons
	- [ ] Space Encounters Expanded
	- [ ] Ancient Wonders

### V0.4.3.3
- [ ] Create Oracle Tables from content
	- [ ] Forge Horizons
	- [ ] Space Encounters Expanded
	- [ ] Ancient Wonders
- [ ] Add guidance and in-line rollers to paginated oracles
	- [ ] Forge Horizons
	- [ ] Space Encounters Expanded
	- [ ] Ancient Wonders

### V0.4.3.2
- [ ] Full Chapter Content Linking
	- [ ] Forge Horizons
	- [ ] Space Encounters Expanded
	- [ ] Ancient Wonders
- [ ] Paginated Text and Oracles tables linked to references (e.g. Descriptor +  Focus). Page references removed
	- [ ] Forge Horizons
	- [ ] Space Encounters Expanded
	- [ ] Ancient Wonders

## Current Release

### V0.4.3.1
Number of files : 1029
Committed files : 574
- [x] Initial pagination of Community Content
	- [x] Forge Horizons
	- [x] Space Encounters Expanded
	- [x] Ancient Wonders
- [x] Metadata consistency applied to paginated content
	- [x] Forge Horizons
	- [x] Space Encounters Expanded
	- [x] Ancient Wonders
- [x] Various typo and formatting changes
- [x] Removed 'Pedia' tag from asset files
- [x] Add next chapter links to all Full Chapter content
- [x] Added Ancient Wonder token images

## Completed Changes

### V0.4.3
Number of files : 846
- [x] Added Forge Horizons community content (full page)
- [x] Added Space Sightings Expanded content (full page)
- [x] Added Ancient Wonders content (full page per chapter)

### V0.4.2.1
- [x] Remove tags and normalize non-conforming pages to match tagging standards.
	- [x] Pedia tag retained on Assets index pages, as these pages are universal for all content
- [x] Completed roll sheets for Sundered Ilses and Starsmith Oracles
	- [x] For campaign oracles, also add the relevant subjects to the main oracle rollers. (e.g. Oracles from Character creation would be included on both "Creation" and "Character" rollers. On Character, it would be in the "details" section at the bottom)
- [x] Various formatting and fixes to Oracles and Roll table pages

### V0.4.2
- [x] Oracle tables / rollers revamp
	- [x] Change for full 1 - 100 results to use look up rollers
	- [x] Build tables for Starsmith Oracles
	- [x] Build tables for any non-oracle overlooked content
	- [x] Add oracle rollers to Oracle pages within the "Guidance" call out
	- [x] Add oracle rollers to Moves and Source material tables
- [x] Starsmith Oracles
    - [x] Revise structure of tables to match SF / SI style
	- [x] Shorten length of block callouts for abbreviated linking
	- [x] Match H1 headings with SF/SI breadcrumb structure
	- [x] Section contents page alignment to SF/SI structure
	- [x] Tags Previous / Next links note source in parenthesis, remove "Pedia" tags
	- [x] Pad "-" in tables with spaces
	- [x] Refactor Oracle and other table to add roller to listed tables, linked to Oracle Tables
	- [x] In table / guidance block identifiers remove "Ocl" and any other identifier already in file name
- [x] Sundered Isles
	- [x] Oracle pages: add arrows to both >Action + >Theme, etc.
	- [x] In table / guidance block identifiers remove "Ocl" and any other identifier already in file name
- [x] In all OT sections, decide if table links should go to Source material pages or to OT tables
	- [x] Starforged = Source > Transition to OT
	- [x] Starsmith = Source > Transition to OT
	- [x] Sundered Isles = Oracle Tables
- [x] Oracle Roll Sheets
	- [x] Clean up Starforged dice and table links

### V0.4.1.4
- [x] Sundered Isles
	- [x] Added Oracle Table pages for automated oracle rolls using dice roller
	- [x] Refactored Oracles pages to use new Oracle Tables
	- [x] Added rollers to Campaign / Character creation, added corresponding OT Campaign page
	- [x] First pass at refining Starsmith Oracle content
	- [x] Typos and formatting changes as inconsistencies found.

### V0.4.1.1-3
- [x] Restructure to Index page for new Sundered Isles content
	- [x] Added cover pictures of the two main source books
- [x] Re-work on Starforged material to match style of Sundered Isles material
	- [x] H1 Breadcrumbs consistent
	- [x] Chapter indexes and Section indexes with static TOC
	- [x] Rollable oracle tables
	- [x] Missing art filled in in campaign creation, Foes and Encounters
	- [x] Page numbers added
	- [x] Various style, linking and typo revisions
	- [x] Various dataview query revisions
- [x] Fixed many errors on Oracle Roller page due to changes in Oracle headings / possible file corruption (I blame one-drive)
- [x] Moved Starsmith Faction Influence Oracle to the Leadership page. Renamed page to "Sway"
- [x] Various typos, formatting, and style corrections

### V0.4.1
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
	- [x] Full Chapter content for SI


### V0.4
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
### v0.3
>>>>>>> Stashed changes
- Created roll tables as a hub for rolling oracles and linked to their source pages for reference.
- Restructured Asset from headings to callouts so that each has a heading and ability 1-3 section that can be linked into a character sheet
- Initial work on defining which moves are applicable to ambiguous assets
- Fixed various typos and formatting errors throughout.

### v0.2
- Completed import of core rules, campaign creation, denizens, and oracle sections
- Created meta data templates for Asset abilities. The contents of the meta-data are not yet populated'
- Graphs from the guide book were reimagined as Dolphin diagrams, where possible
- Refactored the index page and created back links in the headers so that all pages flow from Index to the branch.
- Dataview queries added to newly added sections as sub menu sections.
- Fixed various typos and formatting errors throughout.

### v0.11
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

### v0.1
Initial import and layout for 
 * Moves
 * Assets