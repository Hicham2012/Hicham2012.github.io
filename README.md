# Frontend QR-Code

This was a simple HTML and CSS work, where you can present a QR-Code in a unique way, and let people scan it.
Feel free to inspire from it when you creating your own QR-Code for your website or your portfolio 😀

## Welcome 🤗
I wanna thank you firstly for checking on my humble work. If you find any issue, please feel free to correct me.

## Equipements 🤓
Here is what I used to make the webpage:
| Editor | Languages | Frameworks |
| --- | ---| --- |
| [Vs code](https://code.visualstudio.com/)| Vanilla HTML and CSS | None|

I beleive you can use any text editor to make this, [Replit](https://replit.com/~) for example...

## Code 🧐
For the code, all you need to remember is that **HTML is used to structure** while **CSS is used to style**. And the way to display them can be different from each person.
Here is the HTML code I made for this one

```html
<body>
    <main>
        <div class="column">
            <div class="qr-code">
                <img src="/qr-code-component-main/images/image-qr-code.png" width="340px" style="max-width: 380px ; border-radius: 15px" height="310px" />
            </div>
            <div class="comments">
                <p class="title">Improve your front-end skills by building projects</p>
                <p class="description">Scan QR code to visit front-end mentor and take your coding skills to the next level.</p>
            </div>
        </div>
    </main>

    <div class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded by <a href="https://www.frontendmentor.io/profile/Hicham2012" target="_blank">Hicham ZAADLA</a>.
    </div>
</body>
```
### No need to copy it, just understand the structure instead
```
 - body
 - column
    - QR-code (image)
    - Title
    - -Description
 - footer
```

And here is the code for CSS, btw I am a linear-gradient maniac so I may use it for every webpage lol
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');
body {
    display: inline;
    background: rgb(58, 177, 180);
    background: linear-gradient(90deg, rgba(58, 177, 180, 1) 0%, rgba(29, 124, 253, 1) 50%, rgba(69, 239, 252, 1) 100%);
}

.column {
    align-items: center;
    display: flex;
    justify-content: center;
    flex-direction: column;
    border-color: black;
    width: 370px;
    height: 507px;
    margin: 100px auto auto auto;
    background: white;
    border-radius: 30px;
    padding-top: 35px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    margin-top: 25px;
}

.title {
    font-family: 'Outfit', sans-serif;
    margin-left: 20px;
    font-size: 28px;
    font-weight: bold;
    margin-top: 15px;
    margin-left: 10px;
    text-align: center;
    margin-bottom: 0;
}

.description {
    color: grey;
    font-family: 'Outfit', sans-serif;
    font-size: medium;
    margin-left: 20px;
    text-align: center;
    font-size: 20px;
    font-weight: 400;
    margin-right: 20px;
    margin-bottom: 50px;
    margin-top: 15px;
}

.qr-code {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 15px;
}

.attribution {
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    margin-top: 67px;
    color: white;
    font-size: 12px;
    font-family: sans-serif;
    text-decoration: none;
}

.attribution a {
    color: black;
    text-decoration: none;
}
```
I think the code is self-explanatory, so feel free to enjoy making your own CSS too, **Artists**🎨

## Shoutout 🙏
I wanna thank [frontend Mentor](www.frontendmentor.io) for making funny challenges.

  ### Again, please feel free to correct me if I made any issue 🙌