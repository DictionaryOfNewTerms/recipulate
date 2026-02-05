<!-- Last updated: 2026-01-02 | Status: Active -->

# Architecture

## Stack

| Layer | Technology |
|-------|------------|
| Type | Static HTML site |
| Hosting | GitHub Pages |
| Domain | recipulate.com (via CNAME) |
| Styling | Inline CSS in index.html |

---

## Directory Structure

```
/
├── .claude/              # Claude Code project config
│   ├── CLAUDE.md         # Main project config
│   └── docs/             # Project documentation
├── index.html            # Main (only) page - definition of Recipulate
├── favicon.svg           # Site icon
├── CNAME                 # Custom domain config for GitHub Pages
├── robots.txt            # SEO - allow all crawlers
├── sitemap.xml           # SEO sitemap
└── README.md             # Repository readme
```

---

## Key Patterns

### Static Site Simplicity

This is intentionally a minimal static site:
- Single `index.html` with all content and styles inline
- No build process, no JavaScript framework
- Direct GitHub Pages hosting

### Content Focus

The site exists to define and explain the concept of "Recipulate":
- Reciprocity manipulation with hidden strings attached
- Educational content about consent in giving
- Resources for recognizing and addressing this behavior

### SEO

- `robots.txt` allows all crawlers
- `sitemap.xml` points to main domain
- Meta tags in `index.html` for social sharing
