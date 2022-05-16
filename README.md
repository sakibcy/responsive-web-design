# Responsive Web Design
* [Css Units](https://github.com/sakibcy/responsive-web-design#css-units)
* [Flexbox](https://github.com/sakibcy/responsive-web-design#flexbox)
* [Css Articles](https://github.com/sakibcy/responsive-web-design#css-articles)



## Css Units
<img src='./readMeImages/htmlRem.png' />


## FlexBox
When you're building a house, you need a blueprint. In the same way, we need a blueprint when we're making websites. And Flexbox is the blueprint.

The Flexbox model allows us to layout the content of our website. Not only that, it helps us create the structures needed for creating responsive websites for multiple devices. 
* [Flexbox Architecture](https://github.com/sakibcy/responsive-web-design#flexbox-architecture)
* [Flexbox Chart](https://github.com/sakibcy/responsive-web-design#flexbox-chart)


## Flexbox Architecture
<img src='./readMeImages/flexBoxArchitecture.png' />

## Flexbox Chart
<img src='./readMeImages/flexBoxChart.png' />
<img src='./readMeImages/flexBoxProperty.png' />

## flex-direction property
This property allows us to set the direction and orientation in which our flex-items should be distributed inside the flex-container.
<img src='./readMeImages/flexDirectionRow.png' />
<img src='./readMeImages/flexDirectionColumn.png' />

## justify-content property
This property arranges flex-items along the MAIN AXIS inside the flex-container.
<img src='./readMeImages/justifyContent.png' />
<img src='./readMeImages/justifyContentSpace.png' />


## align-content property
This property arranges flex-items along the CROSS AXIS inside the flex-container. This is similar to justify-content.
Please note that without the ```flex-wrap``` property, this property doesn't work. Here's a demo:
<img src='./readMeImages/alignContent.png' />
<img src='./readMeImages/alignContentSpace.png' />

## place-content
This is the shorthand for the align-content and justify-content properties:
<img src='./readMeImages/placeContent.png' />


## align-items property
This property distributes Flex-items along the ```Cross Axis```.
<img src='./readMeImages/alignItem.png' />


## align-self property
This property works on the child classes. It positions the selected item along the Cross Axis.
<img src='./readMeImages/alignSelf.png' />
In total we have 6 values:
* flex-start
* flex-end
* center
* baseline
* stretch
* auto

## The order property

In addition to reversing the order in which flex items are visually displayed, you can target individual items and change where they appear in the visual order with the ```order``` property.

The ```order``` property is designed to lay the items out in ordinal groups. What this means is that items are assigned an integer that represents their group. The items are then placed in the visual order according to that integer, lowest values first. If more than one item has the same integer value, then within that group the items are laid out as per source order.

As an example, I have 5 flex items, and assign order values as follows:

* Source item 1: order: 2
* Source item 2: order: 3
* Source item 3: order: 1
* Source item 4: order: 3
* Source item 5: order: 1

These items would be displayed on the page in the following order:

* Source item 3: order: 1
* Source item 5: order: 1
* Source item 1: order: 2
* Source item 2: order: 3
* Source item 4: order: 3

Items have a number showing their source order which has been rearranged.

<img src="./readMeImages/order-property.png" />

You can play around with the values in this live example below and see how that changes the order. Also, try changing flex-direction to row-reverse and see what happens — the start line is switched so the ordering begins from the opposite side.

## gap (grid-gap)

The gap CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for row-gap and column-gap.
<img src="./readMeImages/gap.png" />

## Css Articles
* [Learn CSS Units – Em, Rem, VH, and VW with Code Examples ✨✨](https://www.freecodecamp.org/news/learn-css-units-em-rem-vh-vw-with-code-examples/)
* [Flexbox Tutorial with Flexbox Properties Cheat Sheet 🎖️](https://www.freecodecamp.org/news/css-flexbox-tutorial-with-cheatsheet/)
