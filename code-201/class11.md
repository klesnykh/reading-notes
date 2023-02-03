# Class 11 Reading Notes

*Video and Audio Content*  
1\. In the old days of video and audio in HTML you had to use plugin based technologies to access them, vs now you have <\audio> <\video> and javascript  
2\. src is the source of the video, controls are the controls on the video  
3\. So that if for some reason the user can't see the video they can use the fallback to still access it  
4\. Short story: video the pirate could move around and walk, and on his shoulder sat a audio the parrot because the pirate could not talk. As video would be explaining with his hands the parrot understood, and just as his name implies audio helped video by explaining with his words.  

*A Complete Guide to Grid*  
1\. flex makes the contents easier to move around, grid makes a bunch of boxes to put the content in and then you can tell the contents what to do in that grid  
2\. the grid container is the parent element, basically hold all the grid boxes, grid lines are the dividing lines that make up the structure of the grid, track is the row or column in the grid, grid items are the content of each smallest box  

*Responsive Images*  
1\. You can make the site run smoother/quicker because depending on the screen size smaller screens don't need huge images and will load faster without them  
2\. They provide several additional source images (srcset) along with hints to pick up on the right one (sizes). An example is srcset="---.jpg 480w, ---.jpg 800w" and then under it is sizes="(max-width: 600px) 480px, 800px"  
3\. Because of the way loading a website works. It first reads the HTML and downloads all related images, and then it reads the css and JS files, so esentially it would have to re-load that image as a smaller one if you use css or js vs making the responsiveness of the site quicker/smoother and take up less memory by specifying the srcset in the html
