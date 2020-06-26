# CSS reset
This is a tiny CSS reset stylesheet.

## CSS properties explanation

### Why revert display
If we don't revert display, all elements will be displayed, including elements that are not meant to be displayed like `style` `script` `title` etc.

### Why border-box
I just think that its easier to think of the element itself as a block instead of thinking of its content as a block.

### default-styles attribute
This is useful for elements that have default styles that might be useful in some cases, but in most cases, it would end up being overridden like `button` `input` `select` etc.

## Known issues
- This will override all styles in `:host` making this approach hard to recommend when working with web components 
