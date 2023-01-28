---
Name: "Advance"
PageType: Move
PageCategory: Legacy
InlineCmd: ADVANCE
RollType: None
Trigger: [""] 
---
# [[_Moves Index|Moves]]: Advance
### Categories: [[_Fate Moves|Fate Moves]]
>[!abstract]  Context and Preparation
>When you develop your abilities, improve your resources, gain a reward, or boost your influence...

> [!warning] Move Action
>  You may spend 3 experience to add a new asset, or 2 experience to upgrade an asset. 
>  Choose from the following categories as appropriate to your focus and opportunities.
>- Module: Upgrade your command vehicle
>- Support Vehicle: Acquire or improve a secondary vehicle
>- Path: Bolster your personal capabilities or follow a new calling
>- Companion: Gain or improve a trusted helper
>- Deed: Learn from your experiences or build a legacy

## Full Description
Make this move when you spend experience to add an asset or upgrade an existing asset. See page 45 for details on how to record spent experience using your legacy tracks. 

When you Advance, you should consider how your recent experiences, successes, and projects have led to your new resources and abilities. You can bend the fiction of your story toward an asset you would like to purchase or upgrade, or let your selection of assets flow naturally from the situations and opportunities you encounter.

For example: 
- You barter some precursor artifacts to pay for a REINFORCED HULL.
- You charted paths into the far reaches of the Forge, making you a skilled NAVIGATOR.
- A grateful connection, a skilled shipwright, presents you with a custom SNUB FIGHTER as a gift.
- You steal an armored EXOSUIT from a band of mercenaries.
- In your downtime, you work to overhaul a deactivated SURVEY BOT. 
- You betray a powerful faction and are now a FUGITIVE. 

Envisioning how your abilities connect to experiences gives them additional significance and context. They will be a reminder of the paths taken, the challenges overcome, and the bonds formed. 

Keep in mind that assets are only part of your character. They help define the major aspects of your role, resources, and abilities, but don’t limit what you can gain or accomplish in the course of your story. 

> [!quote]- Narrative example
> You rescue a stray GLOWCAT from a ruined settlement, but don’t have experience to spend on the companion asset. Your new friend still exists in your story, but doesn’t have narrative focus or mechanical benefits until you Advance and acquire the asset.

## Related Assets
```dataview
TABLE without ID
	link(file.link, title) As "Asset Name",
	PageCategory As "Asset Category"
WHERE contains(PageType, "Asset") & contains(this.file.inlinks, file.link)
SORT PageCategory asc, file.name asc
```

## Related Moves
```dataview
TABLE without ID
	link(file.link, title) As "Move Name",
	PageCategory As "Move Category"
WHERE contains(PageType, "Move") & contains(this.file.inlinks, file.link) & !contains(PageType, "Index")
SORT PageCategory asc, file.name asc
```

## Tags
#Pedia/Moves/Legacy 

<font size=-2>This work is based on Ironsworn: Starforged (found at [www.ironswornrpg.com](http://www.ironswornrpg.com)), created by Shawn Tomkin, and licensed for our use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license  (creativecommons.org/licenses/by-nc-sa/4.0/).</font>