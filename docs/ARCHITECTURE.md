# Architecture

This portfolio is a multi-page static website with no build step or runtime dependencies. Home, About, Services, Projects, and Contact each have a separate HTML file and use standard links for navigation.

## Files

- `index.html`, `about.html`, `services.html`, `projects.html`, and `contact.html` contain the separate pages and shared navigation.
- `styles.css` defines the responsive layout, visual theme, and mobile navigation presentation.
- `script.js` provides the small-screen navigation toggle and current footer year.
- `assets/` contains the CV document and project preview images referenced by the page.

## Runtime

The browser loads the stylesheet and deferred script directly from `index.html`. Project and CV links are relative paths, so the site can be hosted from a static file server or opened locally.
