# Yotor Landing Page

A pixel-perfect implementation of the Yotor church management system landing page, built from the Figma design.

**Repo:** https://github.com/eyosiyasketema1/yotor-landing
**Figma:** https://www.figma.com/design/zQq6RHQQogtcKplk8vZI8L/Yotor-Landing-page

## Stack

- Pure HTML5
- Vanilla CSS (no frameworks)
- Minimal vanilla JavaScript

## Project structure

```
yotor-landing/
├── index.html         Main landing page
├── INSTRUCTIONS.md    Build brief used as reference for Claude
├── assets/            Logos, icons, images
│   ├── yotor-logo.svg
│   └── Globe.svg
├── .gitignore
└── README.md
```

## Local preview

Open `index.html` directly in your browser, or run a local server:

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000

## Responsive breakpoints

- Desktop: default
- Tablet: ≤ 1024px (hamburger menu)
- Mobile: ≤ 768px

## Sections progress

- [x] Navigation bar
- [ ] Hero
- [ ] Logo strip
- [ ] CTA bar
- [ ] Features (Yotor Provides)
- [ ] Feature grid
- [ ] Focus banner
- [ ] Testimony
- [ ] Old way banner
- [ ] Reviews
- [ ] How it works
- [ ] Pricing
- [ ] Mobile app
- [ ] FAQ
- [ ] Better way CTA
- [ ] Footer
