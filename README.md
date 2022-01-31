# LKCS Financial - Home Page Challenge
[View the Live Website](https://shyann-lkcs.netlify.app)

## Objective
Implement the home page design for the fictional bank, LKCS Financial.

## Considerations
### Initial Implementation with Bootstrap 5

Upon first recieving this assignment, I drew out the various sections, rows, and columns to help me better envision 
how to initially carve out the HTML. Since Bootstrap 5 operates with a grid system, I knew it would help me organize elements to create 
a clean and responsive webpage. I also leveraged Bootstrap 5 for the purpose of building a responsive, dropwdown navbar that could be toggled by a 
hamburger icon while viewing the website on smaller devices like phones.

### Diagonal Design

Making the diagonal design was by far the most interesting challenge. After doing some research and messing around with the new things I learned, 
I recreated the effect by using CSS to create psudo-elements, transforming them by skewing them along the y-axis to get that parallelogram shape, 
and then clip-path the edges of those elements to give the illusion the sections are actually slanted. While this solution worked, it caused a few 
finicky margin/padding type issues where there was more space between elements than desired.
  - [Create Diagonal Layouts Like It's 2020](https://9elements.com/blog/pure-css-diagonal-layouts/)
  - [Go Skew() Yourself!](https://www.youtube.com/watch?v=dDtJPv7DlDU&t=218s)
  - [Diagonal Containers in CSS](https://codyhouse.co/blog/post/css-diagonal-containers)
  - [Clippy: Clip Path Tool](https://bennettfeely.com/clippy/)

### Font Size Tool

explanation of javascript

### Additional Effects

animate, hover, countup
