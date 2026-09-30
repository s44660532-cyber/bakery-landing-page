# Golden Crumb Bakery — Landing Page

A single-page, responsive landing page for a fictional artisan bakery. No build step, no dependencies — just HTML, CSS and a little JavaScript.

## Getting started

Open `index.html` in your browser, or serve the folder locally:

```bash
npx serve .
# or
python -m http.server 8000
```

## Structure

| File         | Purpose                                        |
| ------------ | ---------------------------------------------- |
| `index.html` | Page markup and content                        |
| `styles.css` | All styling, design tokens and responsive rules |
| `script.js`  | Mobile nav toggle and footer year               |

## Features

- Fully responsive layout (mobile nav, fluid grids, `clamp()` typography)
- Hero, menu, story, testimonials, visit/contact and footer sections
- CSS custom properties for easy re-theming
- `prefers-reduced-motion` support for animations
- Google Fonts: Fraunces (display) + Inter (body)

## Customizing

Change colors, spacing and radii in the `:root` block at the top of `styles.css`.
