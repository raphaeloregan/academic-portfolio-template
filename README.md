# Academic Portfolio Template

A lightweight, accessible multi-page academic portfolio built with plain HTML and CSS.

## What’s included

- Home page with profile, interests, and featured work
- Work index page linking to project/case-study pages
- CV page
- Contact page
- Custom 404 page
- `sitemap.xml` and `robots.txt` for discoverability

## Accessibility and UX defaults

- Semantic page structure (`header`, `main`, `section`, `footer`)
- Consistent primary navigation across all pages
- Descriptive link labels (e.g., **Work**, **CV**, **Contact**)
- Mobile-friendly layout via responsive CSS

## Quick start

1. Clone this repository.
2. Open `index.html` in your browser to preview.
3. Replace placeholder text and links with your own details.
4. Deploy to GitHub Pages, Netlify, or any static host.

## Customization checklist

Update these placeholders across the site:

- `Your Name`
- `Your Job Title`
- `Your Institution`
- `Year`
- `yourfullname@example.com`
- `yourlinkedinurl`
- `https://example.com`

Then update project content:

- `example-1/` → your first project slug
- `example-2/` → your second project slug
- Project titles and summaries in `index.html` and `work/index.html`

## Navigation conventions used

To avoid broken links on static hosting, navigation uses relative links:

- From root pages: `./`, `work/`, `cv/`, `contact/`
- From subpages: `../`, `../work/`, `../cv/`, `../contact/`

If you add new folders, follow the same pattern.

## Deployment notes

- Keep file and folder names lowercase with hyphens (example: `climate-risk-analysis/`).
- Ensure each project folder has an `index.html`.
- Update `sitemap.xml` after adding or renaming pages.

## License

Free to use and adapt for personal academic portfolios.
