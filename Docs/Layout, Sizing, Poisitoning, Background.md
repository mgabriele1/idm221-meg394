# Layout, Sizing, Poisitoning, Background
## Default Styles & Normalize
- PARAGRPH comes with some sizing
    - 16px margin on the top and bottom (root)
    - 1 rem of space between paragraphs
    - bottom margin of p1 and top margin of p2 are collapsed into 1 rem instead of 2
- use *{margin:0 padding: 0} to reset all margins and padding to nothing
    - lets you size from scratch
- normalize does not flush everything
    - will leave default paragraph settings
- can leave defaults and change them per element when needed
- be careful when using ID selector, might want to use parent selector
    - want most versitale & efficient selector
---
## The Box Model
- html puts content into boxes (div)
- by default the box for any block element takes up as much width as possible and adds line break after
- can define block element height and width to change size of textbox
- can specify padding
    - goes between the text and the border
- can specify border
    - goes around element
    - can be any size you want to spcify
    - case where px is used
    - can be a color or line
- can specify margin
    - goes outside of the border
- calculate height of element
    - top margin + top border + top padding + content height + bottom padding + bottom border + bottom margin
    - same for width
- layout tab in browser editor will let you see box model for element
---
## Height and Width
- <b>overall width/ height of element will be larger than just the element (element + margins etc). calculate into overall width and height </b>
- box sizing property
    - *{box-sizing: border-box;}
        - call at beginning of style sheet
    - will take the width you set and size element down so TOTAL element (including margins etc) is the width you set
- height is ususally left alone - as big as it needs to be
- default value is "auto" based off content inside
    - paragraph will be as wide as it can be
- can use any unit you want to set
    - width:
    - height:
- can set min and max
    - min-width:
    - mad-width:
    - lets you set width that can translate between devices
### Overflow
- what the text that doesn't fit in the box will do
- scroll, hidden, etc
- overflow: auto
    - when something doesn't look the way you want it to
---
## Margins, Border, Padding
Margins 
- can specify margin top, right, bottom, left
- can specify "margin" and can add 1-4 values
    - goes around box in a circle clockwise starting at the top
    - 1 value copies to all 4 sides
    - 2 values: top/ bottom, left/ right
    - 3 values: top, right/ left, bottom
    - 4 values sets: top, right, bottom, left
- can specify "auto" for  margin - will try to center your element on the page
    - <b> use auto for left and right margins </b>
    - <b>NEED TO specify a width for div</b> or will default to take up full page width

Padding
- works the same way as margins except it is on the INSIDE of border
- can specify padding top, right, bottom, left
- can specify "padding" and add 1-4 values

Border
- width: can set top, bottom, left, right LIKE margins and padding
    - thickness of border
- ALSO declare style
    - solid, dotted, dashed, etc
    - more styles can be found online
- ALSO decalre color
    - can add different color for all edges
- shorthand
    - width style color;
    - no commas
- can be used for more than just decoration
    - control negative space
    - a white border can make it look like there is space between elements
- <b>Rounded Edges & Shadows</b>
    - border-radius
        - takes 4 values
    - box-shadow 
        - [horizontal offset] [vertical offset] [blur radius] [spread] [color]
---
## Display
- display: ____;
- tells elements how they behave
    - block, in-line, flex etc.
- in-line: meant to display inside of something else
- block: as wide as ppssible, as tall as needs to break for content, adds line break after self
- elements have defaulted display properties
- can change default display property to something else
    - changes the way element acts on page
---
## Background
- can set background as color, image, etc.
- set background for root element to be behind everything
- background-color
    - color codes or transparent
    - can mix color and image because some images have transparency
- background-image: url ('path to image');
    - <b>path to image is related to location of style sheet </b>
- background-repeat
    - if image repeats/ which directions
    - default is x/y repeat
    - repeat-x, repeat-y, no-repeat
- background-attachment
    - fixed when you scroll
- background-position
    - positions image in div
    - can be pixel values, rem values, etc.
    - can set "bottom right", "top left", etc.
- background-size
    - sets background image size, if smaller than width or height will default to repeat
    - keywords
        - cover: covers available space, will keep proportions
        - contain: will fill only the container it is inside of, will keep proportions
- gradients
    - linear-gradient (direction, color%, color%...)
    - new browesers don't need a lot of information
    - <a href="https://www.colorzilla.com/gradient-editor/"> Gradient Editor CSS </a>
        - can google for gradient code
- <b>background shorthand</b>
    - [color] [image] [repeat] [attachment] [position]



