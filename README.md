<br />
<div align="center">
    <img src="./images/200w.gif" alt="Logo">
  </a>
  <br />
  <br />

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]

<h3 align="center">Code Snippets</h3>
<div align="left">
This is small collection of html/css that i frequently use for ease of access.

### Root
```css
:root {
    /* Colors */
    --violet: hsl(257, 40%, 49%);
    --magenta: hsl(300, 69%, 71%);  
    /* Typography */
    --heading-font: "Poppins", sans-serif;
    --body-font: "Open Sans", sans-serif;
    /* Font weights */
    --font-weight-regular: 400;
    --font-weight-bold: 600;
}
```

### Body
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    min-height: 100vh;
    font-family: var(--body-font);
    font-size: 16px;
    line-height: 1.5;
}

```

### Footer
```html
    <footer class="attribution">
        Challenged by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank" rel="noopener">Frontend Mentor</a>.
        Coded by <a href="https://www.frontendmentor.io/profile/sedaryildirim">Sedar Yildirim</a>.
    </footer>
```

```css
footer {
    margin-top: 2rem;
    text-align: center;
}

.attribution {
    font-size: 0.7rem;
    color: var(--dark-cyan);
}

.attribution a {
    color: var(--medium-cyan);
    text-decoration: none;
}

.attribution a:hover {
    text-decoration: underline;
}

```
</div>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/sedaryildirim/code-snippets.svg?style=for-the-badge
[contributors-url]: https://github.com/sedaryildirim/code-snippets/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/sedaryildirim/code-snippets.svg?style=for-the-badge
[forks-url]: https://github.com/sedaryildirim/code-snippets/network/members
[stars-shield]: https://img.shields.io/github/stars/sedaryildirim/code-snippets.svg?style=for-the-badge
[stars-url]: https://github.com/sedaryildirim/code-snippets/stargazers
[license-shield]: https://img.shields.io/github/license/sedaryildirim/code-snippets.svg?style=for-the-badge
[license-url]: https://github.com/sedaryildirim/code-snippets/blob/main/LICENSE.txt
[product-screenshot]: imgs/screenshot.png
