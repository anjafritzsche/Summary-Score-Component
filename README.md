# Another project finished

this is my second project, I finished with the style guide of frontend mentor.
The task was to code, whats in the picture. You can find the link to the challenge at the page.
If you want to read about some of experiences, I wrote some of them down below.
Questions of feedback? Yes, you´re always welcome. Just send me a message. I try to answer asap.

# # # PROJECT DETAILS

# How I processed and structured?

As I´m more familiar with design, I first added the guide picture into Illustrator and painted outlined boxes, what elements I will use, how are they structured and so on. As this was finished, I started coding trough the text, ordered the structure, nested all Elements and started just with the alginment of each box or element in css, to make sure it will everything work for desktop & mobile. After the basis was done, I styled with colors,and font/sizes etc. Then I coded first the Desktop version, then the mobile version with the Media Query. At the end I tested every desktop view, and added some more querys with different width. It´s not finished yet and will work further trough some details. 

# How long did it take?
I coded everything in one piece in 7 hours.

# What was challenging?

- during the process I needed to nest more div elements around some parts, to optimise the alignment,margins/ paddings for each card. it was a big challenge to get the alignment right without any other elements. I'm sure there are less complex solutions.

- while coding I noticed that the score circle does not behave proportionally when I compress my browser window. One solution would have been to use flex-grid, und place items, but then the element doesn't shrink at all and sticks above all other elements. I decided to put up with the shrinking and try again later with flex-shrink or search for another solution. for now I leave this here. If you have a nice solution, I would be happy to get some help here. I still miss some knowledge in some basics.

- The media query was finished very quick. Because of the basic css, i had to adjust only a few % of the surrounding containers at the beginning. This was my plan, why I added more containers around. As I went trough more Media sizes, I noticed, there where many more adjustments to do. Its not optimized for a vertical pad view, but I´m okay with that.

- last but not least: what the flex! How many flexboxes are too much? I still believe there are more clever methods to work with functions and combinators, but this is my level of knowledge for now.

- I have no knowledge in js, so I couldn`t use the data.json file.

# what did I learn?

- I learned a lot about the relationships of the individual elements.
- I learned to think deeper and around the corner, for later needs for mobile versions. So I learned to use parent containers, to make it more easy in the finishing. (I added some more insights down below in Acknowledgements)
- Having a roadmap is pure gold.
- The selection of elements is super important, because of their own characteristics.
- And more attention to design details.
- How much structure even such a small project needs anyway and how to do this.
- work more resvonsive and get more feeling with % & vh/vw

# what I used

- illustrator (just my personal preference, I´m a visual learner)
- Visual Studio Code
- style guide from frontend mentor
- coffee

## Acknowledgments or what helps me

I can recommend, to go trough a project like this with a clear guideline, what to use, why and how, BEFORE start coding. If you have no other tools, try mindmap (it's usable in Browser or App & it's free) or any tool you know, to wire elements, structure them, sort them, build containers and make notes around your elements. This helps to work trough nesting. The better I worked in the first place, the better it flows by itself later.

Some more: I was thinking about how to handle the containers and the properties of the containers to easily create a responsive version with few selectors later. The reason was, I didn't want to tackle every element again, so I worked with nesting of several containers of the two cards. Some of them had only one function, to align things or to give a padding that works on one of the two cards. The container alignbox was only there to get the elements inside the map on one line above and below, without giving margins to each selector.

That's it. Thanks.

# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Light red: hsl(0, 100%, 67%)
- Orangey yellow: hsl(39, 100%, 56%)
- Green teal: hsl(166, 100%, 37%)
- Cobalt blue: hsl(234, 85%, 45%)

## Gradients

- Light slate blue (background): hsl(252, 100%, 67%)
- Light royal blue (background): hsl(241, 81%, 54%)

- Violet blue (circle): hsla(256, 72%, 46%, 1)
- Persian blue (circle): hsla(241, 72%, 46%, 0)

### Neutral

- White: hsl(0, 0%, 100%)
- Pale blue: hsl(221, 100%, 96%)
- Light lavender: hsl(241, 100%, 89%)
- Dark gray blue: hsl(224, 30%, 27%)

### Notes

Use transparency to get the colour variations necessary to match the design. Hint: look into using `hsla()`.

## Typography

### Body Copy

- Font size (paragraphs): 18px

### Font

- Family: [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk)
- Weights: 500, 700, 800
