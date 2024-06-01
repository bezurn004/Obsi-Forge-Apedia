---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Derelicts Oracle"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Derelicts
## Summary: Exploring Derelicts
Derelicts are broken into zones for primary areas and functions. When you envision moving from one section to another while exploring a derelict, you may roll or choose on the zone chart on the opposite page to help identify what you find. If that’s enough detail, stop rolling and envision the nature of those spaces. You can also use the [[OCL_Core#Description and Focus|Descriptor and Focus]] to generate additional aspects of a zone or as an alternative to rolling for a zone.

### Detailed Derelict Generation
If you want to give your exploration of a derelict extra focus, use the zone oracles on the following pages. Each includes several tables. 
- Area: Roll on this table to help envision the spaces you encounter in that segment of your exploration. Each zone may consist of one or more areas as appropriate to what you envision for the overall complexity of the derelict. If you [[MV_Undertake an Expedition|Undertake an Expedition (move)]], an area can serve as a waypoint in your survey of the derelict. 
- Feature: Roll on this table when you want to reveal new aspects of your current surroundings. This is best used sparingly, a bit of occasional extra detail or ambiance, rather than rolling for every segment of your exploration. 
- Peril: Roll on this table when you want help envisioning a complication or danger within a zone, such as when suffering a cost as an outcome of your exploration. 
- Opportunity: Roll on this table when you want inspiration for a beneficial encounter or event within a derelict, such as when you roll a strong hit with a match as you [[MV_Undertake an Expedition|Undertake an Expedition (move)]], or if you [[MV_Explore a Waypoint|Explore a Waypoint (move)]] and find an opportunity.

If you encounter a prompt for a “New Zone” when rolling for an area, you are transitioning into a different section of the derelict, and can roll or envision that zone as you like. “New Zone via >Access” means you should first envision the connecting path between the old zone and the new; the Access oracles can help flesh this out.

### Surveying a Prepared Site
If you envision your character with a map or scan of the derelict, or the goal of your exploration is to reach a specific zone (such as the bridge on a derelict starship), you can create a simple flow chart of the layout. Include zones and the access types that connect them. Leave some blank zones to discover during play. Use this map—along with rolls on the zone oracles as appropriate—to help envision your path through the site.


## Derelict Oracles

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Derelict Oracle Focus",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Derelict") & !contains(PageCategory, "Index") & !contains(file.path, "Template")
SORT OracleFocus, asc
```

## Tags
#Pedia/Oracles/Derelicts

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>