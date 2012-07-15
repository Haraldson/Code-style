CSS
===

## Example code

```css
body {
    font: 12px/1 "Font Name", FontName, sans-serif;
    background: url(/path/to/file.png) 50% 0 no-repeat;
}

h1,
h2 {
    property: value;
    background: #000;
}

h3 { color: red; }
```

### Line breaks
* Each selector on their own line
* Opening brace on the same line as the (last) selector
* One property/value pair per line
* Closing brace on its own line
* Next block after one empty line
* **Blocks consisting of only one property/value pair are allowed be one-liners*

### Formatting strings
* Fonts with spaces in their names should be enclosed in double quotes; "
* References to files should not be enclosed in any quotes

### Saving the forest
* Use shorthand where possible (if you don't know the shorthand for a given property, it's not life or death)
* Use shortened HEX codes where possible; #FFFFFF -> #FFF and #AABBCC -> #ABC

### Naming
* Give names (classes, IDs, data-attributes...) based on function, not a given look
* No camelCase, no PascalCase; use dashes to separate words in names