# CSS Rules, Starting, Selectors, Browser Defaults
## Rule Sets
- made up of series of selectors
  - what do we want to target on the page
- /* selector*/
  - what will you be editing
- h1 {/* property: value*/}
  - all the rules related to h2
  - (example) color: red;
- comments /* commented out */
---
## Start Writing Styles for Site
- <b> DO NOT use style attributes in HTML </b>
  - have to copy for every section
  - difficult to maintain
- <b> DO NOT imbed style tag in head of document</b>
  - next page in project will not have same styling
  - manage between multiple files
- <b> MAKE A NEW FILE</b>
  - new file for styles
  - add all rules in new file
  - <b>in HTML link file</b>
    - < link rel="stylesheet" href="stylefile<b>.css</b>"/>
    - make sure href is CORRECT PATH
---
## Rules of CSS
- style sets load in "cascading" order
  - overrides with latest declaration
- can declare any CSS rule as important
  - trumps everything
  - declaration !important;
    - should never need if you are writing code
- how to apply style to specific paragraph
  - use ID
  - #id name {can set rule for specific element}
  - <b> will always trump general declaration</b>
- <b>MAINTAINABILITY </b>
  - dont copy element styling, better way to do it
    - classes, IDs
  - keep sheets organized
---
## Class
  - allows you to style multiple elements
  - < p class = "name">
    - does not have to be paragraph, can be any element
  - .class to specify
  - can specify certain types of class 
    - h2.class 
    - applies styling only to h2s
- can select by ID, class, element

### CSS Pseudo-classes
- :psudo-class name
  - can set a : name to style 
- :link, link unvisited
- :visited, visited link
- :active, mouse button down
- :hover, element with mouse hover
- :focus, elements with form
---
## Selectors
- <a href="https://github.com/philsinatra/IDM221/blob/edfc329612b0222a66add1eca418df147fbdc46a/instructor_materials/IDM221-04-selectors.md"> Selector Class Notes </a>
  - styling and types found here^
- Descendent Selector
  - can say "div p {}" 
    - selects any paragraphs under a div and styles them
  - useful for lists and anchors
  - can be very specific 
    - nav ul li a 
- adjacent sibling selector
  - h2 + p
    - selects only paragraph that comes after h2
- child selector
- etc, see link^

### Universal Selector
- <b> "*" selects every element on page </b>
---
## Differences Between Browsers
- <a href="http://necolas.github.io/normalize.css">normalize style sheet</a>
  - clears inconsistencies between browsers
  - file to download and include
  - <b> link ABOVE your style sheet </b>
- reset style sheet
  - gets rid of browser defaults
  - resizes everything to normal
  - no margin
  - no bullets
  - everything is reset
  - <b> link in presentation </b>
### Built in Developer Tools
- <b>Inspector</b>
- right click > inspect
- will find you element in tree
  - HTML code
  - CSS styling on right
    - with line number and file styling came from
- also allows you to change the info and see it changing on site in real time
  - non destructive
  - refresh page and all changes will disappear 
### Normalizing browser
- normalize
  - can link normalize sheet BEFORE style sheet
  - can import normalize sheet into style sheet
- mobile device icon in browser code
  - responsive design mode for mobile size
---
## Variables
- html{ --backgroundcolor: #hexcode}
- can then set: background-color: --backgroundcolor
- whenever you want to make a change only have to do it once in code and it will change everywhere there is a variable




