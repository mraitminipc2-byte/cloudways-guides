# Cloudways Guides — written companion to MR AIT's video course

A static blog that turns MR AIT's Cloudways video course into written, step-by-step guides — with the original videos embedded in every lesson.

## Lessons

1. [Try Cloudways VPS for FREE: 2 Methods](guides/try-cloudways-free.html) — 3-day no-card trial and $10–20 in credits
2. [How to Get Started with Cloudways](guides/getting-started-with-cloudways.html) — sign-up, coupon, first VPS, WordPress access
3. [Launch a VPS Server in 5 Minutes: The Deep Dive](guides/launch-vps-in-5-minutes.html) — Lightning Stack, master credentials, monitoring, backups
4. [How to Use Cloudways: Deploy, Access, and Migrate WordPress](guides/how-to-use-cloudways.html) — DigitalOcean deploy + free All-in-One WP Migration
5. [Cloudways vs Shared Hosting (and Raw VPS)](guides/cloudways-vs-shared-hosting.html) — why the switch pays off
6. [Cloudways vs Hostinger](guides/cloudways-vs-hostinger.html) — dashboard tour, Flexible/Autonomous/Velocity, cost comparison

## How the site works

Pure static HTML + one CSS file — no build step, no JavaScript frameworks, no external dependencies. Hosted with **GitHub Pages**.

- `index.html` — course home with all lesson cards
- `guides/*.html` — one page per video: embedded player + written guide
- `css/style.css` — the whole stylesheet
- `sitemap.xml`, `robots.txt` — SEO basics
- `404.html` — GitHub Pages friendly not-found page

## Editing a lesson

Open the corresponding `guides/<slug>.html` and edit the HTML directly — each page is self-contained. Re-run the generator script (in the private workspace, not the repo) if lessons are added or reordered.

## Credits & disclaimer

All videos are © [MR AIT](https://www.youtube.com/@mrait); this site is a written study companion that embeds them via YouTube's official player. Pricing and promo details reflect the videos and change often — verify current offers on Cloudways' own site. Educational content only.
