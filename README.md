# All-in-One Explanation and Interview Questions: HTML, CSS, and SQL

## Introduction
This document provides a comprehensive explanation of commonly used HTML tags, CSS keywords, and functions. Additionally, it includes a curated list of common interview questions on HTML, CSS, and SQL to help you prepare for technical interviews.

---

## Explanation of Commonly Used HTML Tags

- `<!DOCTYPE html>`: Declares the document type and version of HTML (HTML5).
- `<html lang="en">`: Root element of the HTML document with language attribute.
- `<head>`: Contains meta-information about the document.
- `<meta charset="UTF-8" />`: Sets character encoding to UTF-8.
- `<meta name="viewport" content="width=device-width, initial-scale=1" />`: Ensures responsive design on different devices.
- `<title>`: Sets the title of the webpage shown in the browser tab.
- `<link rel="stylesheet" href="style.css" />`: Links an external CSS file.
- `<body>`: Contains the visible content of the webpage.
- `<header>`: Defines the header section of the page.
- `<nav>`: Defines a navigation section.
- `<ul>`, `<ol>`: Unordered and ordered lists.
- `<li>`: List item.
- `<main>`: Main content area of the page.
- `<section>`: Defines sections in a document.
- `<div>`: Generic container for grouping elements.
- `<h1>`, `<h2>`, `<h3>`, ...: Headings of different levels.
- `<p>`: Paragraph.
- `<a href="#">`: Anchor tag for links.
- `<img src="image.jpg" alt="description" />`: Embeds an image.
- `<footer>`: Defines the footer section.

---

## Explanation of Commonly Used CSS Keywords and Functions

- Selectors:
  - Element selector: `p`, `h1`, `div`
  - Class selector: `.classname`
  - ID selector: `#idname`
  - Descendant selector: `div p`
- Properties:
  - `color`: Text color.
  - `background-color`: Background color.
  - `font-family`: Font type.
  - `font-size`: Size of the font.
  - `margin`: Space outside elements.
  - `padding`: Space inside elements.
  - `border`: Border around elements.
  - `width`, `height`: Dimensions of elements.
  - `display`: How elements are displayed (`block`, `inline`, `flex`, etc.).
  - `position`: Positioning method (`static`, `relative`, `absolute`, `fixed`).
  - `float`: Floating elements left or right.
- Functions:
  - `rgb()`, `rgba()`: Color functions.
  - `calc()`: Perform calculations for property values.
  - `url()`: Used to include images or fonts.
- Pseudo-classes:
  - `:hover`: Style when mouse hovers over an element.
  - `:active`: Style when an element is activated.
  - `:nth-child()`: Selects elements based on their position.

---

## Interview Questions on HTML

1. What is the difference between HTML and XHTML?
2. What are semantic HTML elements? Give examples.
3. What is the purpose of the `DOCTYPE` declaration?
4. How do you make a website responsive?
5. What is the difference between `<div>` and `<span>`?
6. How do you include CSS in an HTML document?
7. What are data attributes in HTML?
8. Explain the difference between block-level and inline elements.
9. What is the purpose of the `<meta>` tag?
10. How do you optimize a website for SEO using HTML?

---

## Interview Questions on CSS

1. What are the different ways to apply CSS to a web page?
2. Explain the box model in CSS.
3. What is the difference between `relative`, `absolute`, `fixed`, and `sticky` positioning?
4. How does CSS specificity work?
5. What are pseudo-classes and pseudo-elements? Give examples.
6. How do you center a div horizontally and vertically?
7. What is the difference between `em`, `rem`, `%`, and `px` units?
8. Explain Flexbox and its main properties.
9. What is the difference between `visibility: hidden` and `display: none`?
10. How do media queries work in CSS?

---

## Interview Questions on SQL

