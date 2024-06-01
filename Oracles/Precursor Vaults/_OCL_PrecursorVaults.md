---
## Source
SourceMaterial: "Ironsworn: Starforged"
SourceAuthor: "Shawn Tompkin"

## Page
Alias: "Precursor Vaults Oracle"
PageType: "Oracle"
PageCategory: "Index"
---
# [[_OCL_Index|Oracles Summary]]: Precursor Vaults
## Summary: Exploring Precursor Vaults
When you first come upon a vault, use the tables on the previous two pages to help envision its form and nature. For a more abstract prompt, just use the [[OCL_Core#Oracle: Descriptor|Descriptor]] oracle. In either case—if that’s enough detail for the role of the vault in your story, stop there. 

### Detailed Precursor Vault Generation
If the survey of a vault is a focus for your current quest, use the oracle tables in this section to generate a more complete picture of the site. ==See the next page for a diagram of the three main phases of exploration.== #missingArt 
 - Exterior: Start by generating the basic form and characteristics of the vault using [[OCL_Vault-Create|Vault Creation]] oracles. These features represent what you observe from a safe distance. 
 - Interior: If you enter the site, check the [[OCL_Vault-Interior#Oracle: Precursor Vault: Interior First Look|Inner First Look]] oracle for initial impressions of what lies within. If you explore further, use the [[OCL_Vault-Interior#Oracle: Precursor Vault: Interior Feature|Interior Feature]] oracle to define what you find or encounter. If you [[MV_Undertake an Expedition]] within a vault, check this oracle if you want help setting the scene for a waypoint. 
 - Sanctum: As you delve deeper into a vault, the corruption and strangeness of the place takes hold. Use the [[OCL_Vault-Sanctum#Oracle: Precursor Vault: Sanctum Feature|Sanctum Feature]] oracle to represent the aberrant nature of a vault’s depths. 

### Delving the Sanctum
Your passage from the Interior into the Sanctum is triggered by a rolled result on the [[OCL_Vault-Interior#Oracle: Precursor Vault: Interior Feature|Interior Feature]] oracle: “Transition into the Sanctum.”

If you [[MV_Undertake an Expedition|Undertake an Expedition (move)]] into a vault, you can also use the progress track as a gauge for your current location. Once you reach six or more filled progress boxes, you have reached the Sanctum.

If you envision a vault as particularly strange and perilous, use the Sanctum as the framing for the entirety of your exploration. If it is relatively mundane, use only the Interior.

### Revealing the Vault's Purpose
If the original function of the vault is a mystery, use the [[OCL_Vault-Purpose#Oracle: Precursor Vault: Purpose|Vault Purpose]] oracle to see what lies at its heart. Check this oracle when your story leads to a reveal of the site’s true nature, such as when you [[MV_Finish an Expedition]].

### Perils and Opportunities
Use these oracles to help envision a complication or favorable circumstance within a vault, such as when you [[MV_Explore a Waypoint]] and are prompted to envision a peril or opportunity.

## Precursor Vault Oracles

```dataview
TABLE without ID
	link(file.link, OracleFocus) As "Precursor Oracle Focus",
	SourceMaterial As "Source Material"
WHERE contains(PageType, "Oracle") & contains(PageCategory, "Vault") & !contains(PageCategory, "Index") & !contains(file.path, "Template")
SORT OracleFocus, asc
```

## Tags
#Pedia/Oracles/PrecursorVaults

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>