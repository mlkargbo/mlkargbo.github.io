# Mohamed Lamin Kargbo — Personal Portfolio Website

A clean, minimal personal portfolio for a Solutions Data Architect. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies beyond two CDN font families.

---

## Live Site

Hosted on GitHub Pages: `https://your-username.github.io`

---

## Tech Stack

| Layer | Choice | Reason |
|-------|--------|--------|
| Markup | HTML5 (semantic) | Accessible, SEO-friendly structure |
| Styles | Vanilla CSS with custom properties | Zero runtime, full design control |
| Scripts | Vanilla JavaScript (ES5-compatible) | No dependencies, instant load |
| Fonts | [Cabinet Grotesk](https://www.fontshare.com/fonts/cabinet-grotesk) + [Satoshi](https://www.fontshare.com/fonts/satoshi) via Fontshare | Distinctive, not overused |
| Icons | [Google Material Symbols Rounded](https://fonts.google.com/icons) | Consistent, scalable, ligature-based |

---

## Project Structure

```
mlk-portfolio/
├── index.html      # All content and page structure
├── style.css       # Design tokens, layout, components
├── base.css        # CSS reset and global foundations
└── README.md
```

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Headline, profile card, key stats, CTAs |
| 2 | **About** | Summary copy and Core Domains grid |
| 3 | **Experience** | Chronological timeline (2017 – present) |
| 4 | **Skills** | 6 categorised skill cards with tech pills |
| 5 | **Certifications** | 12 professional certifications |
| 6 | **Fellowships & Awards** | Afrika Kommt! AK11, OYW Ambassador, Perplexity Fellowship, ForbesBLK |
| 7 | **Education** | Johns Hopkins University & Saint Monica University |
| 8 | **Contact** | LinkedIn, email, phone, and CTA card |

---

## Design System

### Color Palette

| Role | Light | Dark |
|------|-------|------|
| Background | `#F4F3EF` | `#0E0F13` |
| Surface | `#F8F7F3` | `#13151B` |
| Text | `#1A1916` | `#D4D5D9` |
| Primary (blue) | `#1C4ED8` | `#60A5FA` |
| Accent (teal) | `#0891B2` | `#22D3EE` |

### Typography

- **Display / Headings:** Cabinet Grotesk — weight 800, letter-spacing `-0.03em`
- **Body:** Satoshi — weight 400–500, line-height 1.6

### Spacing

4px base unit scale — `--space-1` (4px) through `--space-32` (128px).

---

## Features

- **Light & dark mode** — respects system preference, manual toggle in the nav
- **Scroll reveal animations** — content fades in on scroll via `IntersectionObserver`
- **Sticky header** — with backdrop blur and scroll-aware shadow
- **Smooth scroll** — all anchor nav links use native smooth scrolling
- **Responsive layout** — mobile-first, tested from 375px to 1440px
- **Accessible markup** — semantic HTML5, ARIA labels, keyboard navigable, WCAG AA contrast
- **Mobile hamburger menu** — collapses nav links on small viewports
- **SEO ready** — meta description, Open Graph tags, structured heading hierarchy

---

## Updating Content

All content lives in `index.html`. Key sections to update:

- **New job:** Add a `.timeline-item` block inside `#experience`
- **New certification:** Add a `.cert-card` block inside `#certifications`
- **New award/fellowship:** Add a `.award-card` block inside `#awards`
- **Contact details:** Search for `medikargbo@gmail.com` or `mohamedlaminkargbo`

### Adding a Material Icon

Icons use Google Material Symbols Rounded via ligature text:

```html
<span class="ms">icon_name</span>
```

Browse all icon names at [fonts.google.com/icons](https://fonts.google.com/icons).

---

## Deployment

### GitHub Pages (recommended)

1. Push all files to a repository named `your-username.github.io`
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Site goes live at `https://your-username.github.io`

### Updating the site

```bash
git add .
git commit -m "Update: describe your change"
git push
```

GitHub Pages redeploys automatically within ~30 seconds.

---

## Custom Domain (optional)

1. Purchase a domain from any registrar
2. In GitHub Pages settings, enter your custom domain
3. Add a `CNAME` DNS record pointing to `your-username.github.io`
4. Enable **Enforce HTTPS** in GitHub Pages settings

---

## License

This portfolio is personal — all written content, professional history, and personal details belong to Mohamed Lamin Kargbo. The code structure and design system may be freely reused and adapted.

---

*Built with ❤️ · May 2026*
