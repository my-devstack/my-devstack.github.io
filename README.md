# MyDevStack

> **Local AWS Control Panel** — MyDevStack is the UI only (Vue frontend + Go proxy). It ships no emulator; point it at any AWS-compatible local endpoint you already run. Create, edit, and delete resources across **25+ AWS services**. No AWS account required.

This repository hosts the [MyDevStack](https://github.com/my-devstack/mydevstack) landing page at **[my-devstack.github.io](https://my-devstack.github.io)**.

## Tech Stack

- **HTML5** — Single-page marketing site
- **Tailwind CSS** — Utility-first styling (CDN)
- **Google Fonts** — Inter (UI) + JetBrains Mono (code)
- **GitHub Pages** — Hosting

## Site Files

- `index.html` — landing page (single file, no build step)
- `robots.txt` — allows all crawlers, points to sitemap
- `sitemap.xml` — single URL entry for the landing page
- `logo.svg`, `screenshots/` — static assets referenced from the page

## Development

No build step required. Just open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server 8081
# open http://localhost:8081
```

## Related

| Repo | Description |
|------|-------------|
| [my-devstack/mydevstack](https://github.com/my-devstack/mydevstack) | MyDevStack application (Go backend + Vue frontend) |

## License

MIT
