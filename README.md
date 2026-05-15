# Lucky Dragon Arcade

Public website for Lucky Dragon Arcade — 9524 Monroe Rd, Charlotte, NC 28270.

Static site (HTML/CSS/JS), no build step. Hosted on GitHub Pages.

## Local preview

Open `index.html` in a browser, or run a tiny server from this directory:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Editing

- Hours, address, copy: `index.html`
- Colors, layout, type: `styles.css`
- Footer year, smooth scroll: `script.js`

## Form

The booking form currently uses a `mailto:` action that opens the visitor's
email client addressed to `angeljinyi@gmail.com`. To switch to a hosted form
(recommended), sign up at https://formspree.io and replace the form's `action`
with the Formspree endpoint, then remove `enctype="text/plain"`.
