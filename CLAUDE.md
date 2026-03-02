# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Walnut & Wilson Homes LLC — a static marketing website for a home repair and renovation business in Dayton/Cincinnati, Ohio. Hosted on GitHub Pages at walnutandwilsonhomes.com.

## Architecture

This is a **single-file static site** with no build system, no package.json, and no framework.

- `index.html` — The entire site (~1,730 lines): HTML structure, inline CSS (`<style>` block, lines 15–251), and inline JavaScript (`<script>` block, lines 1520–1728)
- `CNAME` — GitHub Pages custom domain config
- `images/` — Logo and sample project photo
- `website photos/` — 68+ project photos (JPG)

## Tech Stack

- **HTML5** with Tailwind CSS 3+ via CDN (`cdn.tailwindcss.com`)
- **Vanilla JavaScript** (no dependencies, no bundler)
- **Font Awesome 6.4.0** (CDN) for icons
- **Google Fonts**: Inter (body), Montserrat (headings)
- **FormSubmit.co** for quote request form submissions (sends to walnutandwilsonhomes@gmail.com)
- Project gallery images hosted on Google Cloud Storage (`storage.googleapis.com/uxpilot-auth.appspot.com/`)

## Deployment

Push to the GitHub repo triggers automatic GitHub Pages deployment. No build step required.

## Site Sections (in order within index.html)

Header (fixed nav) → Hero → Why Us (benefits) → Gallery (grid + carousel) → Services (9 cards) → Process (5 steps) → Licensed Trades → Testimonials (carousel) → Contact/Quote Form → Footer

## Color Palette (Tailwind custom config)

| Name | Hex | Usage |
|------|-----|-------|
| navy-charcoal | #0F172A | Primary dark backgrounds |
| slate-med | #334155 | Body text |
| off-white | #F8FAFC | Light backgrounds |
| warm-orange | #F97316 | Accent/CTA buttons |
| demo-gray | #4B5563 | Supplementary text |

## JavaScript Components

All JS is inline at the bottom of index.html:

- **Header scroll behavior** — Hides on scroll down, shows on scroll up (5px threshold)
- **Mobile hamburger menu** — Toggle with ARIA attributes, auto-closes on link click
- **Smooth scrolling** — Anchor links use `scrollIntoView({ behavior: 'smooth' })`
- **Carousel navigation** — Left/right buttons scroll by viewport width (projects + testimonials)
- **Image modal gallery** — Click to enlarge, arrow key/button navigation, ESC to close
- **Drag-and-drop file upload** — Visual feedback, file size formatting, file list preview

## Key Considerations

- All external dependencies load via CDN — no local installs needed
- The site is mobile-first responsive with breakpoints at md (768px) and lg (1024px)
- Form submissions go through FormSubmit.co (third-party, no backend)
- When editing, be aware everything is in one file — CSS changes are near the top, JS at the bottom, HTML structure in between
