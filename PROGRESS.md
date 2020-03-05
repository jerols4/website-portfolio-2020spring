## Progress 03-05-2020

This is the first preview of my project. I intend to make a minimalist website to showoff my photography portfolio. With this,
 I plan on keeping the colors simple and complimentary. In this preview, I currently have the navbar and slideshow functioning.
 This involved a lot of following tutorials on w3schools.com, but don't let that make you think I was just copy-pasting and good 
 to go. For the navbar, I used a list for all of the separate 'containers.' This allowed me to place a 'logo' (just text) of my
 name in the top left of the website, as well as links in the top right to an about page and my photography Instagram. Thanks
 to the tutorial I followed, I was able to get the links to have nice hover effects, but to keep the page minimal, I got rid
 of the gaudy boxes around these items and how they were aligned. I then wanted a carousel/slideshow to show off a preview
 of a few pictures, so I followed another tutorial to do so. This part was tricky and required a lot of messing around to get
 working. One problem I ran into was the images weren't loading until an arrow was clicked. I realized this was because
 I had the call to my JavaScript file before the call to my CSS file, so the JavaScript would try to access unknown CSS elements.
 I then had an issue where the active links from the navbar were getting styles applied to them. I figured out this is because
 the tutorial I was following had classes of the same name, which I renamed. The slideshow also didn't account for images of 
 different heights, so I had to include a .mySlides img selector that would resize any images that went over the height limit I set.
 I finally messed around with the colors associated with the slideshow until I felt that it fit the design well enough. Following
 these tutorials, I learned a lot about have HTML, JavaScript, and CSS interact with eachother and how to play off of those interactions
 to get the result that I want. 
