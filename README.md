# Sikku — moved

The website now lives at <https://offline-works.github.io/sikku/>, in the
`offline-works` organisation. Edit it there; nothing in this repository is
maintained.

**Do not delete this repository, and do not touch `privacy.html`.** That path is
compiled into the app (`AboutSheet.swift`) and is the privacy policy on record in App Store Connect, compiled into builds now in review, so it has to keep
serving the full policy text from this exact URL. It may become a redirect only
once a build has shipped naming the new URL, and this repository may only be
deleted once no installed copy still points here.

`index.html` is a client-side redirect to the new site — GitHub Pages serves
static files only and cannot issue a real 301.

Nothing else is needed here. The icons were removed once the other sites stopped
hot-linking them.
