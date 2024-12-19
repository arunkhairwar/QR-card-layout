# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help me improve my coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![scanner is not in working condition but it will work soon](./design/screenshot.png.jpg)

currently the scanner is not in working condition so nothing will happend after scanning, but i am going to make use it as a portfolio scanner, so that anyone can directly jump to my portfolio just by scanning it. 

### Links

- Solution URL: [GitHub Repositry](https://github.com/arunkhairwar/QR-card-layout.git)
- Live Site URL: [soon](#nothing)

## My process
- I bring the template and starter file from frontend mentor site 
- understand it and delete some unnessary files, then create a custom folder and files, and wrote own code
- then create a remote respositry on github, and push it. *i was facing some conflicts and problem with branching, merging, restor the previous solution etc. with git, then i decided to clear my basic concept first with git & github then move forward, so i learn it.* 
- the resource is mention here: [resource](#Useful-resources) 
- i lack the consitency for few day's because i was feeling am too slow and unable to reach expecation. and this simple project is taking more time from me, - as compare to watching the tutorial and building one. *but i was wrong* 
- then after a week, i forget all my mistake, inconsistency, guilt and decide to finish it. i woke up early set the deep work session. did it. _still the responsiveness is missing i will be adding it soon_

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow 
<!--
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles
 -->


### What I learned

this project helped me to learn and explore more about version contorl and common use of it. like why we need to use it, and how important it is to manage our code. apart from this i learn about 
- how to achieve responsivenss using pure CSS code without any framework, 
- learn flexbox and it's usage. 

To see how you can add code snippets, see below:

```html
<div class="card-layout">
      <div class="QR">
        <img src="/images/image-qr-code.png" alt="qr" />
      </div>
      <div class="otherInfo">
        <h3>Visit My Portfolio by Scaning this QR</h3>
        <p>
          scan the QR to visit my portfolio and explore more about me. like past
          expreience, project etc.
        </p>
      </div>
    </div>
```
```css
.card-layout {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex-wrap: wrap;
  background-color: white;
  /* position: absolute; */
  margin-top: 70px;
  width: 250px;
  height: 400px;
  border: 2px solid black;
  border-radius: 20px;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
