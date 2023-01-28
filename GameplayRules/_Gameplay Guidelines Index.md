---
Alias: "Gameplay Rules"
PageType: Index
PageCategory: Gamplay
---
# Gameplay Rules [[_INDEX|Index]]

## Getting started

```dataview
TABLE without ID
	link(file.link, Name) As "Page TItle",
	CatgoreyOrder As "Category Order"
WHERE contains(PageType, "Gameplay") & contains(PageCategory, "GettingStarted") & !contains(PageType, "Index") & !contains(file.path, "Template")
SORT CategoryOrder asc, file.name asc
```

## Core Gameplay Guidelines
```dataview
TABLE without ID
	link(file.link, Name) As "Page TItle",
	CategoryOrder As "Category Order"
WHERE contains(PageType, "Gameplay") & contains(PageCategory, "Fundamental") & !contains(PageType, "Index") & !contains(file.path, "Template")
SORT CategoryOrder asc, file.name asc
```

## Optional Gameplay Guidelines


## Homebrew

[[_GP_Clocks]]


