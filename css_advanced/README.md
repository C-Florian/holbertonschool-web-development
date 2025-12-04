# CSS, advanced

Holberton School – Front-end Web Development  
Project: CSS, advanced  
Author: Florian Chéreau


## Project Overview

This project is the continuation of **0x02. HTML, advanced**.

In the HTML project, the focus was on building a clean, semantic, and accessible page structure. In this project, the goal is to bring that structure to life with CSS, by reproducing the given Figma design as closely as possible:

- Applying consistent typography and colors  
- Working with layout, spacing, and alignment  
- Understanding and using CSS specificity correctly  
- Building a pixel-perfect (or nearly) implementation of the designer’s mockup  

You are not allowed to use any external frontend library or framework (no Bootstrap, no Tailwind, no React, etc.). Only HTML, CSS and a bit of JavaScript when necessary.


## Learning Objectives

By the end of this project, you should be able to explain to anyone:

### General

- What CSS is  
- How to add style to an element  
- What a class is  
- What a selector is  
- How to compute CSS Specificity Value  
- What Box properties are in CSS  
- How the browser loads a webpage  


## Resources

You are encouraged to read or watch:

- Learn to Code HTML & CSS (until "Creating Lists" included)  
- Inline Styles in HTML  
- Specifics on CSS Specificity  
- CSS SpeciFishity  
- CSS – MDN  
- MDN Learning Area  

These resources cover the core concepts used in this project: selectors, specificity, box model, inline vs external styles, etc.


## Design and Figma

The final expected design is available on Figma:

- Figma page: [Insert Figma link here]  
- FIG file: [Insert link if needed]  

Notes:

- If your computer is missing fonts, you can download:
  - Source Sans Pro  
  - Spin Cycle OT  
- Some Figma values are decimals (example: 13.78px). You may round them.

Use “Duplicate to your Drafts” on Figma to access all design details (colors, spacing, typography, layout, etc.).


## Project Structure

Repository:

- GitHub repository: `holbertonschool-web-development`
- Directory: `css_advanced`

For this task (0. README and objectives):

- `css_advanced/README.md` → this file  
- `css_advanced/index.html` → copy of the index.html from 0x02. HTML, advanced  

Example structure:

holbertonschool-web-development/
└── css_advanced/
├── README.md
└── index.html
└── styles.css


Later tasks in this project will add:

- A stylesheet file (for example: styles.css)
- More advanced CSS features such as transitions, responsive layout, animations, variables, etc.


## Requirements

### General

- All files must end with a new line  
- A README.md file at the root of the project is mandatory  
- No external libraries or frameworks allowed  
- Only HTML, CSS, and JavaScript  

### Code Quality

- HTML and CSS must validate through W3C Validators  
- Use semantic HTML  
- Keep CSS clean and organized  
- Avoid duplicated rules when possible  


## How the Browser Loads a Webpage

This project is a good opportunity to understand how browsers render pages:

1. The browser downloads the HTML file.  
2. It parses it and builds the DOM tree.  
3. It downloads and parses CSS files, building the CSSOM.  
4. DOM + CSSOM form the render tree.  
5. The browser computes positions and sizes (layout).  
6. The browser paints and renders the result on screen.

Understanding this process helps reason about specificity, cascade, and layout behavior.


## CSS Specificity and Box Model (Summary)

CSS specificity defines which rule is applied when several selectors target the same element.  
Order of specificity from highest to lowest:

1. Inline styles  
2. IDs  
3. Classes, attributes, pseudo-classes  
4. Elements and pseudo-elements  

The CSS box model consists of:

- Content  
- Padding  
- Border  
- Margin  

Mastering these is essential for matching a Figma design.


## Testing and Validation

Before submitting, ensure:

1. HTML validates with the W3C HTML Validator  
2. CSS validates with the W3C CSS Validator  
3. The page renders correctly in at least one modern browser  
4. The layout matches the Figma design regarding:
   - Fonts  
   - Colors  
   - Sizes  
   - Spacing  
   - Alignment  


## Author

Name: Florian Chéreau  
GitHub: https://github.com/C-Florian  
Holberton School – France (Sens)
