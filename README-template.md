# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [github](https://github.com/raficode2303/recipe-page-main.git)
- Live Site URL: [Netlify](https://recipe-page-main-2024.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup such: `ul, ol, li, ::marker, hr, h1-h6, img, table, caption, tr, td `
- CSS custom properties
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

to use LQIP - low-quality image placeholder and preload at `<link>` tag

Do research on various HTML elements and ensure i use the most appropriate element based on the content???!

to use `::marker` css selector.

that `<li>` list-style size can modify by using `::marker{font-size: ...;}`

how to apply a different colors in <li> tag, one color for the list-style-type and second color for the text by using `::marker {color: ...;}`

too-much-css make text rows of <li> tag to start in the different place (vertically) - i learned to NOT change the default behavior of elements unless it necessary, because it cause other issues to solve.

how vertically centering the `::marker` pseudo-element using `::before` because ::marker pseudo-element in CSS does not support vertical alignment or many other properties related to positioning and dimensions. This is due to the fact that ::marker is not a standard box in CSS.

I noticed that details of specific design take me a long time to achieve the desired result - nee to improve it!

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<table class="nutrition-table">
  <caption>
    -- table heading --
  </caption>
  <tr>
    <td>Calories</td>
    <td>277kcal</td>
  </tr>
</table>
```

```css
@media (width > 600px) {
  .app {
    max-width: clamp(300px, 90%, 700px);
  }
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

focusing on in future projects: be more efficient and finish the project more quickly. to be completely comfortable with CSS Selectors also to solve the challenge using GRID/FLEX.

2. how to solve notification like:
   ARIA roles used must conform to valid values
   `<header role="header" class="header">`

All page content should be contained by landmarks
`<img class="image-recipe" src="./assets/images/image-omelette.jpeg" width="1312" height="600" alt="omelette image" loading="lazy">`

### Useful resources

- [CSS Selector Reference](https://www.w3schools.com/cssref/css_selectors.php) - This helped me for CSS issues. I really liked this site and always using it.
- [stackoverflow](https://stackoverflow.com/) - help with problems others have handle.
- [copilot](https://copilot.microsoft.com/) - AI chat to help me with CSS.
