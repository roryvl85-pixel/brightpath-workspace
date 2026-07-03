# Services Pilot — Website

One-page static site for the Services Pilot (ghostwriting + workflow automation), built as a free pilot to collect early testimonials.

- `index.html` — page content
- `styles.css` — styling (light/dark aware)

## Tally form

The intake form is embedded via Tally in `index.html`. Search for `REPLACE_WITH_TALLY_FORM_ID` and swap in the real Tally form ID once the form is built.

## Deploy

Static site, no build step. Point Netlify at this repo with:
- Build command: (none)
- Publish directory: `/`
