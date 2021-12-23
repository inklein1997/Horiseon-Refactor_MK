# Horiseon-Refactor_MK

## Table of Contents
- [Project Goal](##Project-Goal)
- [Links](##Links)
- [Screenshot](##Screenshot)
- [Changes Made to Primary Code](#Changes-Made-to-Primary-Code)
- [Acknowledgements](##Acknowledgements)

## Project Goal
The intention of this project is to **refactor**, or improve code without changing what it does, to ensure that the application meets accessibility standards.  This was done utilizing semantic element tags and alt attributes.

## Links
- [URL to Deployed Application](https://inklein1997.github.io/Horiseon-Refactor_MK/)
- [URL to Github Repository](https://github.com/inklein1997/Advanced-CSS-mini-project)

## SCREENSHOT
![Screenshot of page](./assets/images/inklein1997.github.io_Horiseon-Refactor_MK.png)

## Changes Made to Primary code
### index.html updates
---
**HEADER CHANGES**
```
updated semantic tag for header from <div> to <header>
updated semantic tag for nav bar from <div> to <tag>
changed span class attribute to id attribute
```

**"MAIN" CHANGES**
```
changed div class="content".../div to main.../main
Deleted Class attributes from each section.  IDs were assigned since each section is unique.
added "alt" attributes to imgs
```
**"ASIDE" CHANGES**
```
changed div class="benefits".../div to aside.../aside
Only one class needed for all 3 divs.  Changed to div class="benefit">.../div
added "alt" attributes to imgs
```
**"FOOTER" CHANGES**
```
changed div class="footer".../div to footer.../footer
```

### style.css updates
---
**GENERAL**
```
changed tags in stylesheet to match tag changes made in index.html
reordered css style elements to match flow of index.html
```
**"MAIN" CHANGES**
```
added content in "a {}" to "header nav ul li {}"
deleted "header nav ul {
    list-style-type: none;
}"
consolidated separate h2 in main since all had same styling.
Consolidated all section elements to remove unnecessary and redundant style code
```
**"ASIDE" CHANGES**
```
Corrected stylesheet to match class names and tag name changes that were made on index.HTML
```
**"FOOTER" CHANGES**
```
Corred stylesheet to match class names and tag name changes that were made on index.HTML
```

## Acknowledgements
-  Original code was supplied by the University of Texas at Austin Bootcamp curriculum.