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
This project is a Frontend Mentor challenge solution where the goal was to build a simple, responsive webpage that displays a QR code card. The card includes a QR code image and a short descriptive text underneath. The focus of the project was on HTML structure, CSS styling, and layout techniques.
The project also demonstrates basic Git and GitHub workflow, including adding and updating files such as HTML, CSS, and images.
This simple project is a great exercise in layout, styling, and design precision, making it ideal for practicing frontend fundamentals.


### Screenshot
Here is a link to the image of my final solution:
[Screentshot of final solution](Final.png)


### Links
Live Site URL: 
[Add live site URL here](https://fm-challenge1-nine.vercel.app/)


## My process
- I started off with adding HTML to the document. This was a quick and simple process as it only required a few short sentences, link the CSS to the HTML, adding an image, and using semantic elements.
- I then moved on to my CSS. This part was a bit trickier for me. I began by setting up my design layout of where I wanted to the card to be. Eventually after a while, I managed to figure it out.
- I toyed around with some more CSS code to trial-and-error it, seeing what worked and what did'nt. What changes were being made in real time, etc.
- Finally figured it out, and it all came together to be the final solution (seen in the links above).

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned
A steep curve I struggled with the most was aligning the entire card to the center, both vertically and horizontally, which I still feel I didn't full nail it into the coffin.
But through research and trial-and-error, I found that this piece of code helped the most:

```css
body{
    min-height: 100vh;
    max-height: 90vh;
    display: flex;
    justify-content: center; 
    align-items: center;  
}
```

It was also quite funny to me. I finally learnt how to add custom fonts to a webpage. We weren't taught this in our module, but I finally got it correct:

```html
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
```

```css
body{
    font-family: 'Outfit', sans-serif;    
    font-size: 15px;
}
```


### Continued development
I still don't feel too confident with aligning my objects, especially when it comes to aligning them in the center. So I do feel I need to put in more practice with that. Also just constantly refreshing my mind on the basics of HTML and CSS. When you're studying different modules and you don't get enough practice in you tend to forget. So this was a good refresher for me, but still a lot I need to focus on.


### Useful resources
- [An Interactive Guide to CSS Grids](https://www.joshwcomeau.com/css/interactive-guide-to-grid/) - This is an amazing article which helped me build my knowledge and understand on CSS Grid. It's a fun, unique, interactive guide and I'd recommend it to anyone still learning or struggling with the concept.


## Author
- LinkedIn - [Ashton Blaze Berridge](https://www.linkedin.com/in/ashton-berridge-6ba4ab255/)
- Frontend Mentor - [@ashyb13](https://www.frontendmentor.io/profile/ashyb13)
- GITHUB - [@ashyb13](https://github.com/ashyb13)


## Acknowledgments
I worked alongside a fellow friend of mine, Net-Runner-Syndrome. He has really helped me grip the understanding of things I tend to forget and is always willing to help me/anyone who needs it.

Here's a link if you'd like to check out some of his stuff:
GITHUB - [@Net-Runner-Syndrome](https://github.com/Net-Runner-Syndrome)
