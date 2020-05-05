# Project 0

Web Programming with Python and JavaScript

This is a mobile first website project on Coral Reefs.
It uses Bootstrap 4 to accomplish this.
The first lines would be the HTML5 doctype declaration and the viewport meta tags for proper responsive behaviors.

It has 4 linked pages: the index.html, what.html, why.html and how.html.

The other files/folders are:
- bootstrap/scss/ - folder for the bootstrap core files
- img/ - folder for the images used in this website
- theme.css - the main stylesheet file
- theme.scss - sass code to generate the theme.css above
- theme.css.map - the scss map that goes with the theme.css
- css/custom.css - stylesheet file for quick styling

Page layout:
- each page has a navbar, content area, and footer.
- the navbar is derived from the standard bootstrap navbar code so it's fluid by default. For this project I used the page links, and the navbar brand in which I used an image instead of just the default text.
- the content area is wrapped in a grid container with a heading and two rows.
- the first row contains the showcase subsection
- the second row is for additional page features or components.
- inside the showcase subsection is a main image which floats to the right of the paragraphs. So the paragraphs and other content wraps around the related image.
- the lower section on the other hand will not wrap but rather continue to float left being on the next row down.
- at the bottom is the footer div which expands the whole length like the navbar

Theme:
- the primary theme color is an ocean color #1a8c97
- that is the background color of the navbar, the body and the footer
- the background image will be behind the showcase subsection.

index.html:
- 1st row is .showcase: a floating image and paragraphs which wraps around the image.
- 2nd row is #features: 3 card components in 3 columns

what.html:
- 1st row is .showcase: a floating image with paragraphs and an unordered list which wraps around the image
- 2nd row: none

why.html:
- 1st row is .showcase: a floating image with paragraphs and an unordered list which wraps around the image
- 2nd row has a div.table-responsive-sm  with a table#medicine-table: has 5-cols so you can scroll the table sideways on smaller devices to see

how.html:
- 1st row is .showcase: a floating image with paragraphs and an unordered list which wraps around the image
- 2nd row: none

Media Queries:
- on large desktops and up: page headers will have bigger fonts and the .showcase white box background is less transparent
- on portrait phone viewports: card components will stack and its images will not show
- on landscape phone viewports: card images will start showing but smaller
- on tablets: card images will scale bigger
- on desktops: card images continue to scale bigger
- on large desktops and up: card images scale proportionate to its parent
