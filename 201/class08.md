# Linking to other sites

\<a>
Links are created using the \<a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.
Users can click on anything that appears between the opening \<a> tag and the closing </a> tag and will be taken to the page specified in the href attribute.
When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL .

- Link to other pages on the same site:

  When you are linking to other pages within the same site,
you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file.
If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page.

- Directory structure:

  1.structure
The diagram on the right shows the directory structure for a fictional entertainment listings website called ExampleArts.
The top-level folder is known
as the root folder. (In this example, the root folder is called examplearts.) The root folder contains all of the other files and folders for a website.
Each section of the site is placed in a separate folder; this helps organize the files.

  2.relationships

  The relationship between files and folders on a website is described using the same terminology as a family tree.
In the diagram on the right, you can see some relationships have been drawn in.
The examplearts folder is a parent of the movies, music and theater folders. And the the movies, music and theater folders are children of the examplearts folder.

   3.homepages

  The main homepage of a site written in HTML (and the homepages of each section in a child folder) is called index.html.
  Web servers are usually set up to return the index.html file if no file name is specified.

  - Email Links

    mailto:

    To create a link that starts up
the user's email program and addresses an email to a specified email address, you use the \<a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
On the right you can see that an email link looks just like any other link but, when it is clicked on, the user's email program will ope\n a new email message and address it to the person specified in the link.

- LAYOUT

    An HTML layout is a blueprint used to arrange web pages in a well-defined manner. It is easy to navigate, simple to understand and uses HTML tags to customize web design elements. Crucial for any website, an HTML layout that uses the correct format will easily improve a website's appearance.

**Normal Flow, or Flow Layout, is the way that Block and Inline elements are displayed on a page before any changes are made to their layout. The flow is essentially a set of things that are all working together and know about each other in your layout. Once something is taken out of flow it works independently.**

![descraption](https://slideplayer.com/slide/2408990/9/images/76/Notes+based+on+JC+Jackson+s+notes+and+GV+Jourdan+s+modifications.jpg)

**Relative positioning
Relative positioning is the first position type we'll take a look at. This is very similar to static positioning, except that once the positioned element has taken its place in the normal layout flow, you can then modify its final position, including making it overlap other elements on the page.**

![discraption](https://www.internetingishard.com/html-and-css/advanced-positioning/css-positioning-schemes-790d5b.png)

**Relative positioning
Relative positioning is the first position type we'll take a look at. This is very similar to static positioning, except that once the positioned element has taken its place in the normal layout flow, you can then modify its final position, including making it overlap other elements on the page.**
