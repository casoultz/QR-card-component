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


## Overview
This is a newbie challenge I took up to practice my html and css skills. The challenge was about using html and css to create an identical QR card component. 

### Screenshot

[C:\Users\CHARVEE\OneDrive\Desktop\QR Comp.pjt\Screenshot(2).png]

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [https://github.com/casoultz/QR-card-component]
- Live Site URL: [https://casoultz.github.io/QR-card-component/]

## My process
Since I have practiced 2-3 similar projects before this, it was a pretty quick process without many problems.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learnt how to center div elements in both the horizontal as well as the vertical axis. 

```html
 <div class="box"><img id="qr-code" src="image-qr-code.png" alt="qr-code" width="270">
```
```css
.container {
    position: absolute;
    z-index: 1;
    background-color: white;
    width: 290px;
    height: 460px;
    border-color: white;
    border-style: solid;
    border-radius: 15px;
    top: 50%;
    transform: translateY(-50%);
    box-shadow: 0 0 20px -10px;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I want to continue working on my css grid skills and media queries..

### Useful resources

- [https://www.w3schools.com] - Whenever I was stuck somewhere it helped me out.

## Author

- Frontend Mentor - [@casoutlz](https://www.frontendmentor.io/profile/casoultz)
- Twitter - [@casoultz](https://www.twitter.com/yourusername)

