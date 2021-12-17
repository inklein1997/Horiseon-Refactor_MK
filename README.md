# Horiseon-Refactor_MK

index.HTML updates

<HEADER> CHANGES
updated semantic tag for header from <div> to <header>
updated semantic tag for nav bar from <div> to <tag>


<MAIN> CHANGES
changed <div class="content">...</div> to <main>...</main>
Deleted Class attributes from each section.  IDs were assigned since each section is unique.


<ASIDE> CHANGES
changed <div class="benefits">...</div> to <aside>...</aside>
Only one class needed for all 3 divs.  Changed to <div class="benefit>

<FOOTER> CHANGES
changed <div class="footer">...</div> to <footer>...</footer>


style.css updates

changed tags in stylesheet to match tag changes made in index.html

<MAIN> CHANGES
''added content in "a {}" to "header nav ul li {}"
''deleted "header nav ul {
    list-style-type: none;
}"
consolidated separate <h2> in <main> since all had same styling.
Consolidated all section elements to remove unnecessary and redundant style code

<ASIDE> CHANGES
Corrected stylesheet to match class names and tag name changes that were made on index.HTML

<FOOTER> CHANGES
Corred stylesheet to match class names and tag name changes that were made on index.HTML
