# TinDog Landing Page

[![HTML5](https://img.shields.io/badge/HTML5-markup-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-blueviolet.svg)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A static landing-page project for a fictional dog-matching app, built with HTML and Bootstrap. It presents a hero section, feature highlights, testimonials, pricing cards, and a footer.

## Features

- Bootstrap grid, responsive utilities, and card components.
- Hero section with call-to-action buttons.
- Feature highlights and testimonial/press-logo area.
- Three sample pricing cards.
- Inline SVG icons and local image assets.
- Separate main and reference/solution HTML pages.

## Project Structure

```text
Bootstrap-Tindog-Project/
├── index.html
├── solution.html
├── css/
├── images/
└── goal images/
```

## Run Locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Keep the `css/` and `images/` directories alongside the HTML files so relative asset paths resolve.

The page loads Bootstrap from a CDN, so an internet connection is needed for the external framework and its JavaScript bundle.

## Concepts Practiced

- Bootstrap grid, containers, spacing, and responsive utility classes.
- Landing-page section composition.
- Pricing cards, calls to action, and inline SVG.
- Using local images and a third-party CSS/JavaScript framework.

## Limitations and Improvements

- This is a static UI exercise; the sign-up and download buttons do not connect to a real service.
- Review asset paths when moving files.
- Check layout behavior on smaller viewports and add meaningful alternate text to images.
- Consider extracting duplicated styling and validating the page markup.

## Third-Party Content

This project follows a common TinDog/Bootstrap learning exercise and includes local images and inline SVG content. Their original sources and redistribution terms are not fully documented in this repository. Verify rights before redistributing third-party material; this project's MIT License does not override those terms.

## License

Licensed under the MIT License. See [LICENSE](LICENSE) for details.
