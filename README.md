# Cici Virtual Bookkeeping Services — Website

A responsive marketing website for **Cici Virtual Bookkeeping Services**, a virtual bookkeeping business serving Australian sole traders and small businesses. Built as a single-page site with fixed-fee package pricing, a services overview, and a lead-capture contact form.

**[Live demo →](#)** *https://lighthearted-figolla-a98666.netlify.app/*


## Features

- Responsive layout (desktop, tablet, mobile) with a working hamburger menu on small screens
- Package comparison section (Starter / Growth / Premium) plus a one-off services table
- FAQ accordion
- Contact form with client-side validation and a success confirmation state
- Scroll-reveal animations and a sticky, blurred header on scroll
- No build tools or frameworks — plain HTML, CSS, and JavaScript

## Tech stack

- **HTML5** — semantic markup
- **CSS3** — custom properties (design tokens), CSS Grid/Flexbox, no framework
- **Vanilla JavaScript** — no dependencies, no build step
- **Fonts:** [Inter Tight](https://fonts.google.com/specimen/Inter+Tight), [Inter](https://fonts.google.com/specimen/Inter), and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## Project structure

```
.
├── index.html      # Page markup
├── styles.css       # All styling (design tokens, layout, responsive rules)
├── script.js        # Nav toggle, scroll reveal, FAQ accordion, form validation
└── README.md
```

## Running locally

No build step required — it's static HTML/CSS/JS.

```bash
git clone https://github.com/<your-username>/cici-virtual-bookkeeping.git
cd cici-virtual-bookkeeping
```

Then either:
- Open `index.html` directly in a browser, or
- Serve it locally for a closer-to-production experience, e.g.:
  ```bash
  npx serve .
  ```

## Deployment

This site is a static site, so it deploys directly to [Netlify](https://netlify.com), [Vercel](https://vercel.com), or [GitHub Pages](https://pages.github.com) with no configuration:

**Netlify:**
1. Push this repo to GitHub
2. In Netlify: **Add new site → Import an existing project → GitHub**
3. Select this repo — no build command or publish directory overrides needed (`index.html` is at the root)

## Notes

- Contact form currently shows a success state on submit but does not send data anywhere — hook it up to a form backend (e.g. Netlify Forms, Formspree) or your own API to make it functional.
- Placeholder contact details (email/phone) in `index.html` should be replaced with real business details before going live.

## License

This project is for portfolio/demonstration purposes.
