## Text in HTML: 
● Structural markup: the elements that you can use to describe both headings and paragraphs

● Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on 

## Headings: 

HTML has six "levels" of headings:
\<h1> is used for main headings \<h2> is used for subheadings
If there are further sections under the subheadings then the \<h3> element is used, and so on...
Browsers display the contents of headings at different sizes. The contents of an \<h1> element is the largest, and the contents of an \<h6> element is the smallest. The exact size at which each browser shows the headings can vary slightly. Users can also adjust the size of text in their browser. You will see how to control the size of text, its color, and the fonts used when we come to look at CSS.

## Paragraphs: 

\<p>
To create a paragraph, surround the words that make up the paragraph with an opening \<p> tag and closing \</p> tag.
By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

## Bold & italic: 


\<b>
By enclosing words in the tags \<b> and \</b> we can make characters appear bold.
The \<b> element also represents a section of text that would be presented in a visually different way (for example key words in a paragraph) although the use of the \<b> element does not imply any additional meaning.
\<i>
By enclosing words in the tags \<i> and \</i> we can make characters appear italic.
The \<i> element also represents a section of text that would be said in a different way from surrounding content — such as technical terms, names of ships, foreign words, thoughts, or other terms that would usually be italicized.

## White space: 

In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines.
When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as white space collapsing.

## Quotations: 


There are two elements commonly used for marking up quotations:
\<blockquote>
The \<blockquote> element is used for longer quotes that take up an entire paragraph. Note how the \<p> element is still used inside the \<blockquote> element.
Browsers tend to indent the contents of the \<blockquote> element, however you should not use this element just to indent a piece of text — rather you should

## Specifying Typefaces

- font-family
The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
The value of this property is the name of the typeface you want to use.
The people who are visiting your site need the typeface you have specified installed on their computer in order for it to be displayed.
You can specify a list of fonts separated by commas so that,
if the user does not have your first choice of typeface installed, the browser can try to use an alternative font from the list.
It is also common to end with a generic font name for that type of font

## Size Of Type:
- font size:

  The font-size property enables you to specify a size for the
font. There are several ways to specify the size of a font. The most common are:
pixelS
Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters px.
percenTageS
The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.
If you create a rule to make all text inside the <body> element to be 75% of the default size (to make it 12px), and then specify another rule that indicates the content of an element inside the <body> element should be 75% size, it will be 9px (75% of the 12px font size). 

# Java Script : 

![JS Method](https://media.geeksforgeeks.org/wp-content/uploads/20190306104652/obj21.png)

![JS Method](https://www.tutsmake.com/wp-content/uploads/2020/05/JavaScript-Data-Types-Examples-1.jpeg)

![JS Method](https://image.slidesharecdn.com/javascriptbeyondjqueryjfokus2013johnwilander-130207032832-phpapp01/95/javascript-beyond-jquery-jfokus-2013-10-638.jpg?cb=1360207895)