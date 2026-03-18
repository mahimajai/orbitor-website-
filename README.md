# Orbitor — Digital Experience Website

A clean, fully static business/agency landing page built with plain HTML and CSS. Orbitor presents a professional digital services company with multiple sections, animated statistics, and a responsive layout — all in a single HTML file with no external dependencies.

---

## Live Preview

Open `indexx.html` directly in any modern browser — no build step or server required.

---

## Features

- **Navbar** — Logo, navigation links, and a "Get an Estimate" CTA button
- **Hero Section** — Bold headline, subtext, and a profile image
- **Features Section** — Three-column layout highlighting core services (Software Development, Expense Analysis, IT Growth)
- **Why Choose Us** — Descriptive copy alongside a 2×2 card grid of service highlights (Data Analysis, Web Development, Content Management, Mobility)
- **Banner / CTA** — Full-width background image overlay with a portfolio call-to-action
- **Portfolio Gallery** — Four-image photo grid showcasing past work
- **Animated Stats Counter** — JavaScript-driven counters for Projects Done, Users Worldwide, Countries, and Awards
- **Testimonials** — Four-card testimonial row with avatar images
- **Footer** — Company info, navigation links, support links, and contact details

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Inline `<style>` block — layout, flexbox, colors, typography |
| Vanilla JavaScript | Animated stats counter on page load |
| Unsplash (CDN) | Hero and portfolio images |
| RandomUser.me (CDN) | Testimonial avatar images |

> No frameworks, no libraries, no build tools — just a single `.html` file.

---

## Project Structure

```
orbitor-website-/
└── indexx.html   # The entire website — HTML, CSS, and JS in one file
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mahimajai/orbitor-website-.git
cd orbitor-website-
```

### 2. Open in browser

```bash
# macOS
open indexx.html

# Windows
start indexx.html

# Linux
xdg-open indexx.html
```

No installation or dependencies needed.

---

## Sections Overview

| Section | Description |
|---|---|
| Navbar | Brand logo + nav links + CTA |
| Hero | Headline, tagline, image |
| Features | 3-column service highlights |
| Why Choose Us | Left text + 4 feature cards |
| Banner | Background image + CTA box |
| Portfolio | 4-image gallery grid |
| Stats | Animated counters (orange bar) |
| Testimonials | 4 client review cards |
| Footer | Links, contact info, copyright |

---

## Customisation

Since everything lives in a single file, customisation is straightforward:

- **Brand colour** — Search for `#f05a28` (orange-red) and replace with your colour
- **Logo name** — Update the `.logo` div in the navbar
- **Nav links** — Edit the `<a>` tags inside `.navbar`
- **Hero text** — Edit the `<h1>` and `<p>` inside `.hero-text`
- **Stats targets** — Change the counter limits (`1349`, `98`, `30`, `11`) in the `<script>` block
- **Images** — Replace the Unsplash URLs with your own hosted images
- **Footer content** — Update company info, social links, and contact details

---

## Browser Support

Works in all modern browsers:

- Chrome / Edge (latest)
- Firefox (latest)
- Safari (latest)


## License

This project is open source. Feel free to use and adapt it for your own projects.
