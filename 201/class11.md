# IMAGE IN CSS

1. Center an Image
To center an image, set left and right margin to auto and make it into a block element:

2. Transparent Image
The opacity property can take a value from 0.0 - 1.0. The lower value, the more transparent:

3. Image Filters
The CSS filter property adds visual effects (like blur and saturation) to an element.

- Definition and Usage
The background-size property specifies the size of the background images.

There are four different syntaxes you can use with this property: the keyword syntax ("auto", "cover" and "contain"), the one-value syntax (sets the width of the image (height becomes "auto"), the two-value syntax (first value: width of the image, second value: height), and the multiple background syntax (separated with comma).

## IMAGE ROLLOVERS & SPRITES

Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it.
This is achieved by setting a background image for the link or button that has three different styles of the same button (but only allows enough space to show one of them at a time). You can see the image we are using in this example on the right. It actually features two buttons on the one image.
When the user moves their mouse over the element, or clicks on it, the position of the background image is moved to show the relevant image.
