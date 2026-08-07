# Minimal Personal Homepage

A clean, responsive personal-site template inspired by the visual structure of mjboswell.com, with original placeholder copy and no copied imagery or branding.

## Edit

- Change `Your Name` in `index.html`.
- Replace the three `href="#"` social links.
- Replace the `.portrait-placeholder` block with an image, for example:

```html
<img class="portrait" src="portrait.jpg" alt="Portrait of Your Name">
```

Then add this to `styles.css`:

```css
.portrait {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  object-fit: cover;
}
```

## Run

Open `index.html` directly in a browser, or serve the folder with any simple static web server.
