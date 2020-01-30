# 1.2.1 - CSS or Counterfeit Stainless Steel

---

_*actually it's Cascading Style Sheets_

---

<img src='./assets/html_js_css.jpg' />

---

- We use CSS to change the look of our content.
- CSS is used to change page layout, colors, fonts, text-sizes, image size, etc…
it can also be used to add images,
- You can do almost anything _presentational_ with CSS.
- You are limited only by your knowledge of CSS. (and your grit)

---

## Link CSS to an HTML page
you dont want to write CSS in HTML, so yu need to link it.
```html
<head>
    <link href="main.css" rel="stylesheet">
</head>
```

The `<link>` tag is used to import the CSS file containing rules applying the styles to the DOM elements.

---

## CSS Selectors

CSS Selectors are used to specify on which elements to apply styling. 
never use id (unless you really have to), they are unique (just one per page)
id's are used for JS

| Type  | Example     | Note  |
| ----- | ----------- | ----- |
| class | `.my-class` | 👍👍  |
| tag   | `body`      |  👍   |
| id    | `#bacon`    |  🚫   |

---

### Example (using tags):
all lower case in HTML and CSS, no spaces (a space creates an extra class)
`<h1>My Amazing Blog</h1>`

```css
h1 {
    font-size: 32px;
}
```

---

### Example (using classes):

`<h1 class="blog-title">My Amazing Blog</h1>
`
```css
.blog-title {
    font-size: 32px;
}
```

---

### Example (using ids):

`<h1 id="blog-title">My Amazing Blog</h1>
`
```css
#blog-title {
    ...don't do it.
    use a class instead
}
```

---

When styling HTML, we should

- ALWAYS use classes.
- SOMETIMES use HTML tags.
- NEVER use ids.
- NEVER EVER use ids. 🙏

---