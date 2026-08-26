# Sikku — moved

The website now lives at <https://offline-works.github.io/sikku/>, in the `offline-works` organisation. Edit it
there; nothing in this repository is maintained.

**Do not delete this repository.** Two things in it are still load-bearing:

- `privacy.html` — the full policy text, deliberately *not* a redirect, because
  this URL is the privacy policy on record in App Store Connect and is compiled into builds now in review. It can become a redirect only once a build has shipped naming the new
  URL.
- `icon-180.png` and `icon-512.png` — still hot-linked by the sibling cards and
  Open Graph tags on the other sites.

`index.html` is a client-side redirect to the new site: GitHub Pages serves
static files only and cannot issue a real 301.
