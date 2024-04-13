# CSS Properties
## Font Properties
- font
  - font-size
    - 1px = 1/96th of an inch (inch = 25.4mm)
    - 1pt = 1/72th of an inch 
    - 1em = 100% of the font-size of the parent element
      - Ex: 
      `body { font-size: 16px; }`
      `p { font-size: 2em; }` = 16px * 2
    - 1rem = 100% of the font-size of the root element (html element) 
  - font-weight
    - normal / bold (keywords)
    - lighter / bolder (relative to parent)
    - number (100-900)
  - font-family (Typeface)
    - Sans-Serif: base font with no serifs
    - Comma list: multiple fonts to use if first font doesn't work
    - Use double quotes for fonts with spaces
    - Use fonts.google.com to find free fonts to use
  - text-align
    - left / right / center / justify
  