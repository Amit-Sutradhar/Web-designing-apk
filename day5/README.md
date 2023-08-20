Universal Selector (*):

Selects all elements on the page, regardless of their type or attributes.
Example: * { margin: 0; padding: 0; } resets margins and padding for all elements.
Type Selector (element):

Selects all elements of a specific HTML type.
Example: a { color: blue; } changes the color of all anchor elements to blue.
Class Selector (.class):

Selects elements with a specific class attribute.
Example: .alok { color: rgb(51, 231, 57); } changes the color of elements with the class "alok" to a shade of green.
ID Selector (#id):

Selects a single element with a specific ID attribute.
Example: #siju { background-color: bisque; } sets the background color of the element with the ID "siju" to a light brown.
Descendant Selector (ancestor descendant):

Selects elements that are descendants of a specific ancestor element.
Example: body h2 + p .alok { padding: 10px; } adds padding around elements with class "alok" that are descendants of <h2> + <p> within the <body>.
Adjacent Sibling Selector (element + element):

Selects an element that is directly preceded by another element.
Example: h2 + p { margin-top: 20px; } adds margin to <p> elements that directly follow <h2> elements.
General Sibling Selector (element ~ element):

Selects elements that share the same parent and are siblings of a specific element.
Example: h2 ~ p { font-style: italic; } makes <p> elements siblings of <h2> elements italicized.
Attribute Selector ([attribute], [attribute=value], [attribute~=value]):

Selects elements based on their attribute values.
Example: li[class] { color: chocolate; } changes the color of all <li> elements with any class attribute to a shade of brown.
Pseudo-class Selector (element:pseudo-class):

Selects elements based on a specific state or condition.
Example: a:hover { color: brown; } changes the color of anchor elements when hovered over.
Pseudo-element Selector (element::pseudo-element):

Selects parts of an element, such as the first line or first letter.
Example: p::first-line { font-weight: bold; } makes the first line of all paragraphs bold.
Grouping Selector (selector1, selector2, ...):

Selects multiple elements that match any of the specified selectors.
Example: li[class="two"], li[class~="a"] { color: chartreuse; } changes the color of <li> elements with class "two" or containing "a" to chartreuse.

