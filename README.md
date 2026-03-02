<div align="center">

<img src="docs/images/banner.jpg" alt="Walnut & Wilson Homes LLC Banner" width="100%">

# Walnut & Wilson Homes LLC

### Licensed Home Repairs & Renovations in Dayton & Cincinnati, OH

[![Website](https://img.shields.io/badge/Website-walnutandwilsonhomes.com-F97316?style=for-the-badge&logo=google-chrome&logoColor=white)](https://walnutandwilsonhomes.com)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://github.com/flourishments/walnut-and-wilson-homes)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#tech-stack)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](#tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#tech-stack)

[![License](https://img.shields.io/badge/License-Proprietary-0F172A?style=flat-square)](#license)
[![Status](https://img.shields.io/badge/Status-Production-22C55E?style=flat-square)](#)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile_First-F97316?style=flat-square)](#responsive-design)
[![Accessibility](https://img.shields.io/badge/Accessibility-WCAG_2.1-334155?style=flat-square)](#accessibility)
[![SEO](https://img.shields.io/badge/SEO-Optimized-F97316?style=flat-square)](#seo)
[![Schema](https://img.shields.io/badge/Schema-JSON--LD-0F172A?style=flat-square)](#structured-data)

---

**From small fixes to full remodels — skilled work from a tight, experienced team.**

[View Live Site](https://walnutandwilsonhomes.com) &bull; [Request a Quote](https://walnutandwilsonhomes.com#contact) &bull; [Call (937) 562-1235](tel:9375621235)

</div>

---

## About

Walnut & Wilson Homes LLC is a licensed and insured home repair and renovation company serving the **Dayton** and **Cincinnati** metro areas in Ohio. With a lead manager bringing **20+ years** of residential and commercial experience, we handle everything from quick repairs to full-scale remodels — managed start-to-finish with a single point of contact.

This repository contains the production website deployed at [walnutandwilsonhomes.com](https://walnutandwilsonhomes.com).

---

## Services

<div align="center">
<img src="docs/images/services-overview.jpg" alt="Services Overview Infographic" width="80%">
</div>

| Category | What We Do |
|----------|-----------|
| **Repairs & Maintenance** | Appliances, water heaters, punch lists, general repairs |
| **Demolition & Junk Removal** | Interior demo, furniture removal, cleanouts |
| **Plumbing** *(Licensed)* | Leak detection, drain cleaning, gas plumbing, water/sewer lines |
| **Electrical** *(Licensed)* | Diagnostics, wiring, panel upgrades, troubleshooting |
| **Carpentry & Finish Work** | Cabinetry, trim, moulding, framing |
| **Masonry / Brick / Stucco** | Chimney repair, brick walls, tuckpointing |
| **Concrete & Exterior** | Driveways, patios, decks, landscaping |
| **Painting & Drywall** | Interior/exterior painting, drywall repair, flooring |
| **Remodeling + Project Mgmt** | Bathrooms, kitchens, basements, whole-house renovations |

### Licensed Trades

```
┌─────────────────┐   ┌─────────────────┐   ┌─────────────────┐
│    PLUMBING      │   │   ELECTRICAL    │   │      GAS        │
│                  │   │                 │   │                 │
│  Water & sewer   │   │  Wiring, panel  │   │  Licensed gas   │
│  lines, gas      │   │  upgrades,      │   │  work for all   │
│  plumbing        │   │  diagnostics    │   │  residential    │
└─────────────────┘   └─────────────────┘   └─────────────────┘
```

---

## Customer Journey

<div align="center">
<img src="docs/images/customer-journey.jpg" alt="Customer Journey Process Flow" width="80%">
</div>

```mermaid
flowchart LR
    A["📞 Contact Us"] --> B["📋 Free Consultation"]
    B --> C["💰 Detailed Quote"]
    C --> D["🔨 Expert Execution"]
    D --> E["✅ Final Walkthrough"]

    style A fill:#0F172A,color:#fff,stroke:#F97316
    style B fill:#0F172A,color:#fff,stroke:#F97316
    style C fill:#0F172A,color:#fff,stroke:#F97316
    style D fill:#0F172A,color:#fff,stroke:#F97316
    style E fill:#0F172A,color:#fff,stroke:#F97316
```

### Detailed Process Flow

```mermaid
flowchart TD
    START(["🏠 Homeowner Needs Help"]) --> CONTACT{"How to Reach Us?"}

    CONTACT -->|"Call/Text"| PHONE["📱 (937) 562-1235"]
    CONTACT -->|"Email"| EMAIL["✉️ walnutandwilsonhomes@gmail.com"]
    CONTACT -->|"Website Form"| FORM["📝 Online Quote Request"]

    PHONE --> CONSULT["📋 Free On-Site Consultation"]
    EMAIL --> CONSULT
    FORM --> CONSULT

    CONSULT --> ASSESS["🔍 Diagnostic Assessment"]
    ASSESS --> QUOTE["💰 Written Quote with Timeline"]

    QUOTE --> DECISION{"Customer Approves?"}
    DECISION -->|"Yes"| PERMIT{"Permits Needed?"}
    DECISION -->|"Questions"| CONSULT

    PERMIT -->|"Yes"| PULL_PERMIT["📜 Pull Permits"]
    PERMIT -->|"No"| SCHEDULE["📅 Schedule Work"]
    PULL_PERMIT --> SCHEDULE

    SCHEDULE --> EXECUTE["🔨 Professional Execution"]
    EXECUTE --> INSPECT{"Inspection Required?"}

    INSPECT -->|"Yes"| PASS_INSPECT["✅ Pass Inspection"]
    INSPECT -->|"No"| WALKTHROUGH["🤝 Final Walkthrough"]
    PASS_INSPECT --> WALKTHROUGH

    WALKTHROUGH --> COMPLETE(["🎉 Project Complete!"])

    style START fill:#F97316,color:#fff,stroke:#0F172A
    style COMPLETE fill:#22C55E,color:#fff,stroke:#0F172A
    style CONSULT fill:#0F172A,color:#fff,stroke:#F97316
    style EXECUTE fill:#0F172A,color:#fff,stroke:#F97316
    style QUOTE fill:#334155,color:#fff,stroke:#F97316
    style DECISION fill:#F97316,color:#fff,stroke:#0F172A
    style PERMIT fill:#F97316,color:#fff,stroke:#0F172A
    style INSPECT fill:#F97316,color:#fff,stroke:#0F172A
```

---

## Tech Stack

<div align="center">
<img src="docs/images/tech-stack.jpg" alt="Technology Stack Architecture" width="80%">
</div>

```mermaid
graph TD
    subgraph Frontend ["🖥️ Frontend"]
        HTML["HTML5"]
        TW["Tailwind CSS 3+ (CDN)"]
        JS["Vanilla JavaScript"]
    end

    subgraph CDN ["☁️ CDN Services"]
        FA["Font Awesome 6.4.0"]
        GF["Google Fonts (Inter + Montserrat)"]
    end

    subgraph Integrations ["🔗 Integrations"]
        FS["FormSubmit.co (Quote Forms)"]
        GCS["Google Cloud Storage (Gallery Images)"]
    end

    subgraph Hosting ["🚀 Hosting & Deployment"]
        GH["GitHub Pages"]
        CNAME["Custom Domain: walnutandwilsonhomes.com"]
    end

    Frontend --> CDN
    Frontend --> Integrations
    Frontend --> Hosting

    style Frontend fill:#0F172A,color:#fff
    style CDN fill:#334155,color:#fff
    style Integrations fill:#F97316,color:#fff
    style Hosting fill:#22C55E,color:#fff
```

### Architecture Overview

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Markup** | HTML5 | Semantic structure with ARIA accessibility |
| **Styling** | Tailwind CSS 3+ (CDN) | Utility-first responsive design |
| **Typography** | Google Fonts | Inter (body) + Montserrat (headings) |
| **Icons** | Font Awesome 6.4.0 (CSS) | UI icons throughout the site |
| **Forms** | FormSubmit.co | Email-based quote request handling |
| **Images** | Google Cloud Storage | Gallery and project photo hosting |
| **Hosting** | GitHub Pages | Static site deployment with custom domain |
| **Domain** | walnutandwilsonhomes.com | CNAME-configured custom domain |

---

## Site Architecture

```mermaid
graph LR
    subgraph Navigation
        NAV["Fixed Header + Mobile Hamburger"]
    end

    subgraph Sections ["Page Sections (Single Page)"]
        direction TB
        HERO["🏠 Hero + Quick Contact"]
        WHY["⭐ Why Choose Us (6 Benefits)"]
        GALLERY["📸 Gallery + Before/After Slider"]
        SERVICES["🔧 Services (9 Categories)"]
        LICENSED["📜 Licensed Trades"]
        REMODEL["🏗️ Remodeling Showcase"]
        PROCESS["📋 5-Step Process"]
        TESTIMONIALS["💬 Client Testimonials"]
        FAQ["❓ FAQ (6 Questions)"]
        CONTACT["📞 Contact + Quote Form"]
    end

    subgraph Footer
        FOOT["Company Info + Links + Service Areas"]
    end

    subgraph Mobile
        CTA["📱 Sticky CTA Bar (Call + Quote)"]
    end

    NAV --> Sections
    Sections --> Footer
    Mobile -.->|"Visible on scroll"| Sections

    HERO --> WHY --> GALLERY --> SERVICES --> LICENSED --> REMODEL --> PROCESS --> TESTIMONIALS --> FAQ --> CONTACT

    style HERO fill:#0F172A,color:#fff
    style CONTACT fill:#F97316,color:#fff
    style CTA fill:#F97316,color:#fff
```

---

## Design System

### Color Palette

| Swatch | Name | Hex | Usage |
|--------|------|-----|-------|
| ![#0F172A](https://via.placeholder.com/20/0F172A/0F172A?text=+) | Navy Charcoal | `#0F172A` | Primary dark backgrounds, headings |
| ![#334155](https://via.placeholder.com/20/334155/334155?text=+) | Slate Medium | `#334155` | Body text, secondary sections |
| ![#F8FAFC](https://via.placeholder.com/20/F8FAFC/F8FAFC?text=+) | Off White | `#F8FAFC` | Light backgrounds |
| ![#F97316](https://via.placeholder.com/20/F97316/F97316?text=+) | Warm Orange | `#F97316` | Accent, CTAs, interactive elements |
| ![#4B5563](https://via.placeholder.com/20/4B5563/4B5563?text=+) | Demo Gray | `#4B5563` | Supplementary text |

### Typography

| Role | Font Family | Weights |
|------|-------------|---------|
| **Headings** | Montserrat | 600, 700, 800 |
| **Body** | Inter | 300–800 |

### Responsive Breakpoints

```
Mobile First (default)  →  Tablet (768px / md:)  →  Desktop (1024px / lg:)
```

---

## Features

### Interactive Components

```mermaid
mindmap
  root((Website Features))
    Navigation
      Fixed header with scroll hide/show
      Mobile hamburger menu with animation
      Smooth anchor scrolling
    Gallery
      4-card featured projects grid
      Before/After image comparison slider
      68+ photo horizontal carousel
      Full-screen modal with keyboard nav
    Forms
      Quote request with validation
      Drag-and-drop photo upload
      FormSubmit.co email delivery
    UX
      Sticky mobile CTA bar
      Collapsible FAQ accordion
      Testimonial carousel
      Hover effects & transitions
```

### Key Feature Details

| Feature | Description |
|---------|-----------|
| **Before/After Slider** | CSS + range input image comparison for 3 renovation projects |
| **Image Modal** | Full-screen gallery viewer with arrow key navigation and ESC close |
| **FAQ Accordion** | 6 collapsible questions, single-open behavior, FAQ schema markup |
| **Sticky Mobile CTA** | Fixed bottom bar with Call + Quote buttons, scroll-aware visibility |
| **Drag & Drop Upload** | Visual file upload with size formatting and file list preview |
| **Smart Header** | Hides on scroll down, reappears on scroll up (5px threshold) |

---

## SEO

### Optimization Summary

| Feature | Status |
|---------|--------|
| Descriptive `<title>` tag | ✅ |
| Meta description | ✅ |
| Canonical URL | ✅ |
| Open Graph tags | ✅ |
| Twitter Card tags | ✅ |
| Robots meta (index, follow) | ✅ |
| Semantic HTML5 structure | ✅ |
| Image alt text (descriptive) | ✅ |

### Structured Data

Two JSON-LD schemas are embedded:

```mermaid
graph LR
    subgraph Schema ["JSON-LD Structured Data"]
        LB["🏢 HomeAndConstructionBusiness"]
        FAQ["❓ FAQPage"]
    end

    LB -->|"name, phone, email"| CONTACT["Contact Info"]
    LB -->|"areaServed"| AREAS["Dayton + Cincinnati"]
    LB -->|"hasOfferCatalog"| SERVICES["6 Service Offerings"]

    FAQ -->|"mainEntity"| QA["6 Question/Answer Pairs"]

    style LB fill:#0F172A,color:#fff
    style FAQ fill:#334155,color:#fff
    style CONTACT fill:#F97316,color:#fff
    style AREAS fill:#F97316,color:#fff
    style SERVICES fill:#F97316,color:#fff
    style QA fill:#F97316,color:#fff
```

---

## Accessibility

| Feature | Implementation |
|---------|---------------|
| **Skip to content** | Keyboard-accessible skip link (first element in body) |
| **Landmark roles** | `<header>`, `<main>`, `<footer>`, `<nav>` |
| **ARIA attributes** | Modal (`role="dialog"`), carousel buttons (`aria-label`), menu (`aria-expanded`) |
| **Image alt text** | Descriptive alt text on all 72+ images |
| **Form labels** | All inputs have matching `<label>` with `for`/`id` |
| **Keyboard navigation** | Arrow keys in modal, ESC to close, tab navigation |
| **Color contrast** | Orange accent on dark backgrounds meets WCAG AA |

---

## Performance

| Optimization | Details |
|-------------|---------|
| **Lazy loading** | 72 images with `loading="lazy"` + `decoding="async"` |
| **Hero priority** | `fetchpriority="high"` on LCP hero image |
| **Font Awesome** | CSS-only (JS bundle removed) |
| **DNS prefetch** | Pre-resolved `storage.googleapis.com` |
| **Resource hints** | `preconnect` for Google Fonts |

---

## Project Structure

```
walnut-and-wilson-homes/
├── index.html                  # Complete single-page website (2,071 lines)
│   ├── <head>                  # Meta tags, SEO, Open Graph, JSON-LD schemas
│   ├── <style>                 # Custom CSS (Tailwind extensions)
│   ├── <body>                  # All page sections
│   └── <script>                # Interactive JS components
├── CNAME                       # GitHub Pages domain → walnutandwilsonhomes.com
├── CLAUDE.md                   # AI assistant development guide
├── README.md                   # This file
├── images/
│   ├── logo.png                # Company logo
│   └── trim-work.jpg           # Featured project photo
├── website photos/             # 68 project photos (JPG, ~31 MB total)
│   ├── IMG-20260116-WA0001.jpg
│   ├── IMG-20260116-WA0002.jpg
│   └── ... (66 more)
└── docs/
    └── images/                 # README infographics
        ├── banner.jpg          # Company banner
        ├── customer-journey.jpg # Process flow infographic
        ├── services-overview.jpg # Services grid infographic
        └── tech-stack.jpg      # Architecture diagram
```

---

## Deployment

```mermaid
flowchart LR
    DEV["💻 Local Development"] -->|"git push"| GH["🐙 GitHub Repository"]
    GH -->|"Auto-deploy"| GHP["🚀 GitHub Pages"]
    GHP -->|"CNAME"| DOMAIN["🌐 walnutandwilsonhomes.com"]

    style DEV fill:#334155,color:#fff
    style GH fill:#0F172A,color:#fff
    style GHP fill:#F97316,color:#fff
    style DOMAIN fill:#22C55E,color:#fff
```

No build step required. Push to `main` triggers automatic GitHub Pages deployment.

### Local Development

```bash
# Clone the repository
gh repo clone flourishments/walnut-and-wilson-homes

# Open in browser (macOS)
open index.html

# Or serve locally
npx serve .
```

---

## Form Integration

```mermaid
sequenceDiagram
    participant U as 👤 Customer
    participant W as 🌐 Website
    participant FS as 📧 FormSubmit.co
    participant E as 📬 Business Email

    U->>W: Fills quote form + uploads photos
    W->>FS: POST multipart/form-data
    FS->>FS: Format as HTML table email
    FS->>E: Deliver to walnutandwilsonhomes@gmail.com
    E-->>U: Response within 1 business day
```

**Form Fields:** Name, Phone, Email, City/Zip, Project Type (11 options), Description, Photo Upload (drag & drop), Preferred Timeline

---

## Service Area

```
                    ┌─────────────────────────────┐
                    │          OHIO                │
                    │                              │
                    │    ● Columbus                │
                    │                              │
                    │  ★ DAYTON ←── Full Service   │
                    │    (Main Area)               │
                    │         │                    │
                    │    ★ CINCINNATI ── Full Svc  │
                    │                              │
                    │  Surrounding areas on request │
                    └─────────────────────────────┘
```

---

## Contact

| Channel | Details |
|---------|---------|
| **Phone/Text** | [(937) 562-1235](tel:9375621235) |
| **Email** | [walnutandwilsonhomes@gmail.com](mailto:walnutandwilsonhomes@gmail.com) |
| **Website** | [walnutandwilsonhomes.com](https://walnutandwilsonhomes.com) |
| **Quote Form** | [Request a Quote](https://walnutandwilsonhomes.com#contact) |

---

## License

This project and all its contents are proprietary to **Walnut & Wilson Homes LLC**. All rights reserved.

---

<div align="center">

**Built with care by [Walnut & Wilson Homes LLC](https://walnutandwilsonhomes.com)**

*Licensed & Insured &bull; 20+ Years Experience &bull; Dayton & Cincinnati, OH*

[![Website](https://img.shields.io/badge/Visit-walnutandwilsonhomes.com-F97316?style=for-the-badge&logo=google-chrome&logoColor=white)](https://walnutandwilsonhomes.com)

</div>
