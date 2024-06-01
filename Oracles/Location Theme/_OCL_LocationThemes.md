---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Location Themes Oracle"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Location Themes
## Summary: Exploring Location Theme Locations
Themes help you envision atmosphere, features, and encounters within an unusual, aberrant, or important location. Each theme on the following pages includes a set of oracles. 

Use these oracles to...
- **Feature:** Reveal a new aspect of the location. 
- **Peril:** Help envision a complication or hazard. 
- **Opportunity:** Help envision a beneficial encounter or event, such as when rolling a strong hit with a match in a location.

You can answer questions about a place using only the tables provided for a theme, such as when delving into an Infested cave. Or pair a theme with other location oracles for more flavor and variety; for example, you might explore a Haunted Grave World, a Ruined Derelict, a Sacred Precursor Vault, or an Inhabited Settlement.

When mixing-and-matching a theme with another set of tables, use the techniques described for an oracle array (page 384) to determine which oracle you reference for that question or phase of your exploration

## Oracle: Location Theme Type
Choose a theme that supports what you know of that location’s nature. For a random theme, roll on this oracle.

| 1d100 | Result |
| --- | --- |
| 1-15 | [[OCL_LocationTheme-Chaotic\|▶Chaotic]] |
| 16-25 | [[OCL_LocationTheme-Fortified\|▶Fortified]] |
| 26-35 | [[OCL_LocationTheme-Haunted\|▶Haunted]] |
| 36-50 | [[OCL_LocationTheme-Infested\|▶Infested]] |
| 51-60 | [[OCL_LocationTheme-Inhabited\|▶Inhabited]] |
| 61-75 | [[OCL_LocationTheme-Mechanical\|▶Mechanical]] |
| 76-90 | [[OCL_LocationTheme-Ruined\|▶Ruined]] |
| 91-100 | [[OCL_LocationTheme-Sacred\|▶Sacred]] |
^table-ISSF-Core1-0-OclLocationThemeTypes

## Location Theme Oracles

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Location Theme Oracle Focus",
	OracleDescriptor As "Description",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Location Theme") & !contains(PageCategory, "Index") & !contains(file.path, "Template")
SORT OracleFocus, asc
```

## Tags
#Pedia/Oracles/LocationThemes


<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>