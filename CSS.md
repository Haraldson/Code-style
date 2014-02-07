# CSS

## Example code

```css
body {
    font: 12px/1 "Font Name", FontName, sans-serif;
    background: #fff url(/path/to/file.png) 50% 0 no-repeat;
}

h1,
h2 {
    text-transform: uppercase;
    font-weight: bold;
}

.user-quote { font-style: italic; }
```

### Line breaks
* Each selector on their own line
* Opening brace `{` on the same line as the (last) selector
* One property/value pair per line
* Closing brace `}` on its own line
* One empty line before the next block of styles
* **Blocks consisting of only one property/value pair are allowed to be one-liners**

### Formatting strings
* Fonts with spaces in their names should be enclosed in double quotes
* References to files should not be enclosed in any quotes

### Saving the world’s forests
* Zero is zero; specifying any unit for zero makes no sense – just `0`, please
* Use shorthand where possible (if you don’t know the shorthand for a given property, it’s not life or death)
* Use shortened HEX codes where possible; `#ffffff` → `#fff` and `#aabbcc` → `#abc`

### Naming
* Give names (classes, IDs, data-attributes...) based on function, not a given look
* No camelCase, no PascalCase; use dashes to separate words in names
