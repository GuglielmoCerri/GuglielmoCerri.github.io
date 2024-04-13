# My Portfolio Website

Welcome to my portfolio website! This repository contains the source code of my personal site, which is hosted on GitHub Pages.

## Forking and Customization

On my site, I've included a contacts section that uses a Formspree form to handle emails sent by users. 

Please follow these steps after forking the repository:

1. Go to [Formspree](https://formspree.io/) and create a free account if you haven't already.
2. After logging in, create a new form and obtain the unique token.
3. In the `index.html` file, find the following code:

```html
<form action="https://formspree.io/f/xbjwkqok" method="POST" class="contact__form grid" id="submit_form">
```

Replace the token `xbjwkqok` with your newly obtained Formspree token.

Thank you for your interest in my work and for collaborating to keep my inbox clean!
