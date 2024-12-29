1. pseudo element ::after
   Pseudo-elements in CSS are used to style specific parts of an element without modifying the actual HTML structure. They allow you to target and style elements' "virtual" parts, such as the first letter of text, the content before or after an element, or other generated content.
2. content must be there and adds new line or text , not thru html
3. its inline by default at the end of content it selcts

29-12-24
display: flex ensures that all direct children of the <ul> (the <li> items) are laid out in a horizontal row.
justify-content: space-around distributes them evenly across the row.
Block-Level Behavior of Links:

The display: block on the <a> tags only affects the clickable area of the links. It makes the link occupy the entire width of its parent <li>, but the parent <li> itself is horizontally aligned by Flexbox.
What’s Actually Happening:

position: absolute
What it does: Removes the dropdown-content from the normal flow of the document and positions it relative to the nearest positioned ancestor (or the viewport if no ancestor is positioned).
This is commonly used for dropdowns to ensure they don’t interfere with the layout of other elements.
When Using position: absolute: The element is removed from this normal flow, and its position is determined using the top, right, bottom, and left properties relative to the nearest positioned ancestor.
