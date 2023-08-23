
CSS Concepts and Properties
Cascading Style Sheets (CSS)
CSS is a stylesheet language used to describe the presentation of a document written in HTML or XML. It enables you to control the layout, colors, fonts, and other visual aspects of a webpage. In this example, we'll explore several CSS concepts and properties.

1. Specificity and Cascading
CSS uses specificity to determine which styles should be applied when conflicting rules exist. The bff class and the #my-friends ID selectors showcase specificity. The .bff class selector is more specific than the ul li tag selector, allowing it to override properties such as color and font-weight.

2. Inheritance
Inheritance is the process by which certain properties of a parent element are passed down to its children. The font-family property set in the body selector is inherited by all elements within the body, ensuring consistent typography throughout the page.

3. Overflow
The overflow property controls what happens when content overflows the dimensions of an element. In the .overflow-box class, we set overflow: scroll; to display scrollbars when content exceeds the dimensions of the box, allowing users to scroll through the content.

CSS Properties Used
1. font-family
Purpose: Specifies the font for text content.
Example: font-family: Arial, sans-serif;
2. background-color
Purpose: Sets the background color of an element.
Example: background-color: #f0f0f0;
3. color
Purpose: Sets the text color.
Example: color: blueviolet;
4. font-weight
Purpose: Sets the thickness of the text characters.
Example: font-weight: bold;
5. font-size
Purpose: Sets the size of the font.
Example: font-size: 16px;
6. margin
Purpose: Sets the spacing outside an element.
Example: margin: 5px 0;
7. text-transform
Purpose: Controls the capitalization of text.
Example: text-transform: uppercase;
8. list-style
Purpose: Defines the style of list markers (bullets/numbers).
Example: list-style: none;
9. overflow
Purpose: Determines what happens when content overflows an element's dimensions.
Example: overflow: scroll;
