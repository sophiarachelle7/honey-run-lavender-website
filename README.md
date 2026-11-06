# Honey Run Lavender website

Coming-soon site for honeyrunlavender.com. Plain HTML, no build step.

- `index.html` – the whole site (styled to match the pitch deck)

## Email signups
The page has `const FORM_ENDPOINT='';` near the bottom. Until it's set, the signup
button opens a pre-filled email to info@honeyrunlavender.com. To collect signups
automatically, create a free form at formspree.io and paste its URL
(e.g. `https://formspree.io/f/abcd1234`) into `FORM_ENDPOINT`.

## Publishing
Turn on GitHub Pages (Settings → Pages → Deploy from branch → main / root), then add
the custom domain honeyrunlavender.com and point the domain's DNS at GitHub Pages.
