# Matching Mocks [WIP]

A common workflow in professional front-end development is:
1. Receive a design file (*mock-up*) from a visual design or UX team
2. Convert the visual design to an HTML/CSS/JS page

In this exercise we will practice the process of turning a visual design into code, and also improve our HTML and CSS quality through code review sessions.

The design we will be working with is a Figma mock-up, and can be viewed [here](https://www.figma.com/file/DTHZxrnPpAQhYgH1XFQiBi/Untitled?node-id=0%3A1). You may notice a tool bar on the right side with some CSS.
This CSS is not entirely correct, so avoid copying it. You may copy the  color values in the tool bar, but nothing else.

There are a lot of HTML tags and attributes. There are alot of CSS rules and values too. You are not expected to memorize all of these (no one can). You can use the following documentation for reference:
- [HTML MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS)

No online tutorials, forums, or guides! 
Our goal is to plan and build a user interface through our own decisions

## Level 1: Semantic and Accessible HTML
- [ ] Write minimal HTML without any CSS or presentational markup
- [ ] Use semantic HTML tags
- [ ] DO NOT add any CSS styling

--- CSS Units Lecture ---

## Level 2: Typography and Color
- [ ] Add a file called `style.css` and link it to the HTML page
- [ ] Make the HTML page match the design's typography using CSS
  - [ ] Match Font-Family (You can use Google Fonts: https://fonts.google.com/)
  - [ ] Match Font-Size
- [ ] Apply color
  - [ ] Match background colors in the mock-up
    - [ ] You may add `<div>`s as needed
  - [ ] Match foreground (text) colors in the mock-up

--- Box Model Lecture ---

## Level 3: Layout and Spacing
- [ ] Use fixed pixel widths and box elements to organize the form into sections and layout boxes
- [ ] Make sure margins, borders, and padding match the mock exactly

--- Responsive Design Lecture ---

--- Flexbox Lecture ---

## Level 4: Responsive Design
- [ ] Add a meta tag to set viewport width
- [ ] Change fixed pixel layout to flex box layout
