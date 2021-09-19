# Who is Roy Fielding?

- Senior Principal Scientist at Adobe, is known for his pioneering work on the World Wide Web, open source, and software architecture. He wrote the standards for HTTP/1. x and URI, has been a contributor to many other Web technologies, and defined the REST architectural style.

## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

- Machines don't have a universal noun - that's why they suck. Every programming language, database, or other kind of system has a different way of talking about nouns. That's why the URL is so important. It let's all of these systems tell each other about each other's nouns.

## What is the HTTP protocol that Fielding and his friends created?

- The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a URL.

## What does a GET do?

- the browser does an HTTP GET on the URL you typed in and back comes a web page.

## What does a POST do?

- If one system needs to add something to another system, it would use an HTTP verb of POST.

## What does PUT do?

- If a system wants to replace something in another system, it uses an HTTP verb of PUT

## What does PATCH do?

- to do a partial update, it'll hopefully use PATCH.