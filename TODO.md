### Adding the Volunteer Form Link

Search for `VOLUNTEER FORM LINK` in `index.html` and replace `#volunteer-form-placeholder`
with your Google Form URL (e.g., `https://forms.gle/YOUR_FORM_ID`).

### Adding Endorsements Content

Find the `endorsements-text` section in `index.html` and replace the placeholder notice
with the endorsements photo and paragraphs of text.

### Changing the Font

Open `styles.css` and update these two lines near the top:

```css
--font-primary: 'Open Sans', sans-serif;   /* body text */
--font-heading: 'Merriweather', serif;      /* headings  */
```

Also update the `@import url(...)` line at the top of the CSS file to load your preferred
Google Font (or remove it to use a system font).

