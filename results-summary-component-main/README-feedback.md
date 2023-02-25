## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

- SCREENSHOOT HORIZONTAL 
![](./design/ScreenShoot_horizontal.jpeg)

- SCREENSHOOT VERTICAL
![](./design/ScreenShoot_vertical.jpeg)


### Links

- Solution URL: https://marlenecondesso.github.io/result-summary-component/results-summary-component-main/index.html
- Live Site URL: https://marlenecondesso.github.io/result-summary-component/results-summary-component-main/index.html

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

```css
    -set full size page:
        .page{
            min-height:100vh;
        }
    -set background color with gradiant:
        .background-color-fill{
            background-image: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
        }
    -set responsive layout when user reduce size window:
        @media screen and (max-width: 800px){ 
            .cssUpdate{
                ------
            }
        }

    -use rem or em when set font-size:
        .text{
            font-size: 1.3rem;
        }
```
```html
    -Wrap the page's whole main content in the <main> tag:
        <body>
            <main>
                <div class="attribution">
                Challenge by<a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
                Coded by <a href="#">Marlene Condesso</a>.
                </div>
            </main>
        </body>
```
## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments
I would like to thanks the user from frontendmentor.io, @Melvin Aguilar for give me your own feedback and tips on 'community feedback' of my last challenge, 'qr code challenge'. 
It was very usefull in this challenge. THANK YOU. 

