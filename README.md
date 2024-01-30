### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](/design/desktop-design.png)
![](/design/mobile-design.png.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned how I can scale down images inside a flex container when I reduce viewport width.

```html
<h1>
  <section class="logos">
    <img src="images/logo-google.png" alt="google logo" />
    <img src="images/logo-ibm.png" alt="ibm logo" />
    <img src="images/logo-microsoft.png" alt="microsoft logo" />
    <img src="images/logo-hp.png" alt="hp logo" />
    <img src="images/logo-vector-graphics.png" alt="vector graphics logo" />
  </section>
</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
.logos {
  width: 80%;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.logos img {
  min-width: 0;
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/maziarja)

## Acknowledgments

"I appreciate Jonas Schmedtmann for his awesome courses on Udemy.
