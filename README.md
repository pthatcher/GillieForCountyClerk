# GillieForCountyClerk
Website for GillieForCountyClerk.com

## Customization Guide

### Adding Images

Place your images in the `images/` directory:

| File | Purpose |
|---|---|
| `images/hero.jpg` | Full-width hero banner at the top of the page |
| `images/about.jpg` | Portrait photo in the "About Me" section |
| `images/endorsements.jpg` | Photo in the "Endorsements" section |

Once images are placed, update `index.html` to replace each placeholder `<div>` with an `<img>` tag.
Search for `HERO IMAGE`, `ABOUT PHOTO`, and `ENDORSEMENTS PHOTO` comments in `index.html` for exact locations.

### Adding the Volunteer Form Link

Search for `VOLUNTEER FORM LINK` in `index.html` and replace `#volunteer-form-placeholder`
with your Google Form URL (e.g., `https://forms.gle/YOUR_FORM_ID`).

### Adding Endorsements Content

Find the `endorsements-text` section in `index.html` and replace the placeholder notice
with the endorsements photo and paragraphs of text.

### Changing the Font

Open `css/styles.css` and update these two lines near the top:

```css
--font-primary: 'Open Sans', sans-serif;   /* body text */
--font-heading: 'Merriweather', serif;      /* headings  */
```

Also update the `@import url(...)` line at the top of the CSS file to load your preferred
Google Font (or remove it to use a system font).

### Color Scheme

All brand colors are defined as CSS variables in `css/styles.css`:

```css
--color-indigo:    #262163;
--color-turquoise: #06B4FD;
--color-red:       #FF2C35;
--color-white:     #FFFFFF;
```

## File Structure

```
index.html          ← Main (single-page) website
css/
  styles.css        ← All styles; font & color variables are at the top
js/
  main.js           ← Mobile navigation toggle
images/             ← Place your photos here (see above)
```
