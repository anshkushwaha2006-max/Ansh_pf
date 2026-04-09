# Project Guidelines

## Code Style
- Keep markup semantic and readable in `index.html`.
- Prefer small, targeted edits; avoid changing layout structure unless requested.
- Keep styles centralized in `style.css` and preserve existing naming patterns.

## Architecture
- `index.html` contains all page sections: header, about, services, portfolio, and contact.
- `style.css` controls layout, theme, and responsive behavior.
- `images/` stores static visual assets referenced by the page.

## Build and Test
- This is a static site with no package manager or build pipeline.
- Run locally with an HTTP server (not `file://`), for example:
  - `python -m http.server 5500`
- Validate by opening `http://localhost:5500/index.html` and checking responsive layout.

## Conventions
- Use relative asset paths (for example `images/cover.jpeg`) for portability.
- Do not leave placeholder copy (for example lorem ipsum) in user-facing sections.
- Keep portfolio copy aligned to video editing/documentary services and creator branding.
