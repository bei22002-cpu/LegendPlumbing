# Legend Plumbing — Website

A 4-page static website: Home, Services, About, Contact.

## What's inside
- `index.html`, `services.html`, `about.html`, `contact.html` — the pages
- `css/style.css` — all styling
- `js/script.js` — mobile menu + scroll animations
- `images/` — your jobsite photos and logo

## How to put this online
This is a plain static site (no database, no build step), so any basic web host works:
1. **Easiest:** Drag the whole folder into [Netlify Drop](https://app.netlify.com/drop) — live in about 10 seconds, free.
2. **Custom domain:** Buy a domain (e.g. legendplumbing.org) through Namecheap/GoDaddy, then connect it to Netlify, Vercel, or any standard hosting provider, and upload these files.
3. **Already have a host/cPanel?** Upload everything in this folder into the `public_html` (or root) directory.

## Things to double-check / personalize before launch
- **Service area & hours** on the Contact page are reasonable placeholders based on your area code — confirm the towns and hours are right.
- **About page bio** is a starting draft — feel free to swap in your own words, how long you've been doing this, licensing details, etc.
- **Contact form** opens the visitor's email app pre-filled to Tyler@legendplumbing.org (no backend/server needed). If you'd rather have it submit silently to your inbox, that needs a small form service (e.g. Formspree) — happy to wire that up if you want it.

## Editing content
Everything is plain HTML/CSS, so any text can be changed directly in the `.html` files with a text editor. Photos live in `images/` — to swap one out, replace the file and keep the same filename, or update the `src=` path in the HTML.
