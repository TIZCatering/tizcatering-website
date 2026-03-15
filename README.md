# Tiz Catering Website

**Domain:** tizcatering.com
**Business:** Nigerian catering in Calgary, AB, Canada

## Deployment (Netlify)

1. Push this folder to a GitHub repo (or drag and drop to Netlify)
2. Connect the repo to Netlify
3. Build settings are in `netlify.toml` (no build step needed, static site)
4. Set custom domain to `tizcatering.com` in Netlify dashboard
5. Enable HTTPS (automatic with Netlify)

## Form Handling

The order form uses Netlify Forms (detected automatically via `data-netlify="true"`).
Submissions appear in the Netlify dashboard under Forms.
Set up email notifications in Netlify: Site Settings > Forms > Form notifications.

## Files

- `index.html` : Full website (HTML, CSS, JS all inline)
- `logo.jpg` : Tiz Catering logo
- `netlify.toml` : Netlify build and redirect config
- `_redirects` : Netlify redirect rules

## Updating the Menu

All menu items are defined in the JavaScript `menuItems` array inside `index.html`.
Each item has: name, description, category, variants (size + price), and an emoji.
To add/edit/remove items, update that array and the site updates automatically.
