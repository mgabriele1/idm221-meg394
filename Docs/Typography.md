# Typography (HTML & CSS)
- font size drives the sizing and layout of the site
- <a href = "https://www.w3schools.com/css/css_text.asp">Working with text in CSS </a>
---
## HTML Special characters
- copy and pasting symbols will <b>NOT</b> render correctly
- <
  - code reads this symbol as the beginning of a tag
  - &lt
- special entity that represents the charater
  - name
  - numeric value 
- <a href="https://www.w3schools.com/html/html_symbols.asp">List of special characters </a>
- special character plug in
  - only grab the text that you want to change or it will change all symbols
---
## Web Safe Typefaces
- fonts may not always be available on people's computer
  - use fonts everyone has access to
  - provide the font you are going to use
- top safe typefaces - very available
  - arial
  - times new roman
  - courier new/ courier
  - verdana
  - georgia
- <a href="https://www.w3schools.com/cssref/css_websafe_fonts.asp">Web safe fonts </a>
- define a font family
  - p {
    - font-family: arial, helvetica, sans-seriff;
    - font-family: 'times new roman', times, serif;
    - font-family: 'courier new', courier, monospace;}
  - extra fonts listed as backup
- font names more than 1 name get put in quote
---
## Custom Typefaces
- can use fonts on your computer
- serves people a copy of font from browser
- <b> add font file in browser folder </b>
- declaration:
  - @font-face {
    - font-famly: 'name'
    - src: url (folder/file.type) format (type)}
- <a href="https://www.fontsquirrel.com/">Font Optimizer </a>
  - generates webfont
  - checks legality and makes font web ready
  - download font zip
  - open style sheet given and customize to work in project
    - will give you different file names for each style/ weight of the font
  - can specify just the letters you want to use
    - minimizes file size that needs to be downloaded
- <b> have to do process for every style and weight font comes in </b>
  - an entire new font family function needs to be made for every new weight and style
  - at the bottom of font family fuciton need to add "font-weight" and "font-style"
- browser needs woff and woff2
- variable fonts are one file that has all weights and styles in it
  - one line for source
  - format
  - font weight: 1 999
  - font style: normla
  - <b> style sheet will come with font - dont have to type it out </b>
---
## Font Size
- 12px is a set font 
    - doesnt get bigger or smaller with zoom
- 150% or 1.5em 
    - relative units based off parent element
      - html coding sets parent element
      - each child is dependent on parent
- on modern browsers the base font size is roughly 16px
    - if user has not changed any preferences
    - use 16px as our base
- em units 
    - emphasis units
    - preferred method
    - unlimited decimal points
    - <b> 1 em unit = 100% of parent font </b>
    - size you want/ parent size = em
- <b> add comments about font size </b>
- rem units
  - calculations based on root element
  - desired value/ root px value = rem
  - start style sheet by saying <b> "html {font-size =100%;}" </b>
    - sets font size to default
    - default is usually 16px
    - 100% respects whatever the user preference is, 16px or not
  - references back to root every time, avoids having to use parent like em
---
## Font Styling
- after picking typeface and establishing sizing
- weight ranges numerically from 100-700 by 100s
  - normal text is around 400
  - can set weight by "normal, bold, lighter"
- line height
  - important to use relative units
  - value chosen is evenly split between top and bottom of each line
    - ex: 14px would be 7px top and 7px bottom
- relative units based off font size
  - don't need units, 1.5 = 150%
  - 1.5 is good starting point
- font variant
---
## Shorthand Declaration
- font: [style] [weight] [variant] size[/line-height] family;
  - can skip anything you don't want to declare
---
## Formatting Text
- alignment (horizontal/ vertical), indent, justified, decoration
- getting rid of things like underlines under links can be an accessibility issue
  - color blind
- text shadows
  - text-shadow: horizontal offset, verical offset, blur, color;
    - no commas
    - negative numbers go in opposite direction
---
## Browsers
- firefox has the most type development tools
---
## Fonts CSS File
- can make a css sheet to define all new fonts and import it into the main css style sheet 
 



