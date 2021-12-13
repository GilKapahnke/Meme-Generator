# Meme-Generator

## Introduction
When I applied for an apprenticeship, the company asked me to choose one of their programming challenges.
My choice was the meme-generator.
The user should be capable to upload a custom picture, which can be edited with an adjustable text.
I have some experience in programming, so I took the opportunity to show my skills.
I chose to make it web-based, since I also have some knowledge in HTML, CSS and Javascript.

## Getting Started
I started making the basic design of the app and decided to make a big editing area with a smaller part to display the picture.
After finishing the basic HTML I started to write the CSS.
I added 3 basic templates which can be imported into the meme.

## JavaScript
Finally I got to the programming part.
I created a button for applying the selected sections (font-family, color and size) and the text when clicking on it.
With a little help from the internet I found a solution to include own pictures.

## html2canvas library 
At this point I had to find a solution to make the meme downloadable. 
After a little research I found a library called "html2canvas" which allows to convert a div element into a canvas.
I was hoping to achieve a direct download by pressing the button.
Unfortunatly it kept throwing errors so I had to stick to the manual download.


The canvas displays the meme under the main part and by saving the image it can be downloaded manually.
