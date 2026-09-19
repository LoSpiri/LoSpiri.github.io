# Lorenzo Spiridioni (LoSpiri) — Portfolio

Personal portfolio at **[https://lospiri.github.io/](https://lospiri.github.io/)** (GitHub User Pages). Plain HTML & CSS, deployed with GitHub Actions.

The [`website`](https://github.com/LoSpiri/website) repository only redirects legacy `/website/` URLs to the user site.

## Development

1. Clone **`LoSpiri.github.io`** (primary repo for site content).
2. Edit HTML/CSS/JS locally and push to `main`; Actions deploys to Pages.
3. Canonical base URL for SEO: `https://lospiri.github.io` (see `sitemap.xml`, canonical tags, JSON-LD).

## SEO checklist (after deploy)

- [Google Search Console](https://search.google.com/search-console): property `https://lospiri.github.io`, submit sitemap `https://lospiri.github.io/sitemap.xml`, request indexing for the home page.
- GitHub profile: set website to `https://lospiri.github.io`.
- LinkedIn: add the same URL in the contact/website field.
- Optional: profile README repo with a link to the site.

## Structure

```
├── index.html           # Home (Person schema, Open Graph)
├── miscellaneous.html
├── projects.html
├── articles.html
├── robots.txt
├── sitemap.xml
├── css/style.css
├── js/components.js
└── .github/workflows/static.yml
```

## Portrait image

Add `img/portrait.jpg` for the bio and `og:image` (required for rich snippets).
