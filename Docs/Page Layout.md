# Page Layout 1
## Position an Element
- Properties that can be set
    - poisiton
    - top
    - bottom
    - left
    - z - index
        - helps with layering
        - multiple elements on top of each other
---
## Position
- poisition: relative;
- determines how an element is positioned on the screen
    - then include top, bottom, left
### Static
- default
- everything is exactly as expected
- location in structure = location in browser
### Relative
- evrything else stays in normal flow exactly as they are
- lets you position an element relative to bounding box
### Absolute
- takes element out of normal flow
- everything on the page acts like the element isn't there
- in a fixed location, scrolls with page
### Fixed
- takes element out of normal flow
- everything on the page acts like the element isn't there
- positioned somewhere and never moves - scrolls with page 
### Sticky
- takes element out of normal flow
- everything on the page acts like the element isn't there
- fixed position on page, scrolls with page, eventually sticks at some location on page and stops scrolling
- parent element is sticky container
### Z-index
- allows you to arrange layers
- controls which elements are on top
- increments of 1
    - good idea to layer things by 10 so you have room between
- <b> will do nothing if element is STATIC </b>
---
## Float
- <b> new better method for float exists </b>
- when you float an element it is taken out of normal flow
- elements after flow element will fill in space
- lets you push content to left or right
    - item will go as far left or right as possible
    - everthing fills in as close as they can
    - if there is not enough space the other elements will go underneath
- <b>clear </b>
    - can clear left or right to stop unwanted elements from floating
    - can clear left, right, both
- <a href= "https://github.com/philsinatra/IDM221/tree/master/examples/07-layout/01"> Float Examples in class repo </a>