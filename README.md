<img src="./images/responsive-web-design.png" />

<br /><br />

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

- ## [Css Units](https://github.com/sakibcy/responsive-web-design#css-units)
  - [REM Unit](https://github.com/sakibcy/responsive-web-design#rem-unit)
  - [How to change the root font-size](https://github.com/sakibcy/responsive-web-design#how-to-change-the-root-font-size)
  - [How to Make Responsive Websites with REM Units](https://github.com/sakibcy/responsive-web-design#how-to-make-responsive-websites-with-rem-units)
  - [EM Unit](https://github.com/sakibcy/responsive-web-design#em-units)
  - [VW unit - viewport width](https://github.com/sakibcy/responsive-web-design#vw-unit---viewport-width)
  - [VH unit - viewport height](https://github.com/sakibcy/responsive-web-design#vh-unit---viewport-height)
- ### [Css Articles](https://github.com/sakibcy/responsive-web-design#css-articles)
- ### [Resources From](https://github.com/sakibcy/responsive-web-design#resources-from)

<br /><br />

## Which to use? Flexbox or Grid?

CSS Grid is a multi-dimension layout module, which means that it has columns and rows. Flexbox can lay out its child items either as columns or rows, but not both.

<img src="./images/grid-vs-flexbox.png" />

<br /><br />

Ask yourself those questions:

- How the component child items are displayed? Inline or as columns and rows?
- How the component is expected to work on various screen sizes?

Most of the time, if the component you are viewing has `all of its child items displayed inline`, then most probably `flexbox is the best solution here`. Consider the following example:

<img src="./images/decide-1.png" />

However, if you see columns and rows, then CSS grid is the solution for your case.

<img src="./images/decide-2.png">

### To learn more read this article 👉 [Grid for layout, Flexbox for components](https://ishadeed.com/article/grid-layout-flexbox-components/)

<img src="./images/parent-childern.png" />

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

<img src='./images/flexBoxArchitecture.png' />

## Flexbox Chart

<img src='./images/flexBoxChart.png' />
<img src='./images/flexBoxProperty.png' />

<br /><br />

# Star using Flex

For start using flex first declare:

```css
display: flex;
```

<br /><br />

## flex-direction property

This property allows us to set the direction and orientation in which our flex-items should be distributed inside the flex-container.
<img src='./images/flexDirectionRow.png' />
<img src='./images/flexDirectionColumn.png' />

<br /><br />

## flex-wrap

This property helps you set the number of flex-items you want in a line or row.
<img src="./images/flex-warp.png" />

<br /><br />

## flex-flow

This is the shorthand for the flex-direction and flex-wrap properties:

<img src="./images/flex-flow.png" />

<br /><br />

## justify-content property

This property arranges flex-items along the MAIN AXIS inside the flex-container.
<img src='./images/justifyContent.png' />
<img src='./images/justifyContentSpace.png' />

<br /><br />

## text-align

Arrange text to left, center, right, start, end

<img src="./images/text-align.png" />

<br /><br />

## align-content property

This property arranges flex-items along the CROSS AXIS inside the flex-container. This is similar to justify-content.
Please note that without the `flex-wrap` property, this property doesn't work. Here's a demo:
<img src='./images/alignContent.png' />
<img src='./images/alignContentSpace.png' />

<br /><br />

## place-content

This is the shorthand for the align-content and justify-content properties:
<img src='./images/placeContent.png' />

<br /><br />

## align-items property

This property distributes Flex-items along the `Cross Axis`.
<img src='./images/alignItem.png' />

<br /><br />

## align-self property

This property works on the child classes. It positions the selected item along the Cross Axis.
<img src='./images/alignSelf.png' />
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

<img src="./images/order-property.png" />

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

## flex-grow

This property grows the size of a flex-item based on the width of the flex-container.

## flex-shrink

This property helps a flex item shrink based on the width of the flex-container. It's the opposite of flex-grow.

<img src="./images/flex-grow.png" />

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

## flex-basis

This is similar to adding width to a flex-item, but only more flexible. flex-basis: 10em, for example, will set the initial size of a flex-item to 10em. Its final size will be based on the available space, flex-grow, and flex-shrink.

<br /><br />

## flex shorthand

This is the shorthand for the flex-grow, flex-shrink and flex-basis properties combined.

<img src="./images/flex-shorthand.png" />

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

<img src="./images/grid-architecture.png" />

<img src="./images/grid-template-cloumns-rows.png" />

<br /><br />

## Grid Chart

Grid properties are divided into:

- Parent properties
- Child Properties

Note: The `red colored text` denotes the `shorthand properties`:

<img src="./images/grid-parent.png" />

<img src="./images/grid-child.png" />

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

<img src="./images/grid-template-columns.png" />
<img src="./images/grid-template-columns-repeat.png" />

<img src="./images/grid-template-columns-view.png" />

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

<img src="./images/grid-template-rows.png" />

<img src="./images/grid-template-rows-repeat.png" />

<img src="./images/grid-template-rows-view.png" />

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

<img src="./images/grid-template-areas.png" />

Call it the blueprint(template) of our layout👇

<img src="./images/grid-template-areas-blueprint.png" />

- `grid-template-areas:`
  The parent property that will create the blueprint
- `grid-area:` the child property that will follow the blueprint.

### First, create the blueprint

Like this 👇 inside the `parent .container` class:

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

<img src="./images/grid-template-areas-parent.png" />
<img src="./images/grid-template-areas-children.png" />

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

<img src="./images/column-gap.png" />

<br /><br />

## row-gap

`row-gap` works with `grid-template-rows`

<img src="./images/row-gap.png" />

<br /><br />

## justify-items

You use this property to `position grid-items (children) inside grid containers along the X-Axis [Main Axis]`. The 4 values are 👇
Alt Text

<img src="./images/justify-items-start.png" />

<img src="./images/justify-items-center.png" />

<br /><br />

## justify-content

You use this property to `position your grid [Basically everything] inside the grid container along the X-Axis [Main Axis]`. The 7 values are 👇

<img src="./images/justify-content-start.png" />

<img src="./images/justify-content-space.png" />

<br /><br />

## align-items

use this property to `position grid-items (children) inside the grid container along the Y-Axis [Cross Axis]`.

 <img src="./images/align-items.png" />

<br /><br />

## align-content

use this property to `position our grid [Basically everything] inside the grid container along the Y-Axis [Cross Axis]`.

<img src="./images/align-content-start.png" />

<img src="./images/align-content-space.png" />

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

<img src="./images/grid-scale.png" />

The illustration below 👇 shows the start and end points of rows and columns of a single cell.

<img src="./images/grid-column-row.png" />

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

The result looks like this: 👇

<img src="./images/grid-column-result.png" />

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

<img src="./images/grid-row.png" />

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

<img src="./images/media-query-syntex.png" />

<br />

### We declare media queries with `@media` first.

### `@media type`

<img src="./images/media-type.png" />

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

<img src="./images/bootstrap5-break-point.png" />

<br /><br />

## max-width

Using this function, we are creating a boundary. This will work as long as we are inside the boundary. Here's a sample 👇

Our Boundary is 500px:\
Notice how the light purple color gets Disabled when we hit above 500px.

<img src="./images/max-width.gif" />
<img src="./images/max-width-img.png" />

<br />

## min-width:

We are also creating a boundary here. But this will work if we go outside the boundary. Here's a sample: 👇

Our boundary is 500px:\
Notice how the light purple color gets enabled after we hit above 500px width.

<img src="./images/min-width.gif" />
<img src="./images/min-width-img.png" />

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

<br />

### REM, EM, VW, VH are relative units

#### Font using the REM unit

<img src="./images/rem-unit.gif" />

### pixels are absolute units.

👇 Notice that the font size of 50px doesn't change when we resize the window.

<img src="./images/pixel-unit.gif">

<br /><br />

## REM Unit

The REM unit depends on the `root element [the HTML element]`. Here's an image to show you how it works:👇

<img src='./images/htmlRem.png' />

## How to change the root font-size

By default `root fon-size` is `16px`. But you can change it 👇

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

And here's the result: 👇

<img src="./images/rem-web.gif">

Here are the calculations:

- For the large screen -> 3 rem \* 25px = 75px
- For tablet screen -> 3 rem \* 18px = 54px
- For mobile screen -> 3 rem \* 12px = 36px
- Default setting -> 3rem \* 16px = 48px

<br /><br /><br />

## EM Units

### Don't use the EM unit 😵❌

Using the EM unit is not worth the effort because:

- you have a high chance of making a calculation error
- you have to write a lot of code in media queries while trying to make the website responsive on all screen sizes
- it's too time-consuming.

The EM unit is the same as the REM unit but it depends on the parent font size. Here's a demo. 👇

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

<img src="./images/em.png" />

Here's the computed part from the developer console: 👇

<img src="./images/em-padding.png" />

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

<img src="./images/50vw.png" />

resizing box which is 50vw in size. It is taking 50% of entire screen even if we resize the window.

<img src="./images/resizevw.gif">

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

And here's the result: 👇

<img src="./images/50vh.png" />

As you can see, it will always cover that much space even if we resize the window.

<img src="./images/resize-vh.gif">

<br /><br /><br />

# Css Articles

- [Learn CSS Units – Em, Rem, VH, and VW with Code Examples ✨✨](https://www.freecodecamp.org/news/learn-css-units-em-rem-vh-vw-with-code-examples/)
- [Flexbox Tutorial with Flexbox Properties Cheat Sheet 🎖️](https://www.freecodecamp.org/news/css-flexbox-tutorial-with-cheatsheet/)
- [Grid for layout, Flexbox for components](https://ishadeed.com/article/grid-layout-flexbox-components/)
- [ Media Queries for Standard Devices ](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
- [CSS Notes for Professionals book](https://goalkicker.com/CSSBook/)

<br /><br /><br />

# Resources from

- [Joy Shaheb](https://www.freecodecamp.org/news/author/joy/)
- [Ahmad Shadeed](https://ishadeed.com/article/grid-layout-flexbox-components/)
