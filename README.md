# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The challenge was to build out the QR code component and get it looking as close to the design as possible.

### Screenshot

![](/qr-code-component-main/qr-code-component-main/images/screenshot.png)

### Links

- Solution URL: (https://github.com/amikoelvis/qr-code-component-main)
- Live Site URL: (https://qr-code-component-main-six-virid.vercel.app/)

## My process
1. Initialized my project as a public repository on. Making it easier to share my code with the community if I need help.
2. Configured my repository to publish my code to a web address. This would also be useful if I needed some help during a challenge as I could share the URL for my project with my repo URL.
3. Looked through the designs and started planning out how I would tackle the project.
4. Before adding any styles, structured my content with HTML. Writing my HTML first helped  focus my attention on creating well-structured content.
5. Wrote out the base styles for my project, including general content styles, such as `font-family` and `font-size`.
6. Started adding styles to the top of the page and worked down.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
1. Flexbox for Centering Content
Using Flexbox for Vertical & Horizontal Centering: The display: flex; with justify-content: center; and align-items: center; in the body allowed me to center content both vertically and horizontally. This is extremely useful for layouts that need to adapt to different screen sizes.

Code Example:

```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
```
2. Mobile-First Approach & Responsiveness
Mobile-First Design: I followed a mobile-first approach where I designed the layout to fit small screens first and then made adjustments for larger screen sizes using media queries. This ensures a smooth experience on mobile devices while scaling up easily to larger devices.

Example of Media Query for Desktop:

```css
@media (min-width: 1440px) {
    .container {
        max-width: 320px;
    }
}
```
3. Effective Use of Margin and Padding
Spacing is Key: I learned how important margin and padding are in creating balanced layouts. Using consistent spacing between elements, whether it's margin around containers or padding inside them, helped make the design look clean and organized.

Spacing Example:

```css
.container {
    padding: 20px;
    margin: 20px;
}
```
4. CSS Reset for Consistent Styling
Consistency Across Browsers: The use of * { padding: 0; margin: 0; box-sizing: border-box; } ensures that all browsers start from a consistent baseline, preventing unwanted space from appearing due to default browser styling.

CSS Reset Example:

```css
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
```

### Continued development
- Media Queries
- CSS Flexbox
- CSS Grid


### Useful resources

- [Basic Concept of Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox) - This helped me understand the fundamentals of CSS flexbox. I really liked this pattern and will use it going forward.
- [CSS styling basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics) - This is an amazing article which helped me finally understand CSS basics. I'd recommend it to anyone still learning this concept.

## Author

- Name - Amiko Elvis
- LinkedIn - (https://www.linkedin.com/in/amikoelvis)
- Twitter - [@ElvisAmiko](https://www.twitter.com/ElvisAmiko)

## Acknowledgments
Frontend Mentor:
Thank you for providing this great challenge and for helping me improve my front-end development skills.
