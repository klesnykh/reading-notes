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

### Poem about http sending data between computers

You want to go to a website
In an effort to learn more about light
Your browser requests the contents from the server
And you being an observer
Notice how when the DNS sends you the HTTP
The HTTP also asks for other stuff like the .css and the .js files
Which are basically like the styles
And sometimes the code goes on for miles
But man! Using this website is all smiles
