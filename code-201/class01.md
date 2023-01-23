# 01 Reading Notes

## How the web works

- some info copied from [how the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- servers store webpages, sites or apps
- every time you look at a webpage is downs from the server to your computer to be shown to you
- internet connects (is the road between) your computer and the server
- TCP/IP - transmissions control protocol and internet protocol. Defines how data should travel across the internet (like the car or bike on the road, how you might get around)
- DNS - Domain name system. An address book for websites (maybe like yellowpages). Browser looks at the DNS to find the websites IP address before it can retrieve the website (website is like a name and ip address is like where you can find them). The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place. Good anaogy is looking up the address of a place so you can go there
- HTTP: Hypertext Transfer Protocol - defines a language for clients and servers to speak to each other. The s at the end I believe stands for security, so https is an added layer of security
- Component Files - wthe many differnet files inside the website
  - code files are mainly html, css, and js
  - asset files the other files in the page, like images, videos, pdf's, word docs etc.

  ---

### Getting Started

- 1.
You want to go to a website  
In an effort to learn more about light  
Your browser requests the contents from the server  
And you being an observer  
Notice how when the DNS sends you the HTTP  
The HTTP also asks for other stuff like the .css and the .js files
Which are basically like the styles  
And sometimes the code goes on for miles  
But man! Using this website is all smiles  

\2. not entirely sure about how html, css, .js are "parsed" in the browser, I just know that basically your browser asks for the html first, and then if the html has .css or .js files incorporated into it then it asks for those files again to have them work for the html
\3. You can find images online, google images for example
\4. for a string you use quotations vs a number you just write the number
\5. variables just hold value, they're important because then you can hold onto whatever value they are and use them again any time

#### Introduction to HTML

\1. Attibutes are used to add extra info/meaning/look to the element
\2. HTML element is composed of a opening tag, content and a closing tag
\3. The difference between an article and a section is articles wrap logical groups of related content and sections are used when you need 2 headers or footers are needed. I think you can group sections under articles
\4. A typical website can use a bunch of different elements. Some typical ones are body, header, paragraph, list, footer, etc.
\5. Metadata makes your site more user friendly, search engines can see what kind of metadata or if you even have metadata and determine how high up your page should be depending on user friendliness
\6. Using meta tag is the same way as using any other tag in the head. Start with meta, fill in the tag and close it with a greater than sign. Kind of like a source for a .js file

*How to Start to design a Website*
\1. the first step to designing a website is to draw out what you want it to look like and what it will do
\2. The most important question is what exactly do i want to accomplish?

*Semantics*
\1. using an h1 element shows that it is the most important sentence in your website, the main sentence
\2. using semantic tage benefits us because we can understand what that code is there for and what it's doing

*What is JavaScript*
\1. 2 things that require javascript on a webpage are controlling multimedia and animating images, and lots more
\2. You can add javascript to an html file via script tags inline or internally, or externally
