TASK 1

In Flexbox, you can align elements horizontally and vertically using the following properties:

Main Axis (usually horizontal)
justify-content: Aligns items along the main axis (usually horizontally).
Values:

  center – centers items horizontally

  flex-start – aligns items to the start (left in a left-to-right layout)

  flex-end – aligns items to the end (right in a left-to-right layout)

  space-between – distributes items with equal space between them

  space-around – distributes items with equal space around them

Cross Axis (usually vertical)
align-items: Aligns items along the cross axis (usually vertically).
Values:

  center – centers items vertically

  flex-start – aligns items to the top

  flex-end – aligns items to the bottom

  align-self: Allows you to override the alignment of individual items within a flex container (useful for one-off custom alignments).

TASK 2

What is Flexbox?
Flexbox (Flexible Box Layout) is a layout model in CSS designed to lay out elements in a container along a single axis (either horizontally or vertically). It was introduced to solve the common issues that arise when using older layout techniques such as float and inline-block. Flexbox allows you to distribute space within a container, even when the sizes of the items are unknown or dynamic.

  Its purpose in modern web design is to simplify the process of creating responsive layouts, aligning elements, and distributing space in a more flexible and predictable way, especially on   different screen sizes.

  Why is Flexbox Better than Traditional Float or Inline-Block Layouts?
Simplified Alignment:

  In Flexbox, aligning items (horizontally or vertically) is straightforward with properties like justify-content, align-items, and align-self. With float or inline-block, aligning elements can be much trickier, especially when trying to vertically center items.

  No More Clearing Floats:

  With float, you often need to use clear to avoid collapsing containers or overlapping elements. Flexbox eliminates this problem entirely since the flex container automatically adjusts its size to fit its content.

Responsive Design:

  Flexbox is extremely useful for building responsive layouts. It can easily adapt to different screen sizes by distributing space and changing the direction of items (using flex-direction), whereas float and inline-block can require complex media queries to manage layouts properly.

Item Ordering:

  Flexbox allows you to change the visual order of items without altering the HTML structure, using the order property. This is something that float or inline-block cannot achieve without manually rearranging the markup.

Equal and Dynamic Spacing:

  Flexbox allows for dynamic and flexible spacing with properties like flex-grow, flex-shrink, and flex-basis. You can make items grow or shrink depending on the available space, and this is not something you can do easily with float or inline-block.
TASK 3

Flex Container Properties:
display: flex;
Turns an element into a flex container, enabling flexbox layout for its children.

flex-direction
Defines the direction of flex items (row, column, etc.).

justify-content
Aligns flex items along the main axis (e.g., start, center, space-between).

Flex Item Properties:
flex-grow
Specifies how much an item will grow relative to others when extra space is available.

flex-shrink
Controls how much an item will shrink when there is insufficient space.

flex-basis
Sets the initial size of a flex item before growing or shrinking.



TASK 4

The flex shorthand property combines flex-grow, flex-shrink, and flex-basis into one line.

Values:
flex-grow: How much an item can grow (default 0).

flex-shrink: How much an item can shrink (default 1).

flex-basis: The initial size of the item (default auto).

It can take any combination of these values.
