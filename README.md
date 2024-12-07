# Frontend Mentor - Recipe page solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

welcome, this is my first frontendmentor challenge, I really enjoyed working on this challenge and I hope to continue with more in the near future, here is what my experience was like

### Screenshot

![desktop](./screenshot desktop.png)
![mobile](./screenshot mobile.png)

### Links

- Solution URL: [Add solution URL here](https://gmmaliel24.github.io/recipe-page-main/)
- Live Site URL: [Add live site URL here](https://gmmaliel24.github.io/recipe-page-main/)

## My process

it was a learning experience, I tested several of the knowledge I had in html and css, some were easier to implement than others, during the first day I created the structure in html and from the second day to the fourth day I implemented the design in css trying several options, and the fifth day I dedicated myself to correct small details and I finished the project, if you could give me your opinion and advice about my solution I would be very grateful.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<div class="nutrition">
        <h2>Nutrition</h2>
    
        <p>
          The table below shows nutritional values per serving without the additional fillings.
        </p>
        
        <table>
          <tr>
            <td>
              <div class="t">
                <p class="content">Calories</p>
                <p class="data">277kcal</p>
              </div>
            </td>
          </tr>
          <tr>
            <td>
              <div class="t">
                <p class="content">Carbs</p>
                <p class="data">0g</p>
              </div>
            </td>
          </tr>
          <tr>
            <td>
              <div class="t">
                <p class="content">Protein</p>
                <p class="data">20g</p>
              </div>
            </td>
          </tr>
          <tr>
            <td class="not">
              <div class="t">
                <p class="content">Fat</p>
                <p class="data">22g</p>
              </div>
            </td>
          </tr>
        </table>
      </div>
```
```css
/*cooking time*/
.time{
    width: 97%;
    border-radius: 5%;
    margin-left: 5px;
    padding: 10px;
    background-color: hsl(330, 100%, 98%);
}
/*title cooking time*/
.time h2{
    padding-left: 15px;
    color: hsl(332, 51%, 32%);
    font-size: x-large;
    font-family: "Outfit", sans-serif;
    font-optical-sizing: auto;
    font-weight: 600;
    font-style: normal;
}
/*cooking time markers*/
.time li::marker{
    color: hsl(332, 51%, 32%);
}
```

### Continued development

in the future I would like to improve my html and css coding, currently I want to learn javascript and react.

### Useful resources



## Author

- Website - [Gamaliel Aguilar](https://www.linkedin.com/in/gamaliel-aguilar-3b6674282/)
- Frontend Mentor - [@gmmaliel24](https://www.frontendmentor.io/profile/gmmaliel24)
- Twitter - [@gamm1108](https://x.com/gamm1108)
