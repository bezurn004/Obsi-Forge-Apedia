---
## Source
SourceMaterial: "Starsmith Assets"
SourceAuthor: "Eric Bright"
SourceLink: 

## Page
aliases:
  - "Starsmith Assets Index"
PageType: AssetIndex
PageCategory: Index
PageOrder: 0
---
# [[_Assets Index|Assets]] - Starsmith Assets Summary

## New Assets
Contained in these pages are 32 new assets for Starforged with some in each category. I’ve tried to stay true to the style of the original assets except that I’ve added some keywords to save on space. 

## Keywords
There were some phrases that kept coming up over and over again on the cards that I decided to trim down to keywords. This allowed more explanatory text on the cards for how to use the assets while hopefully maintaining ease of use because the keywords are simple enough to memorize. 

They new keywords are: 
	- **Boost** - This is the most common mechanical benefit on assets. It means “add +1 and take +1 momentum on a hit.” 
	- **Roll with advantage** - If you’ve been around 5E at all, you know what this means. It’s when you roll two action dice and keep the higher of the two. This statistically is equivalent to getting an add +1, but it just feels so much more fun!
	- **Roll with disadvantage** - Rolling with disadvantage is rolling two action dice and keeping the lower of the two.
	- **Roll a three dice challenge** This is the mechanic that Shawn uses on some of the original Starforged assets where you roll three challenge dice and keep two. It’s like advantage, but if any challenge dice match, you must keep those. This is a cool mechanic because matches are now more likely which in turn gives you more swingy results of either a strong hit with a match or a miss with a match.

## Asset Categories
>**[[_STRSM_Module Assets|Modules]]**
>All modules are designed as upgrades or additions to your command vehicle, but you could reskin them to be attached to support vehicles much like the original Rover asset. For these modules, I tried to think of some of the classics that were missing (like a Holodeck!) but also modules that provide similar mechanical benefits to existing modules while coming at it from a slightly different narrative framing.


>**Vehicle**
> One additional support vehicle is included with this content: **[[AST_Aquatic HOV|AQUATIC HOV]]**

>**[[_STRSM_Path Assets|Paths]]**
>Fifteen additional character paths are included with this content

>**[[_STRSM_Companion Assets|Companions]]**
>Five additional companions are included with this content

>**[[_STRSM_Deed Assets|Deeds]]**
>Four additional deeds are included with this content

## All Starsmith Assets

```dataview
TABLE without ID
	link(file.link, AssetName) As "Asset Name",
	PageCategory As "Asset Cetegory"
WHERE contains(PageType, "Asset") & contains(SourceMaterial, "Starsmith Assets") & !contains(PageType, "Index")
SORT PageOrder asc
```

## Tags
| Previous Section | Tags | Next Section |
|:--- |:---:| ---:|
| **[[Community-Content]]** | #Starsmith/Assets | **[[_STRSM Oracles Index\|Starsmith Oracles Summary]]** |

<font size=-2>Starsmith Assets is created by Eric Bright and licensed for use under the Creative Commons Attribution 4.0 International License (CC-BY).</font>

