# HTML Intro, VS Shortcuts, Git
## Notes about design
- Navigation
  - conventions
- Important info above the fold
- Colors
  - visually impaired
- Navigate with only keys
- Browser compatibility
- Device compatibility
  - designing for phone
  - horizontal/ vertical
---
## HTML Structure/ Tips
### Tips
- elements define content/ structure
- lowercase file names
- no spaces in file names
- Whitespace
  - use to make code more readable
  - use indentation for groups inside others
  - browser will render code the same with/ without white space
### Tags
- must start with < !DOCTYPE html>
- doc tree comes next
  - opening tag: < html lang="en">
  - closing tag: < /html>
- head and body
  - < head> end with < /head>
  - all tags open and close this way
- headings/ paragraphs
  - < h1> biggest heading
  - 6 different levels of headings
  - < p> paragraph
- no closing tag
  - < br> line break
  - < img> image
- Nesting
  - tags do not overlap
  - tag nested inside close before the outside tag closes
- "title" shows up on tab
---
## Editor Shortcuts
- ctrl p: brings up finder that lets you search all files in project
- crtl shift p: lets you search commands editor can do
  - ex: rename
- Type "html" and choose html: 5 for template
  - must be HTML file for that shortcut to appear
- Browser will run HTML files automatically
- type the element that you want to build
  - h1 then tab
  - adds closing and opening
  - gibberish text "lorem" (can add number for number of words)
- ul: unordered list
- ctrl comma: lets you see preferences
  - word wrap lets you choose characters to wrap down to next line
- COMMENTS
  - Shortcut: ctrl /
  - sytax in HTML: < !-- comment -->
  - anything between will not be rendered by browser
  - can hilight text and turn into comment/ nested comment
- Window looking icon to left built in tool for extensions
  - can install and remove right from editor
- crtl shift p - preview
  - adds preview for markdown
---
## Check Site using W3C Validator 
- Link in repository
- W3C HTML Validator
- Online tool that does same thing as linter
- Solve errors from highest in document down
  - might fix lower errors
---
## Git
- Version control is a system that records all of the changes made to code over a period of time
  - saves time if big mistakes are made/ files are lost
- GitHub Desktop
  - green is new
  - orange is changes
  - red is deleted
  - tracks all changes made in history
- New file
  - initialize as readme
  - add ignore
- .gitignore file
  - folder name/
  - *.filetype
  - anytghing specified git will ignore
  - use link for Windows as starter
- add summary before committing
  - check what is ready to be committed
  - summary is one sentence that explains change (add, update, delete, remove, fix)
  - can use emojis to specify type of edit
  - decription elaborates on summary
  - once committed it clears out hist section
---
## Naming Convention
### For project repository
idm221-meg394