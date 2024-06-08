---
Alias: "Gameplay Rules"
PageType: Index
PageCategory: Gamplay
---
# [[index|Index]]: Gameplay Rules 
The gameplay rules are divided into the below sections

1. [[#Getting Started]]: The foundational knowledge and inspiration for the Starforged rules and setting.
2. [[#Core Guidelines]]: Fundamental knowledge to used for playing the game.
3. [[#Non-Player Characters]]: How to create and interact with characters during your adventures.
4. [[#Optional Guidelines]]: Optional rules that can be used to enhance gameplay
5. [[#Homebrew]]: Community additions that can be added or ignored for expanded gameplay options

## Getting Started

```dataview
TABLE without ID
	link(file.link, Name) As "Page Topic"
WHERE contains(PageType, "Gameplay") & contains(PageCategory, "GettingStarted") & !contains(PageType, "Index") & !contains(file.path, "Template")
SORT CategoryOrder asc, file.name asc
```

## Core Guidelines
```dataview
TABLE without ID
	link(file.link, alias) As "Page Topic"
WHERE contains(PageType, "Gameplay") & contains(PageCategory, "Fundamental") & !contains(PageType, "Index") & !contains(file.path, "Template")
SORT CategoryOrder asc, file.name asc
```


## Non-Player Characters
```dataview
TABLE without ID
	link(file.link, alias) As "Page Topic"
wHERE contains(PageType, "Gameplay") & contains(PageCategory, "NPC") & !contains(PageType, "Index") & !contains(file.path, "Template")
SORT CategoryOrder asc, file.name asc
```

## Optional Guidelines
[[_GP_Clocks]]


## Homebrew
Enter stuff here

