# Public legal and support site — KoleQuant games

This public repository contains only legal, privacy, support, and advertising-authorization resources for KoleQuant games. GitHub Pages deploys the site automatically from the `main` branch. The Big Eye documents remain at their existing root paths; Crystal Path: Infinity has isolated pages under `crystal-path/`.

## The Big Eye

Published resources:

- Privacy Policy: https://georgi-cole.github.io/big-eye-legal/privacy-policy.html
- Terms of Use: https://georgi-cole.github.io/big-eye-legal/terms-of-use.html
- Support: https://georgi-cole.github.io/big-eye-legal/support.html

## Crystal Path: Infinity

After the hosting PR is merged and deployed, the public paths will be:

- Index: https://georgi-cole.github.io/big-eye-legal/crystal-path/
- Privacy EN/BG: `crystal-path/privacy.html`, `crystal-path/privacy-bg.html`
- Terms EN/BG: `crystal-path/terms.html`, `crystal-path/terms-bg.html`
- Purchases and refunds EN/BG: `crystal-path/purchases.html`, `crystal-path/purchases-bg.html`
- Support and account deletion EN/BG: `crystal-path/support.html`, `crystal-path/support-bg.html`

The Crystal Path app links to the public URLs from its Settings and sign-in UI. The isolated directory preserves The Big Eye's existing legal links.

## Advertising authorization

When AdMob supplies the real publisher identifier, add a root-level `app-ads.txt` using the exact authorized entry from AdMob. Do not publish a guessed or placeholder publisher ID.
