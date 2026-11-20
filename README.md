# System Design Journal

A minimal engineering journal for a 30-day system design interview practice challenge.

## Website

The site is a lightweight static website built with HTML, CSS, and JavaScript. It is designed to deploy through GitHub Pages.

## Local preview

Open `index.html` in a browser, or run a simple static server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Daily practice format

Each design should cover:
1. Functional and non-functional requirements
2. Back-of-the-envelope capacity estimates
3. API design and data model
4. High-level architecture
5. Deep dives into bottlenecks and failure modes
6. Trade-offs and follow-up improvements

## Publishing

GitHub Actions deploys the repository root to GitHub Pages whenever changes are pushed to `main`. Enable Pages in repository Settings → Pages and select GitHub Actions as the build and deployment source.