1. What is the difference between `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, and `FULL JOIN`?
2. What are primary keys and foreign keys?
3. How do you retrieve unique records from a table?
4. What is normalization? Explain different normal forms.
5. How do you write a query to find the second highest salary in a table?
6. What is the difference between `WHERE` and `HAVING` clauses?
7. How do you create an index in SQL? What are its benefits?
8. What is a subquery? Give an example.
9. Explain ACID properties in database transactions.
10. How do you optimize SQL queries for better performance?

---

This README provides a solid foundation for understanding HTML, CSS, and SQL concepts and prepares you for common interview questions in these areas.

---

## Detailed Dictionary of Code Keywords and Usage

### HTML Tags and Attributes

- `<!DOCTYPE html>`: Declares the document type and version of HTML (HTML5).
- `<html>`: Root element of an HTML page.
- `<head>`: Contains meta-information about the document.
- `<body>`: Contains the visible content of the webpage.
- `<header>`: Defines the header section of a page.
- `<nav>`: Defines a navigation menu.
- `<section>`: Defines a section in a document.
- `<div>`: Generic container for grouping elements.
- `<h1>`, `<h2>`, `<h3>`: Headings of different levels.
- `<p>`: Paragraph text.
- `<a href="URL">`: Creates a hyperlink to another page or location.
- `<img src="image.jpg" alt="description">`: Embeds an image with alternative text.
- `<ul>`, `<ol>`: Unordered and ordered lists.
- `<li>`: List item inside lists.
- `id`: Attribute to uniquely identify an element.
- `class`: Attribute to assign CSS classes to elements.

### CSS Properties and Keywords

- `background-color`: Sets the background color of an element.
- `color`: Sets the text color.
- `font-family`: Specifies the font type.
- `font-size`: Sets the size of the font.
- `margin`: Space outside the element.
- `padding`: Space inside the element.
- `border`: Defines the border around an element.
- `width`, `height`: Sets the dimensions of an element.
- `display`: Controls how an element is displayed (e.g., block, inline, flex).
- `position`: Specifies the positioning method (static, relative, absolute, fixed).
- `float`: Floats an element to the left or right.
- `:hover`: Pseudo-class for styling when mouse hovers over an element.
- `@import`: Imports external CSS files.

### JavaScript Keywords and Functions

- `const`: Declares a constant variable that cannot be reassigned.
  - Example: `const pi = 3.14;`
- `let`: Declares a block-scoped variable that can be reassigned.
  - Example: `let count = 0;`
- `var`: Declares a function-scoped variable (older syntax).
  - Example: `var name = "John";`
- `function`: Defines a function.
  - Example: `function greet() { console.log("Hello"); }`
- Arrow function `=>`: Shorter syntax for functions.
  - Example: `const add = (a, b) => a + b;`
- `document.getElementById()`: Selects an HTML element by its ID.
  - Example: `const btn = document.getElementById('submit');`
- `addEventListener()`: Attaches an event handler to an element.
  - Example: `btn.addEventListener('click', () => alert('Clicked'));`
- `for` loop: Repeats code a set number of times.
  - Example: `for(let i=0; i<5; i++) { console.log(i); }`
- `if` statement: Conditional execution.
  - Example: `if(score > 10) { console.log('Win'); }`
- `Math.random()`: Generates a random number between 0 and 1.
  - Example: `let rand = Math.random();`
- `console.log()`: Prints messages to the browser console.
  - Example: `console.log('Hello World');`
- `createElement()`: Creates a new HTML element.
  - Example: `const div = document.createElement('div');`
- `appendChild()`: Adds a child element to a parent.
  - Example: `parent.appendChild(div);`

### Dice Game (dice/ folder) Specific Code

- `rollBtn.onclick`: Event handler for the roll dice button.
- `diceDisplay.innerHTML = ''`: Clears the dice display area.
- `Math.floor(Math.random() * 6) + 1`: Simulates rolling a six-sided dice.
- `document.createElement('div')`: Creates dice face elements dynamically.
- CSS classes like `.dice-red`, `.dice-blue`, `.dice-green`: Color the dice faces.
- Variables `score` and `turns`: Track the player's score and number of turns.
- Updates the score and displays messages like "Game over" or current turn.

### Static Sites and Teams Projects (fs_as/ folder)

- HTML structure includes `<header>`, `<nav>`, `<section>`, `<footer>`.
- CSS classes like `.btn`, `.container`, `.features-grid` style buttons and layouts.
- Sections like "What We Offer", "Pricing Plans", "Helpful Links" organize content.
- Buttons with classes `.btn-primary`, `.btn-outline` for different styles.
- Navigation menus use `<ul>` and `<li>` for lists.
- Content is organized in cards and grids for responsive design.

### HTML Projects (html/ folder)

- Uses semantic HTML tags like `<main>`, `<section>`, `<article>`, `<header>`.
- Layouts use grid and flexbox CSS for responsive design.
- Images embedded with `<img>` tags and styled with CSS.
- Forms with `<input>`, `<button>`, and validation attributes.
- Navigation bars with lists and links.
- Text formatting tags like `<p>`, `<h1>`, `<ul>`, `<li>`.

### JavaScript Projects (javascript/ folder)

- Password Generator: Uses loops and random selection to create passwords.
- Number Guessing Game: Uses event listeners and conditional logic to check guesses.
- Login Page: Handles form submission and input validation.
- Array operations: Examples of `forEach`, `map`, `filter` functions.
- Day Finder: Converts input to day names using objects and conditionals.
- DOM manipulation: Creating elements, updating text content, handling events.

---

