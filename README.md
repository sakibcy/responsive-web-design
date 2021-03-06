<img src="./images/responsive-web-design.png" />

<br /><br />

- [Normalize Css](https://github.com/sakibcy/responsive-web-design#normalize-css)
- [Box Model](https://github.com/sakibcy/responsive-web-design#box-model)
- [Position Property](https://github.com/sakibcy/responsive-web-design#position-property)
- [Which to use? Flexbox or Grid?](https://github.com/sakibcy/responsive-web-design#which-to-use-flexbox-or-grid)

- ## [Flexbox](https://github.com/sakibcy/responsive-web-design#flexbox)

  - [Flexbox Architecture](https://github.com/sakibcy/responsive-web-design/#flexbox-architecture)
  - [Flexbox Chart](https://github.com/sakibcy/responsive-web-design/#flexbox-chart)
  - #### Property
    - [Start using Flex](https://github.com/sakibcy/responsive-web-design#star-using-flex)
    - [flex-dierection](https://github.com/sakibcy/responsive-web-design#flex-direction-property)
    - [flex-wrap](https://github.com/sakibcy/responsive-web-design#flex-wrap)
    - [flex-flow](https://github.com/sakibcy/responsive-web-design#flex-flow)
    - [justify-content](https://github.com/sakibcy/responsive-web-design#justify-content-property)
    - [text-align](https://github.com/sakibcy/responsive-web-design#text-align)
    - [align-content](https://github.com/sakibcy/responsive-web-design#align-content-property)
    - [place-content](https://github.com/sakibcy/responsive-web-design#place-content)
    - [align-items](https://github.com/sakibcy/responsive-web-design#align-items-property)
    - [align-self](https://github.com/sakibcy/responsive-web-design#align-self-property)
    - [Order Property](https://github.com/sakibcy/responsive-web-design#the-order-property)
    - [grid (grid-gap)](https://github.com/sakibcy/responsive-web-design#gap-grid-gap)
    - [flex-grow](https://github.com/sakibcy/responsive-web-design#flex-grow)
    - [flex-shrink](https://github.com/sakibcy/responsive-web-design#flex-shrink)
    - [flex-basis](https://github.com/sakibcy/responsive-web-design#flex-basis)
    - [flex-shorthand](https://github.com/sakibcy/responsive-web-design#flex-shorthand)

- ## [Grid](https://github.com/sakibcy/responsive-web-design#grid)

  - [Grid Architecture](https://github.com/sakibcy/responsive-web-design#grid-architecture)
  - [Grid Chart](https://github.com/sakibcy/responsive-web-design#grid-chart)
  - [Start using Grid](https://github.com/sakibcy/responsive-web-design#start-using-grid)
  - [Grid Parent](https://github.com/sakibcy/responsive-web-design#grid-parent)

    - [grid-template-columns](https://github.com/sakibcy/responsive-web-design#grid-template-columns)
    - [grid-template-rows](https://github.com/sakibcy/responsive-web-design#grid-template-rows)
    - [grid-template](https://github.com/sakibcy/responsive-web-design#grid-template)
    - [grid-template-areas](https://github.com/sakibcy/responsive-web-design#grid-template-areas)
      - [grid-area (children)](https://github.com/sakibcy/responsive-web-design#grid-area)
    - [column-gap](https://github.com/sakibcy/responsive-web-design#column-gap)
    - [row-gap](https://github.com/sakibcy/responsive-web-design#row-gap)
    - [justify-items](https://github.com/sakibcy/responsive-web-design#justify-items)
    - [justify-content](https://github.com/sakibcy/responsive-web-design#justify-content)
    - [align-items](https://github.com/sakibcy/responsive-web-design#align-items)
    - [align-content](https://github.com/sakibcy/responsive-web-design#align-content)
    - [place-items](https://github.com/sakibcy/responsive-web-design#place-items)
    - [place-content](https://github.com/sakibcy/responsive-web-design#place-content)

  - [Grid Children](https://github.com/sakibcy/responsive-web-design#grid-children)
    - [grid-area](https://github.com/sakibcy/responsive-web-design#grid-area)
    - [grid-column-start, grid-column-end](https://github.com/sakibcy/responsive-web-design#grid-column-start---grid-column-end)
    - [grid-column](https://github.com/sakibcy/responsive-web-design#grid-column)
    - [grid-row-start, grid-row-end](https://github.com/sakibcy/responsive-web-design#grid-row-start---grid-row-end)

- ## [Media Queries](https://github.com/sakibcy/responsive-web-design#media-queries)

  - [Css Media Query Syntex](https://github.com/sakibcy/responsive-web-design#css-media-query-syntax)
  - [min-width & max-width](https://github.com/sakibcy/responsive-web-design#min-width--max-width)
  - [max-width](https://github.com/sakibcy/responsive-web-design#max-width)
  - [min-width](https://github.com/sakibcy/responsive-web-design#min-width)
  - [desktop first approach vs mobile first approach](https://github.com/sakibcy/responsive-web-design#desktop-first-approach-vs-mobile-first-approach)

- ## [Css Units](https://github.com/sakibcy/responsive-web-design#css-units)

  - [REM Unit](https://github.com/sakibcy/responsive-web-design#rem-unit)
  - [How to change the root font-size](https://github.com/sakibcy/responsive-web-design#how-to-change-the-root-font-size)
  - [How to Make Responsive Websites with REM Units](https://github.com/sakibcy/responsive-web-design#how-to-make-responsive-websites-with-rem-units)
  - [EM Unit](https://github.com/sakibcy/responsive-web-design#em-units)
  - [VW unit - viewport width](https://github.com/sakibcy/responsive-web-design#vw-unit---viewport-width)
  - [VH unit - viewport height](https://github.com/sakibcy/responsive-web-design#vh-unit---viewport-height)

- ### [Css Articles](https://github.com/sakibcy/responsive-web-design#css-articles)

- ### [Resources From](https://github.com/sakibcy/responsive-web-design#resources-from-1)

<br /><br />

# Normalize Css

Browsers apply styles to elements before you've written any CSS at all, and sometimes those styles vary. <br />
Normalizing your CSS lets you rest assured, knowing that you have the same base layer of styles applied across all browsers. It should be noted that I am talking about normalization and not resetting.

### [download the css file from here and put it on your project](https://github.com/necolas/normalize.css/)

<br /><br />

# Box Model

<img src="./images/box-model.png" width="450px" />
<br />

### We shoud use

- `margin` for separating elements
- `padding` for giving space inside element

<br /><br />

# Position Property

The position property specifies the type of positioning method used for an element\
There are five different position values:

- [static](https://github.com/sakibcy/responsive-web-design#static)
- [relative](https://github.com/sakibcy/responsive-web-design#relative)
- [fixed](https://github.com/sakibcy/responsive-web-design#fixed)
- [absolute](https://github.com/sakibcy/responsive-web-design#absolute)
- [sticky](https://github.com/sakibcy/responsive-web-design#sticky)

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the `position` property is set first. They also work differently depending on the position value.

## Static

HTML elements are positioned static by default.\
Static positioned elements are not affected by the top, bottom, left, and right properties.\
An element with `position: static;` is not positioned in any special way; it is always positioned `according to the normal flow of the page`.

## Relative

An element with `position: relative;` is positioned relative to its normal position.\
Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

## Fixed

An element with `position: fixed;` is positioned relative to the viewport,\
which means `it always stays in the same place even if the page is scrolled`.\
The top, right, bottom, and left properties are used to position the element.\
A fixed element does not leave a gap in the page where it would normally have been located.

## Absolute

An element with `position: absolute;` is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).\
However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.\
`Note:` Absolute positioned elements are removed from the normal flow, and can overlap elements.

## Sticky

An element with `position: sticky;` is positioned based on the user's scroll position.\
A sticky element toggles between `relative` and `fixed`, depending on the scroll position.\
It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

<br /><br />

## Which to use? Flexbox or Grid?

CSS Grid is a multi-dimension layout module, which means that it has columns and rows. Flexbox can lay out its child items either as columns or rows, but not both

<img src="./images/grid-vs-flexbox.png" width="700px" />

<br /><br />

Ask yourself those questions:

- How the component child items are displayed? Inline or as columns and rows?
- How the component is expected to work on various screen sizes?

Most of the time, if the component you are viewing has `all of its child items displayed inline`, then most probably `flexbox is the best solution here`. Consider the following example:

<img src="./images/decide-1.png" width="700px" />

However, if you see columns and rows, then CSS grid is the solution for your case.

<img src="./images/decide-2.png" width="700px" />

### To learn more read this article ???? [Grid for layout, Flexbox for components](https://ishadeed.com/article/grid-layout-flexbox-components/)

<img src="./images/parent-childern.png" width="700px" />

<br /><br /><br />

# FlexBox

When you're building a house, you need a blueprint. In the same way, we need a blueprint when we're making websites. And Flexbox is the blueprint.

The Flexbox model allows us to layout the content of our website. Not only that, it helps us create the structures needed for creating responsive websites for multiple devices.

- [Flexbox Architecture](https://github.com/sakibcy/responsive-web-design/#flexbox-architecture)
- [Flexbox Chart](https://github.com/sakibcy/responsive-web-design/#flexbox-chart)
- #### Property
  - [Start using Flex](https://github.com/sakibcy/responsive-web-design#star-using-flex)
  - [flex-dierection](https://github.com/sakibcy/responsive-web-design#flex-direction-property)
  - [flex-wrap](https://github.com/sakibcy/responsive-web-design#flex-wrap)
  - [flex-flow](https://github.com/sakibcy/responsive-web-design#flex-flow)
  - [justify-content](https://github.com/sakibcy/responsive-web-design#justify-content-property)
  - [text-align](https://github.com/sakibcy/responsive-web-design#text-align)
  - [align-content](https://github.com/sakibcy/responsive-web-design#align-content-property)
  - [place-content](https://github.com/sakibcy/responsive-web-design#place-content)
  - [align-items](https://github.com/sakibcy/responsive-web-design#align-items-property)
  - [align-self](https://github.com/sakibcy/responsive-web-design#align-self-property)
  - [Order Property](https://github.com/sakibcy/responsive-web-design#the-order-property)
  - [grid (grid-gap)](https://github.com/sakibcy/responsive-web-design#gap-grid-gap)
  - [flex-grow](https://github.com/sakibcy/responsive-web-design#flex-grow)
  - [flex-shrink](https://github.com/sakibcy/responsive-web-design#flex-shrink)
  - [flex-basis](https://github.com/sakibcy/responsive-web-design#flex-basis)
  - [flex-shorthand](https://github.com/sakibcy/responsive-web-design#flex-shorthand)

<br /><br />

## Flexbox Architecture

<img src='./images/flexBoxArchitecture.png' width="700px" />

## Flexbox Chart

<img src='./images/flexBoxChart.png' width="700px" />

<img src='./images/flexBoxProperty.png' width="500px" />

<br /><br />

# Star using Flex

For start using flex first declare:

```css
display: flex;
```

<br /><br />

## flex-direction property

This property allows us to set the direction and orientation in which our flex-items should be distributed inside the flex-container.

<img src='./images/flexDirectionRow.png' width='400px' />

<img src='./images/flexDirectionColumn.png' width="400px"/>

<br /><br />

## flex-wrap

This property helps you set the number of flex-items you want in a line or row.

<img src="./images/flex-warp.png" width="400px" />

<br /><br />

## flex-flow

This is the shorthand for the flex-direction and flex-wrap properties:

<img src="./images/flex-flow.png" width="400px"/>

<br /><br />

## justify-content property

This property arranges flex-items along the MAIN AXIS inside the flex-container.

<img src='./images/justifyContent.png' width="400px" />

<img src='./images/justifyContentSpace.png' width="400px" />

<br /><br />

## text-align

Arrange text to left, center, right, start, end

<img src="./images/text-align.png" />

<br /><br />

## align-content property

This property arranges flex-items along the CROSS AXIS inside the flex-container. This is similar to justify-content.
Please note that without the `flex-wrap` property, this property doesn't work. Here's a demo:

<img src='./images/alignContent.png' width="400px" />

<img src='./images/alignContentSpace.png' width="400px" />

<br /><br />

## place-content

This is the shorthand for the align-content and justify-content properties:

<img src='./images/placeContent.png' width="400px" />

<br /><br />

## align-items property

This property distributes Flex-items along the `Cross Axis`.

<img src='./images/alignItem.png' width="400px" />

<br /><br />

## align-self property

This property works on the child classes. It positions the selected item along the Cross Axis.

<img src='./images/alignSelf.png' width="400px" />

In total we have 6 values:

- flex-start
- flex-end
- center
- baseline
- stretch
- auto

<br /><br />

## The order property

In addition to reversing the order in which flex items are visually displayed, you can target individual items and change where they appear in the visual order with the `order` property.

<img src="./images/order-property.png" width="500px" />

<br /><br />

## gap (grid-gap)

The gap CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for row-gap and column-gap.

```css
gap: 10px;
```

<img src="./images/gap.png" width="532px" height="349px" />

<br /><br />

## flex - grow | shrink | wrap | basis properties

The properties will work when we resize the window.

## flex-basis

The initial size of a flex item\
This is similar to adding width to a flex-item, but only more flexible. flex-basis: 10em, for example, will set the initial size of a flex-item to 10em. Its final size will be based on the available space, flex-grow, and flex-shrink.

## flex-grow

This property grows the size of a flex-item based on the width of the flex-container.

## flex-shrink

This property helps a flex item shrink based on the width of the flex-container. It's the opposite of flex-grow.

<img src="./images/flex-grow.png" width="500px" />

### Please note that flex-grow and flex-shrink work on child classes. So, we will target all our boxes like this:

```css
.box-1 {
  flex-grow: 1;
}
.box-2 {
  flex-grow: 5;
}
.box-1 {
  flex-grow: 1;
}
```

<br /><br />

## flex shorthand

This is the shorthand for the flex-grow, flex-shrink and flex-basis properties combined.

<img src="./images/flex-shorthand.png" width="500px" />

<br /><br /><br />

# Grid

### The Grid items [Contents] are distributed along the main axis and cross axis.

- [Grid Architecture](https://github.com/sakibcy/responsive-web-design#grid-architecture)
- [Grid Chart](https://github.com/sakibcy/responsive-web-design#grid-chart)
- [Start using Grid](https://github.com/sakibcy/responsive-web-design#start-using-grid)
- [Grid Parent](https://github.com/sakibcy/responsive-web-design#grid-parent)

  - [grid-template-columns](https://github.com/sakibcy/responsive-web-design#grid-template-columns)
  - [grid-template-rows](https://github.com/sakibcy/responsive-web-design#grid-template-rows)
  - [grid-template](https://github.com/sakibcy/responsive-web-design#grid-template)
  - [grid-template-areas](https://github.com/sakibcy/responsive-web-design#grid-template-areas)
    - [grid-area (children)](https://github.com/sakibcy/responsive-web-design#grid-area)
  - [column-gap](https://github.com/sakibcy/responsive-web-design#column-gap)
  - [row-gap](https://github.com/sakibcy/responsive-web-design#row-gap)
  - [justify-items](https://github.com/sakibcy/responsive-web-design#justify-items)
  - [justify-content](https://github.com/sakibcy/responsive-web-design#justify-content)
  - [align-items](https://github.com/sakibcy/responsive-web-design#align-items)
  - [align-content](https://github.com/sakibcy/responsive-web-design#align-content)
  - [place-items](https://github.com/sakibcy/responsive-web-design#place-items)
  - [place-content](https://github.com/sakibcy/responsive-web-design#place-content)

- [Grid Children](https://github.com/sakibcy/responsive-web-design#grid-children)
  - [grid-area](https://github.com/sakibcy/responsive-web-design#grid-area)
  - [grid-column-start, grid-column-end](https://github.com/sakibcy/responsive-web-design#grid-column-start---grid-column-end)
  - [grid-column](https://github.com/sakibcy/responsive-web-design#grid-column)
  - [grid-row-start, grid-row-end](https://github.com/sakibcy/responsive-web-design#grid-row-start---grid-row-end)

<br /><br />

## Grid Architecture

<img src="./images/grid-architecture.png" width="500px" />

<img src="./images/grid-template-cloumns-rows.png" width="500px" />

<br /><br />

## Grid Chart

Grid properties are divided into:

- Parent properties
- Child Properties

Note: The `red colored text` denotes the `shorthand properties`:

<img src="./images/grid-parent.png" width="500px" />

<img src="./images/grid-child.png" width="500px" />

<br /><br />

# Start using Grid

to use grid on items first declare it:

```css
display: grid;
```

<br /><br /><br />

# Grid Parent

## grid-template-columns

You use this property to define `the number and width of columns`.

- You can either individually set the width of each column,
- or set a uniform width for all columns using the `repeat()` function.

<img src="./images/grid-template-columns.png" width="500px" />
<img src="./images/grid-template-columns-repeat.png" width="500px" />

<img src="./images/grid-template-columns-view.png" width="500px" />

### Note:

- The pixel values will be an exact measurement. The "auto" keyword will cover the available space.
- If you use `fr (fraction unit)` as a unit of measurement, all the boxes will be equal in size.
- for `repeat()` you can use
  ```css
  grid-template-columns: repeat(3, 1fr);
  ```
  ### or
  ```css
  grid-template-columns: repeat(3, 100px);
  ```

<br /><br />

## grid-template-rows

define the `number and height of rows`. You can either individually set the height of each row, or set a uniform height for all rows using the repeat() function.

<img src="./images/grid-template-rows.png" width="500px" />

<img src="./images/grid-template-rows-repeat.png" width="500px" />

<img src="./images/grid-template-rows-view.png" width="500px" />

<br /><br />

## grid-template

<img src="./images/grid-template.png" />

This is the shorthand of 2 properties:

- grid-template-rows
- grid-template-columns

### An example

```css
grid-template-rows: 100px 100px;
grid-template-columns: 200px 200px;

/* The shorthand */
grid-template: 100px 100px / 200px 200px;
```

<br /><br />

## grid-template-areas

use this property to specify the amount of space a grid cell should carry in terms of columns and rows across the parent container.

<img src="./images/grid-template-areas.png" width="500px" />

Call it the blueprint(template) of our layout????

<img src="./images/grid-template-areas-blueprint.png" width="500px" />

- `grid-template-areas:`
  The parent property that will create the blueprint
- `grid-area:` the child property that will follow the blueprint.

### First, create the blueprint

Like this ???? inside the `parent .container` class:

```css
.container {
  display: grid;
  gap: 20px;
  height: 100vh;

  grid-template-areas:
    "A A A A   A A A A   A A A A"
    "B B B B   B B B B   B B C C"
    "B B B B   B B B B   B B C C";
}
```

<br /><br />

## grid-area

<img src="./images/grid-template-areas-parent.png" width="500px" />

<img src="./images/grid-template-areas-children.png" width="500px" />

<br />

### Implement the blueprint

Target all our `child .box-\*` classes and set the values like this

```css
.box-1 {
  grid-area: A;
}
.box-2 {
  grid-area: B;
}
.box-3 {
  grid-area: C;
}
```

<br /><br />

## column-gap

`column-gap` works with `grid-template-columns`

<img src="./images/column-gap.png" width="500px" />

<br /><br />

## row-gap

`row-gap` works with `grid-template-rows`

<img src="./images/row-gap.png" width="500px" />

<br /><br />

## justify-items

You use this property to `position grid-items (children) inside grid containers along the X-Axis [Main Axis]`. The 4 values are ????
Alt Text

<img src="./images/justify-items-start.png" width="500px" />

<img src="./images/justify-items-center.png" width="500px" />

<br /><br />

## justify-content

You use this property to `position your grid [Basically everything] inside the grid container along the X-Axis [Main Axis]`. The 7 values are ????

<img src="./images/justify-content-start.png" width="500px"/>

<img src="./images/justify-content-space.png" width="500px" />

<br /><br />

## align-items

use this property to `position grid-items (children) inside the grid container along the Y-Axis [Cross Axis]`.

 <img src="./images/align-items.png" width="500px" />

<br /><br />

## align-content

use this property to `position our grid [Basically everything] inside the grid container along the Y-Axis [Cross Axis]`.

<img src="./images/align-content-start.png" width="500px" />

<img src="./images/align-content-space.png" width="500px" />

<br />

## place-items

short form of

- justify-items
- align-items

## place-content

short form of

- justify-content
- align-content

<br /><br /><br />

# Grid Children

<img src="./images/grid-scale.png" width="500px" />

The illustration below ???? shows the start and end points of rows and columns of a single cell.

<img src="./images/grid-column-row.png" width="500px" />

<br /><br />

## grid-column-start - grid-column-end

join multiple Columns together\
Write this code in your CSS:

```css
.container {
  display: grid;
  gap: 20px;
  height: 100vh;

  grid-template-columns: repeat(12, 1fr);
  grid-template-rows: repeat(12, 1fr);
}
```

The result looks like this:

<img src="./images/grid-columns-start.png" />

As we are dealing with child properties, we need to target our `.box-*` classes like this:

```css
.box-1 {
}
.box-2 {
}
.box-3 {
}
.box-4 {
}
```

The default scale of every `.box-*` class is:

```css
grid-column-start: 1;
grid-column-end: 10;

/* The shorthand -> */
grid-column: 1 / 10;
/* or */
grid-column: span 10;
```

The result looks like this: ????

<img src="./images/grid-column-result.png" width="400px" />

<br /><br />

## grid-column

short form of

- grid-column-start
- grid-column-end

```css
grid-column-start: 1;
grid-column-end: 2;

/* The shorthand -> */
grid-column: 1 / 10;
/* or */
grid-column: span 10;
```

<br /><br />

## grid-row-start - grid-row-end

use these two properties to join multiple `ROWS` together.

```css
.box-1 {
  grid-row-start: 1;
  grid-row-end: 11;

  /* shorthand */
  grid-row: 1/11;
}
```

<img src="./images/grid-row.png" width="400px" />

<br /><br /><br />

# Media Queries

- [Css Media Query Syntex](https://github.com/sakibcy/responsive-web-design#css-media-query-syntax)
- [min-width & max-width](https://github.com/sakibcy/responsive-web-design#min-width--max-width)
- [max-width](https://github.com/sakibcy/responsive-web-design#max-width)
- [min-width](https://github.com/sakibcy/responsive-web-design#min-width)
- [desktop first approach vs mobile first approach](https://github.com/sakibcy/responsive-web-design#desktop-first-approach-vs-mobile-first-approach)

<br /><br />

### CSS Media Query Syntax

Here's the syntax of a Media Query:

```css
@media screen and (max-width: 768px) {
  .container {
    //Your code's here
  }
}
```

<img src="./images/media-query-syntex.png" width="400px" />

<br />

### We declare media queries with `@media` first.

### `@media type`

<img src="./images/media-type.png" width="400px" />

the media type, min-width, and max-width functions are basically conditions we are giving to the browser. We don't write the "and" operator if we have one condition. Like this ->

```css
@media screen {
  .container {
    // Your code here
  }
}
```

We write the and operator if we have two conditions, like this:

```css
@media screen and (max-width: 768px) {
  .container {
    // Your code here
  }
}
```

You can also skip the media type and work with just min-width & max-width, like this:

```css
//Targeting screen sizes between 480px & 768px

@media (min-width: 480px) and (max-width: 768px) {
  .container {
    // Your code here
  }
}
```

If you have three conditions or more, you can use a comma, like this:

```css
//Targeting screen sizes between 480px & 768px

@media screen, (min-width: 480px) and (max-width: 768px) {
  .container {
    // Your code here
  }
}
```

<br /><br />

## min-width & max-width

- [max-width](https://github.com/sakibcy/responsive-web-design#max-width)
- [min-width](https://github.com/sakibcy/responsive-web-design#min-width)
- [ Media Queries for Standard Devices ](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

there's no such thing as a standard screen break-point guide because there are so many screen sizes on the market

<img src="./images/bootstrap5-break-point.png" width="400px" />

<br /><br />

## max-width

Using this function, we are creating a boundary. This will work as long as we are inside the boundary. Here's a sample ????

Our Boundary is 500px:\
Notice how the light purple color gets Disabled when we hit above 500px.

<img src="./images/max-width.gif" width="500px" />
<img src="./images/max-width-img.png" width="400px" />

<br />

## min-width:

We are also creating a boundary here. But this will work if we go outside the boundary. Here's a sample: ????

Our boundary is 500px:\
Notice how the light purple color gets enabled after we hit above 500px width.

<img src="./images/min-width.gif" width="400px" />
<img src="./images/min-width-img.png" width="400px" />

<br />

## desktop first approach vs mobile first approach

- `mobile first approach` : min-width
- `desktop first approach` : max-width

<br/><br><br>

# Css Units

- [REM Unit](https://github.com/sakibcy/responsive-web-design#rem-unit)
- [How to change the root font-size](https://github.com/sakibcy/responsive-web-design#how-to-change-the-root-font-size)
- [How to Make Responsive Websites with REM Units](https://github.com/sakibcy/responsive-web-design#how-to-make-responsive-websites-with-rem-units)
- [EM Unit](https://github.com/sakibcy/responsive-web-design#em-units)
- [VW unit - viewport width](https://github.com/sakibcy/responsive-web-design#vw-unit---viewport-width)
- [VH unit - viewport height](https://github.com/sakibcy/responsive-web-design#vh-unit---viewport-height)

<br /><br />

### Absolute unit (fixed)

- `px`

### Relative unit (change on some condition)

- `%` relative to the size of the container
- `vw`, `vh` relative to the viewport
- `em`, `rem` relative to the font size

<br /><br />

### REM, EM, VW, VH are relative units

#### Font using the REM unit

???? Notice font size is changing when we resize the window.

<img src="./images/rem-unit.gif" width="300px" height="300px" />

### pixels are absolute units.

???? Notice that the font size of 50px doesn't change when we resize the window.

<img src="./images/pixel-unit.gif" width="300px" height="300px" />

<br /><br />

## REM Unit

The REM unit depends on the `root element [the HTML element]`. Here's an image to show you how it works:????

<img src='./images/htmlRem.png' width="400px" />

## How to change the root font-size

By default `root fon-size` is `16px`. But you can change it ????

```css
html {
  font-size: 40px; /* Change here */
}

.text {
  font-size: 1rem;
}
```

<br /><br />

## How to Make Responsive Websites with REM Units

Write your styles in rem units instead of the pixels and change the root elements at different breakpoints using media queries.

```css
// large screen

@media (max-width: 1400px) {
  html {
    font-size: 25px;
  }
}

// Tablet screen

@media (max-width: 768px) {
  html {
    font-size: 18px;
  }
}

// Mobile screen

@media (max-width: 450px) {
  html {
    font-size: 12px;
  }
}
```

### Now, set the .text class to 3 rem units, like this:

```css
.text {
  font-size: 3rem;
}
```

And here's the result: ????

<img src="./images/rem-web.gif" width="500px" />

Here are the calculations:

- For the large screen -> 3 rem \* 25px = 75px
- For tablet screen -> 3 rem \* 18px = 54px
- For mobile screen -> 3 rem \* 12px = 36px
- Default setting -> 3rem \* 16px = 48px

<br /><br /><br />

## EM Units

### Don't use the EM unit ???????

Using the EM unit is not worth the effort because:

- you have a high chance of making a calculation error
- you have to write a lot of code in media queries while trying to make the website responsive on all screen sizes
- it's too time-consuming.

The EM unit is the same as the REM unit but it depends on the parent font size. Here's a demo. ????

Note: make sure you remove all the media queries.

```css
html {
  font-size: 16px;
}

.text {
  font-size: 3em;
}

/** Calculations
  font-size should be 
  3 em * 16px = 48px
**/
```

Now, let's try adding 3em padding to the .text class.

```css
html {
  font-size: 16px;
}

.text {
  font-size: 3em;
  padding: 3em;
}

/** Calculations
text    => 3em * 16px = 48px
padding => 3em * 3em * 16px = 144px
**/
```

Instead of being 48px of padding, we are getting 144px padding. As you can see, it is getting multiplied by the previous number.

<img src="./images/em.png" width="400px" />

Here's the computed part from the developer console: ????

<img src="./images/em-padding.png" width="400px" />

<br /><br />

## VW unit - viewport width

It works like the percentage unit. Specifying `50vw` is equivalent to occupying `50% of entire visible screen width`

```css
.text {
  display: none;
}

.box {
  width: 50vw;

  height: 300px;
  /* display: none; */
}
```

If you look carefully, you can see that 50vw means 50%, which will cover half of the entire screen width.

<img src="./images/50vw.png" width="400px" />

resizing box which is 50vw in size. It is taking 50% of entire screen even if we resize the window.

<img src="./images/resizevw.gif" width="500px" />

<br /><br />

## VH unit - viewport height

It works like the percentage unit as well. Specifying `50vh` is equivalent to `occupying 50% of entire visible screen height`

```css
.text {
  display: none;
}

.box {
  width: 300px;

  height: 50vh;
  /* display: none; */
}
```

And here's the result: ????

<img src="./images/50vh.png" width="400px" />

As you can see, it will always cover that much space even if we resize the window.

<img src="./images/resize-vh.gif" width="500px" >

<br /><br /><br />

# Css Articles

- [Learn CSS Units ??? Em, Rem, VH, and VW with Code Examples ??????](https://www.freecodecamp.org/news/learn-css-units-em-rem-vh-vw-with-code-examples/)
- [Flexbox Tutorial with Flexbox Properties Cheat Sheet ???????](https://www.freecodecamp.org/news/css-flexbox-tutorial-with-cheatsheet/)
- [Grid for layout, Flexbox for components](https://ishadeed.com/article/grid-layout-flexbox-components/)
- [ Media Queries for Standard Devices ](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
- [CSS Notes for Professionals book](https://goalkicker.com/CSSBook/)

<br /><br /><br />

# Resources from

- [Joy Shaheb](https://www.freecodecamp.org/news/author/joy/)
- [Ahmad Shadeed](https://ishadeed.com/article/grid-layout-flexbox-components/)
- [W3Schools.com](https://www.w3schools.com)
