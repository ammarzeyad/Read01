# Images In HTML

- In the beginning, the Web was just text, and it was really quite boring. Fortunately, it wasn't too long before the ability to embed images (and other more interesting types of content) inside web pages was added. There are other types of multimedia to consider, but it is logical to start with the humble \<img> element, used to embed a simple image in a webpage. In this article we'll look at how to use it in depth, including the basics, annotating it with captions using \<figure>, and detailing how it relates to CSS background images.

## How do we put an image on a webpage?

 In order to put a simple image on a webpage, we use the \<img> element. This is an empty element (meaning that it has no text content or closing tag) that requires a minimum of one attribute to be useful — src (sometimes spoken as its full title, source). The src attribute contains a path pointing to the image you want to embed in the page, which can be a relative or absolute URL, in the same way as href attribute values in \<a> elements.

![discrapiton](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML/basic-image.png)

## where to place images in code?

Where an image is placed
in the code will affect how it is displayed. Here are three examples of image placement that produce different results:
1: before a paragraph
The paragraph starts on a new line after the image.
2: InsIde the start of a paragraph
The first row of text aligns with the bottom of the image.
3: In the mIddle of a paragraph
The image is placed between the words of the paragraph that it appears in.

## The three rules for creating Images

1 save Images In the right format:

- websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load.

2 Save images at the right size:

- You should save the image at the same width and height it will appear on the website. If
the image is smaller than the width or height that you have specified, the image can be distorted and stretched. If the image is larger than the width and height if you have specified, the image will take longer to display on the page.

3 use the Correct resoiution:

- Computer screens are made up of dots known as pixels. Images used on the web are also made up of tiny dots. Resolution refers to the number of dots per inch, and most computer screens only show web pages at 72 pixels
per inch. So saving images at a higher resolution results in images that are larger than necessary and take longer to download.

![discraption](https://www.milesweb.in/blog/wp-content/uploads/2017/02/image-formats.png)

## The figure & figcaption elements

- The figure element represents a unit of content, optionally with a caption, that is self-contained, that is typically referenced as a single unit from the main flow of the document, and that can be moved away from the main flow of the document without affecting the document’s meaning.

- The figcaption element represents a caption or legend for a figure.

## Color

*Foreground-color.*

- You can specify any color in CSS in one of three ways:

1. Rgb values
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
2. Hex Codes
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
3. Color names
There are 147 predefined color names that are recognized
by browsers. For example: DarkCyan

*Background-color.*

1. CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

2. You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names

3. If you do not specify a background color, then the background is transparent.

4. By default, most browser windows have a white background, but browser users can set a background color for their windows, so if you want
to be sure that the background is white you can use the background-color property on the \<body> element.

![discraption](https://answers.unity.com/storage/temp/55339-screen-shot-2015-10-01-at-21121-pm.png)

## CSS: HSL & HSLA

1. HUE

   This is expressed as an angle (between 0 and 360 degrees).

2. STATURATION

    This is expressed as a percentage.

3. lightness
This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.
The hsla color property allows you to specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents transparency

![discraption](https://image.slidesharecdn.com/refreshdc-html5css3-090719085307-phpapp01/95/up-to-speed-on-html-5-and-css-3-37-728.jpg?cb=1252999046)
