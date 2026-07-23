# Yotor Landing Page — Section Structure

Top-to-bottom order of sections inside the page.

## Top of page

1. **Navigation bar** — sticky header. Logo + 4 nav links + language + Log in + Get Started for free + hamburger on tablet/mobile.

## Main content

2. **Hero** — `#home`
   - Title: *"A Secure and Reliable Solution to Manage Your Church"*
   - Trust badge, description, two CTA buttons, pastor photo with testimonial overlay

3. **Logo strip** — Trusted-by-churches marquee
   - 6 church logos scrolling on an infinite loop

4. **Stats** — By-the-numbers strip
   - 3 cards: Local Churches, Denominations, Church Leaders
   - Teal `OUR IMPACT` eyebrow (masked globe) + bold/muted description
   - Big teal Poppins numbers with `+` suffix, gray General Sans labels
   - Framed by edge-to-edge horizontal lines + vertical content-width lines
   - Scroll-reveal stagger + count-up animation (0 → target with ease-out cubic)

5. **Yotor Provides** — `#products`
   - Auto-cycling 6-tab carousel (Quick Board, Member Management, Team Management, Message, Finance, HR and Asset)
   - Loading-bar underline grows across the tabs and reveals each dashboard preview

6. **Focus More on Ministry** banner
   - Full-width photo card with overlay heading and yellow CTA button

7. **Bento — People, Resources and Oversight**
   - 5 feature cards: Get a clear overview, Easy to use!, Control your entire ecosystem (phone), End-to-end security, Finance management

8. **CTA bar** — "Everything you asked for…" tagline + yellow Get Started button

9. **Comparison** — Old way vs New way
   - Draggable before/after slider with two-way arrow handle, pulse animation, auto-demo on first scroll into view

10. **Testimony** — `#testimony`
    - Pastor video carousel (1 main + 2 thumbnails) — click a thumb to swap sizes in real time

11. **Reviews** — 4 testimonial cards
    - 5-star rating, quote, colored avatar tile — slides horizontally with infinite loop

12. **How It Works** — `#how-it-works`
    - 3 step cards (Create an account → Create your church account → Start using all features) over a dark teal banner with photo behind
    - Hover-reveal arrow on the gray buttons

13. **Pricing** — `#pricing`
    - 3 plan cards (Starter, Core "Recommended", Ministry)
    - Monthly / Yearly toggle with 20% OFF badge
    - Prices are placeholders (`ETB 000`) until real prices are confirmed

14. **Mobile App Download**
    - Heading, subhead, Google Play + App Store badges (linked, currently `href="#"`), 542×542 phone mockup

15. **FAQs**
    - 4-category nav (General Questions, Miscellaneous, Payment Information, Support team)
    - Animated accordion that swaps content per category

16. **Final CTA banner** — *"A better way to manage your church"*
    - Photo card with yellow "manage" accent + cyan "Yotor.church" button

## Bottom of page

17. **Footer** — two visual rows
    - **Top row (white):** logo (cyan-tinted) + tagline + social links (Telegram / YouTube / Facebook — brand-color hover) + 4 link columns (Navigation, Legal, Contact, Office) + copyright
    - **Bottom row (light gray):** giant "yotor.church" wordmark at 211px

---

**Total: 16 content sections** between the navigation header and the footer, plus the sticky `<header>` and the `<footer>` itself.

## Anchor links

Smooth-scroll targets (used by both the navbar and footer Navigation column):

- `#home` → Hero
- `#products` → Yotor Provides
- `#how-it-works` → How It Works
- `#pricing` → Pricing
- `#testimony` → Testimony

## Notes on interactions

| Section | Interactive behavior |
|---|---|
| Navigation | Hamburger toggle on ≤ 1024px |
| Logo strip | Pause-on-hover marquee, respects `prefers-reduced-motion` |
| Stats | Scroll-reveal stagger (fade + slide-up) plus count-up animation (0 → target) on first view |
| Yotor Provides | Auto-cycling loading bar, click any tab to jump, fade-swap of dashboard image + description |
| Comparison | Mouse drag, click anywhere on the card, touch, keyboard (arrows / Home / End), auto-demo on first view |
| Testimony video | Click a thumb to expand it to main size; main shrinks in real time. Left/right arrows rotate through pastors |
| Reviews | Left/right arrows slide cards horizontally with infinite loop |
| How It Works | Hover gray buttons → arrow slides in |
| Pricing | Monthly / Yearly toggle swaps prices |
| Mobile App | Both store badges are `<a>` links with hover lift |
| FAQs | Click category to switch question set; click question to expand/collapse |
| Footer socials | Hover lands on full Telegram blue / YouTube red / Facebook blue |
| Footer text links | Hover bumps to medium weight + 80% opacity |
