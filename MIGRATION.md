# User site: `https://lospiri.github.io/`

SEO tags and `sitemap.xml` already use the **root** URL. Finish migration with one rename (no second repository).

## 1. Rename this repository

1. Open [github.com/LoSpiri/website/settings](https://github.com/LoSpiri/website/settings).
2. Under **Repository name**, change `website` → **`LoSpiri.github.io`**.
3. Confirm. GitHub Pages will serve the site at `https://lospiri.github.io/` instead of `/website/`.

Update your local clone:

```bash
git remote set-url origin git@github.com:LoSpiri/LoSpiri.github.io.git
```

## 2. Pages

Ensure **Settings → Pages → Build and deployment** uses **GitHub Actions** (workflow [`.github/workflows/static.yml`](.github/workflows/static.yml)).

## 3. Search Console

- Add property `https://lospiri.github.io` (or verify via the existing meta tag on the home page).
- Submit sitemap: `https://lospiri.github.io/sitemap.xml`.
- Request indexing for the home page.

## 4. Profiles

- **GitHub (LoSpiri):** set website to `https://lospiri.github.io`.
- **LinkedIn:** same URL in the website field.

## Cleanup (optional)

If a duplicate repo was created under another account (e.g. `lospiri-verkko/LoSpiri.github.io`), delete it to avoid confusion.
