# CSS Interview Question

## 1). how to add comments on css?

```bash
Simply we need to add inside CSS /*--<css element>--*/
```

## 2). Why do we use pseudo-class?

```bash
a pseudo-class is used to special state of an element.
for example : It can be used to :Style an element when a user mouses over it.
 & Style Visited and unvisited links differently. </span>
```

## 3). How is specificity applied?

```bash
Specificity is the mean by which browsers decide which CSS Property
values are the most relevant to an element and, therefore, will be applies
specificty is based on the matching rules are composed of different sorts of CSS Selectors.
Specificity only applies when the element is targeted by multiple declaration.
for example : If there are two or more css rules that point to the
same  element & Style Visited and unvisited links differently.
```

## 4). What method allows an element to be moved from its current position?

```bash
Translate()
The Translate method allows us to move an element current position.
(according to the parameter given for the X-axis and Y-axis)
i.e :
div {
  transform: translate(50px, 100px);
}
```

## 5). what properties does flex model have?

```bash
The flex property sets the flexible length on flexible item.
if the element is not a flexible item, the flex property has no effect.
The flex property shortand for :
flex-grow
flex-shrink
flex-basis
for instance : .wrapper {
                      width: 500px;
                      display: flex;
                      flex-wrap: wrap;
}
                     .wrapper > div {
                      flex: 1 1 150px;
}

```

## 6). What is the difference between flex and grids?

```bash
Flex : Flex is one dimension layout - either a row or a column
div {
  width: 500px;
  display: flex;
  flex-wrap: wrap;
}
Grid : Grid is two dimension layout - both for row and column at the same time.
div{
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```

## 7). Give an example where we have to use grids and where you have to use flexbox?

```bash
If you are using flexbox and find yourself disabling some of the flexibility,
you probably need to use CSS Grid Layout. An example would be if you are
setting a percentage width on a flex item to make it line up with other
items in a row above. In that case, a grid is likely to be a better choice.

```

## 8). Give an example where you cannot use flexbox, and you can only use grids?

```bash


```

## 9). What are combinators?

```bash
CSS combinators are explaining the relationship between two selectors.
CSS selectors are the patterns used to select the elements for style purpose.A CSS selector
can be a simple selector or a complex selector consisting of more than
 one selector connected using combinators.
There are four types of combinators available in CSS which are discussed below:
Descendant combinator - (" ")
Child combinator - (>)
Adjacent sibling combinator - (+)
General sibling combinator - (~)
```

## 10). What does object-fit do?

```bash
The object-fit CSS property sets how the content of a replaced element, such as an <img> or <video> should be resized
to its container.

Property Values -
fill : This is default. The replaced content is sized to fill the element's content box.
 If necessary, the object will be stretched or squished to fit.
contain : The replaced content is scaled to maintain its aspect ratio while fitting within the element's content box.
cover : 	The replaced content is sized to maintain its aspect ratio while filling the element's entire content box.
The object will be clipped to fit.
none : The replaced content is not resized.
scale-down : The content is sized as if none or contain were specified (would result in a smaller concrete object size).
initial : 	Sets this property to its default value.
inherit : 	Inherits this property from its parent element.

```

## 11). What does rotate do?

```bash
The rotation property rotates a block-level element counterclockwise around a given point defined by the rotation-point property.


```

## 12). What rule can be used to define animations ?

```bash
CSS allows animation of HTML elements without using JavaScript or Flash!
An animation lets an element gradually change from one style to another.
You can change as many CSS properties you want, as many times as you want.

To use CSS animation, you must first specify some keyframes for the animation.

Keyframes hold what styles the element will have at certain times.


Animations Properties :
@keyframes
animation-name
animation-duration
animation-delay
animation-iteration-count
animation-direction
animation-timing-function
animation-fill-mode
animation

```

## 13). What does @media do?

```bash
The @media rule is used in media queries to apply different
 styles for different media types/devices. Media queries can be used to check many things,
 such as: width and height of the viewport. width and height of the device

```
