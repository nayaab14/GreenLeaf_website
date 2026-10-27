# GreenLeaf Plant Store Website

A beginner-friendly multi-page website made with HTML, CSS and Bootstrap 5.

## Pages
- `index.html` — Home page with hero section and buttons
- `plants.html` — Plant cards and navigation buttons
- `prices.html` — Responsive table with sample prices
- `contact.html` — Form with text inputs, dropdowns, checkbox, textarea and buttons
- `css/style.css` — Shared custom styling for all pages

## Run locally
1. Extract `GreenLeaf_Website.zip`.
2. Open the extracted folder.
3. Double-click `index.html` to open it in your browser.
4. Internet is needed for Bootstrap, Google Fonts and the online plant photos because they use CDN/remote URLs. The page HTML itself opens locally.

## Publish online (GitHub Pages)
1. Sign in to GitHub and create a new public repository.
2. Upload the contents of this folder (upload `index.html`, `plants.html`, `prices.html`, `contact.html`, and the `css` folder; do not upload only the ZIP).
3. Open the repository's **Settings → Pages**.
4. Under the build/deployment section, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish and open the website URL shown on the Pages screen.

## Important
- The contact form is a front-end demo. It displays a success message in the browser but does not send or save data to a server. A real form needs a backend or form service.
- The prices and contact details are examples and can be edited.
- Keep the `css` folder beside the HTML files so the stylesheet path works.
