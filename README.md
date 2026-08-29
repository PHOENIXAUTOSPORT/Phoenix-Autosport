# Phoenix Autosport website

A simple 3-page static site: `index.html` (Home), `services.html` (Services), `contact.html` (Contact). No build step — plain HTML, CSS and one image.

## Files

- `index.html`, `services.html`, `contact.html` — the pages
- `styles.css` — shared styling for all three pages
- `assets/race-car.jpg` — hero image
- `netlify.toml` — tells Netlify there's no build step, just publish these files as-is

## Deploying

See the deployment steps Claude provided, or in short: push this folder to a GitHub repo, then in Netlify choose "Import an existing project" and point it at that repo. No build command is needed and the publish directory is the repo root.

## Contact form

The Contact page's form posts to FormSubmit (https://formsubmit.co) which forwards submissions to admin@phoenixas.nz. On the very first real submission, FormSubmit emails that inbox a one-time confirmation link — click it to activate the form. After that, every enquiry is delivered straight to the inbox automatically, no backend or server needed.
