# Horiseon-Refactor_MK

## index.html updates


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

## style.css updates


**general**
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
## LINK TO DEPLOYED APPLICATION
https://inklein1997.github.io/Horiseon-Refactor_MK/

## DESCRIPTION
The original code supplied by curriculum has been modified and corrected for improved web accessibility

## SCREENSHOT
![Screenshot of page](./assets/images/inklein1997.github.io_Horiseon-Refactor_MK.png)