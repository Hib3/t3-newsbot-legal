# t3-newsbot legal pages

This folder contains two static pages intended for the Reddit Devvit "App details" form.

- `terms.html`
- `privacy.html`

Recommended hosting: GitHub Pages.

## Quick publish via GitHub Pages

1) Create a new GitHub repository (example: `t3-newsbot-legal`).
2) Upload these files to the repository root.
3) In GitHub: Settings -> Pages -> Build and deployment -> Source: Deploy from a branch.
4) Select Branch: `main` and Folder: `/ (root)`.
5) After it publishes, use these URLs in the Devvit portal:

- https://Hib3.github.io/t3-newsbot-legal/terms.html
- https://Hib3.github.io/t3-newsbot-legal/privacy.html

## Fetch Domains
This app fetches the public RSS feed from b.hatena.ne.jp (hotentry.rss) to auto-post one random entry every 30 minutes to r/Twitter3.
No user personal data is collected or stored outside Reddit.
