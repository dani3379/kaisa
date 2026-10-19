# Kaisa — Chess Club Website Concept

A responsive one-page website concept built with HTML and CSS: burgundy-and-cream styling, clear section navigation, a photographic hero, and a reusable three-card layout. This static portfolio demo shows work relevant to small-business landing pages, club websites, and existing-site visual improvements.

[Open the live website demo](https://dani3379.github.io/kaisa/)

The page is a design/development example, not an operating club, membership, news, or tournament service. It does not claim a commissioned client relationship or depict real club events.

## Implemented features

- Main navigation and footer section links target existing Home, About, Tournaments, and Contact sections.
- CSS Grid adapts the hero and cards to a single column below 800px; navigation wraps on narrow screens.
- Locally hosted supporting photos use consistent card crops, alt text, lazy loading, and asynchronous decoding.
- Semantic page sections, visible keyboard-focus styles, and a reduced-motion scroll setting are included. This is not a completed accessibility-conformance audit.
- The public page uses no JavaScript framework, package installation, build step, or backend.

The three supporting stock photographs are illustrative rather than records of club members, facilities, or events. Their sources and license record are in [CREDITS.md](CREDITS.md). The original hero assets predate this update; their provenance has not been independently established by this copy audit.

## Demonstration boundaries

The membership button, membership/footer social links, and contact text are explicitly labelled placeholders. There is no registration, payment, contact form, live news feed, event-results system, or working social-account integration.

The legacy `admin/` folder contains Netlify CMS/Identity configuration. It is **inactive on this GitHub Pages demo**: Pages does not supply its Git Gateway backend, and some admin/upload paths assume a domain-root deployment. No CMS login or authenticated publishing workflow was tested. The `_redirects` file is a Netlify configuration artifact, not GitHub Pages routing.

## Preview locally

From the repository directory, serve the static files with any local HTTP server, for example:

```text
python -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000/`. There is no dependency-install or application-build step. On GitHub Pages the existing English version is published from the root of `main`; the recovered Bulgarian multipage prototype is a separate archive and has not replaced it.

## Copy-audit scope

The 20 October 2026 audit inspected the HTML, CSS, image references, credits, and legacy admin configuration. Main section targets and local resource paths were checked. The text now labels the site as a portfolio demo without changing its layout, photographs, or styles. This audit does not add a new cross-browser, device, accessibility, or CMS verification claim.
