# Web Dev Practice

Learning web dev day by day, going towards building a full notes app eventually. 1st year student, so pace is slow sometimes because of exams.

## Day 1
First ever HTML. Learned head, title, body tags. Made a page with my name and roll number, added a blue paragraph and a button. Basic but felt good to see something render in the browser.

## Day 2
Lists and links today - ul, ol, li, and a href. Made a list of languages I started and accounts I made (LinkedIn, GitHub lol spelled it wrong first time).

## Day 3
Added an image and a 7-day table. Also tried a div with background color. Accidentally wrote alt="Ohh shit" on an image, need to be more careful with that stuff since it's a public repo lol.

## Day 4
Forms today - login form and a note-adding form. Wrote `<forms>` instead of `<form>` at first, didn't work. Also realized password fields need type="password" not type="text", otherwise it shows plain text.

## Day 5
Learned header, nav, section, footer instead of just divs everywhere. Built a basic layout for what the notes app homepage could look like. Links need https:// in front or they break, learned that the hard way.

## Day 6
CSS classes and IDs, and writing CSS in a style tag instead of inline. Spent a good 10 min confused why my background color wasn't showing up - turned out I misspelled the id in CSS. Lesson: check spelling first when something doesn't work.

## Day 7
Flexbox. display:flex and gap. Made subject cards (Maths, Chemistry, Python) show side by side instead of stacked. This one clicked pretty fast honestly.

## Day 8
CSS Grid - similar to flexbox but does rows and columns both. repeat(3, 1fr) for 3 equal columns. Used it for a notes dashboard that can grow to any number of cards.

## Day 9
Hover effects and transitions. Cards scale up a bit and get a shadow on hover, buttons change color smoothly. Small thing but makes it feel way less static.

## Day 10
Combined everything into one page - header, nav, grid of cards, button, footer. First time it actually looked like a real website instead of random practice snippets.

## Day 11
Started JavaScript. Variables, console.log, basic data types. Checked output in the browser console for the first time - felt like a small milestone.

## Day 12
if-else and functions. Grading logic based on marks, and a reusable greet function. Starting to feel like actual programming now, not just HTML tags.

## Day 13
Arrays and for loops. Had a bug where I wrote "note" instead of "notes" in the loop condition, classic typo. Got "not defined" error, fixed it, moved on.

## Day 14
DOM manipulation - getElementById, changing text and color on button click. First time JS actually changed the page itself. Made a bunch of typos here too (oneclick instead of onclick, getElementsById instead of getElementById) but got it working eventually.

## Day 15
Made notes render from an array using a loop instead of hardcoding them in HTML. This is basically how real apps show data. Took a couple tries to get the function name and class name spelled consistently.

## Day 16
Add and delete notes now - push() and splice(). This felt like the actual "app" part finally coming together. Had a messy round of bugs (case mismatches, missing brackets) but got through it.

## Day 17
localStorage so notes survive a refresh. Had to use JSON.stringify/parse since localStorage only stores strings. Refreshed the page and the notes were still there - genuinely exciting moment.

## Day 18
Notes are now objects {title, content} instead of plain text, so each note has a proper title and body. This is basically how data will look later when a real database comes in.

