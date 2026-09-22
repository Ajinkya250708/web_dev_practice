# Web Dev Practice

Daily practice of HTML, CSS, JS as I learn web development, building towards a full-stack notes app.

## Day 1
Learned basic HTML structure - head, title, body tags. Made a simple page with h1 heading, a paragraph with inline CSS color, and a button.

## Day 2
Learned lists and links - unordered list (ul), ordered list (ol), list items (li), and anchor tags (a href) for hyperlinks. Also used h2 for subheadings.

## Day 3
Learned images, tables, and basic CSS styling. Added an image using the img tag, built a 7-day table using table/tr/th/td, and styled elements with inline CSS (color, background-color, padding) using div.

## Day 4
Learned HTML forms - form, input (text and password types), textarea, label, placeholder, and submit button. Built a login form and a note-creation form as a preview of the notes app's UI.

## Day 5
Learned semantic HTML tags - header, nav, section, and footer - to structure a page properly instead of using generic divs. Built a basic layout for the notes app homepage with a header, navigation menu, welcome section, and footer, styled with background colors and padding.

## Day 6
Learned CSS classes and IDs, and how to write CSS inside a style tag instead of inline. Classes (like .box) can be reused on multiple elements, while IDs (like #main-header) are unique to one element. Learned that class/ID names in CSS must exactly match the HTML, or the style silently fails to apply.

## Day 7
Learned Flexbox - display:flex arranges child elements in a row instead of the default stacked layout, and gap adds spacing between them. Built a notes dashboard with subject cards (Mathematics, Chemistry, Python) arranged side by side using flexbox.

## Day 8
Learned CSS Grid - display:grid arranges elements in both rows and columns (unlike flexbox which only handles one direction). grid-template-columns: repeat(3, 1fr) creates 3 equal-width columns, and items automatically wrap to new rows. Built a notes dashboard grid that can scale to any number of notes.

## Day 9
Learned hover effects and transitions - the :hover pseudo-class applies styles only when the mouse is over an element, and transition makes those style changes animate smoothly instead of happening instantly. Added a scale and shadow effect on note cards and a color change on a button, both with smooth transitions.

## Day 10
Combined everything learned so far into one mini notes app page - header, nav, CSS grid for note cards, hover effects, and a button, all styled together. First page that actually looked like a real website instead of separate practice snippets.

## Day 11
Started JavaScript - learned variables (let), data types (string, number, boolean), and console.log() for printing output. Used the browser console (F12) to see JS output for the first time, and combined variables into a sentence using string concatenation.

## Day 12
Learned if-else conditions and functions. Used if/else if/else to assign grades based on marks, and created a reusable function (greetUser) that takes a parameter and can be called multiple times with different values.

## Day 13
Learned arrays and for loops. Arrays store multiple values in one variable, accessed by index starting from 0. Used a for loop to go through every item in an array and print each one, instead of writing repetitive code.

## Day 14
Learned DOM manipulation - using document.getElementById() to grab an HTML element in JavaScript, then changing its content (innerHTML) or style (style.color) when a button is clicked. First time JS changed the actual webpage instead of just the console.

## Day 15
Combined arrays, loops, and DOM manipulation to dynamically render a list. Instead of hardcoding notes in HTML, stored them in an array and used a loop to generate the HTML automatically - the same pattern real apps use to display data from a database.
