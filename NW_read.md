# NIIRMAAN — B2C Marketplace for Local Home Services

> **Note:** The source code for this project is maintained in a private repository. This document is a public showcase intended for evaluators and collaborators.

**Live Site:** [niirmaan-webfront.netlify.app](https://niirmaan-webfront.netlify.app)

---

## What Is NIIRMAAN?

NIIRMAAN is a service marketplace platform designed for the Bangladesh market (Dhaka-focused). It connects homeowners and businesses with verified, local technicians and service vendors — making it easy to find, compare, and book professionals for everyday needs.

**Services covered:** Plumbing, electrical work, AC installation & repair, carpentry, painting, deep cleaning, appliance repair, and more.

The platform is built around two core user journeys: customers who need reliable professionals fast, and skilled technicians/vendors who want a trusted channel to reach clients.

---

## Key Features

**For Customers**
- Searchable, filterable service catalog (12+ service categories)
- Professional profiles with ratings, pricing ranges, and availability
- Guided 4-step booking flow (search → compare → book → confirm)
- Contact and inquiry form with real-time email delivery via Resend

**For Professionals**
- Dedicated onboarding flows for technicians and vendors
- Separate join-as-technician and join-as-vendor application pages

**Platform Pages**
- Blog, Pricing, FAQ, Careers, Partners, Help, Terms & Privacy
- A live Design System page exposing the full component/token library

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 14.2 (App Router) |
| Language | TypeScript 5.3 |
| UI Library | React 18 |
| Styling | Tailwind CSS 3.4 |
| Animation | Framer Motion 11 |
| Email | Resend (transactional API) |
| Analytics | Google Analytics 4 |
| Deployment | Netlify + @netlify/plugin-nextjs |

---

## Design Philosophy

The UI follows an Apple-inspired, minimal-premium aesthetic:

- **Glass morphism** navigation with backdrop blur and translucency
- **Fluid typography** using CSS `clamp()` — scales seamlessly from 320 px to 1536 px without breakpoint jumps
- **Motion design** via Framer Motion: scroll-triggered reveals, counter animations, parallax hero, floating elements
- **Color system** anchored to Apple's signature blue (#0071E3) with a clean neutral gray ramp
- **Mobile-first** layout with safe-area insets and touch-target minimums; 95%+ device coverage tested

---

## Performance & SEO

**Performance**
- AVIF and WebP image formats via Next.js Image Optimization
- SWC minification and tree-shaking
- 1-year immutable cache headers on all static assets (`_next/static/*`, images, CSS/JS)
- Bundle Analyzer integrated for ongoing size monitoring
- Expected load time under 3 seconds on a mid-range mobile connection

**SEO**
- JSON-LD structured data: `LocalBusiness`, `Organization`, `WebSite` schemas
- Dynamic `sitemap.ts` and `robots.ts` auto-generated at build time
- Full Open Graph and Twitter Card meta tags on every page
- Semantic HTML hierarchy throughout

**Security Headers (Netlify)**
- `Strict-Transport-Security` (HSTS, 2-year max-age)
- `X-Frame-Options: SAMEORIGIN`
- `X-Content-Type-Options: nosniff`
- `X-XSS-Protection`
- `Referrer-Policy: origin-when-cross-origin`

---

## Project Status

**Pre-launch — approximately 82% production-ready** (as of May 2026)

| Area | Status |
|---|---|
| UI/UX & Design | Production-ready |
| Mobile Responsiveness | Production-ready |
| Navigation & Routing | Production-ready |
| Contact Form (Resend) | Integrated, pending final env config |
| SEO Foundation | Complete |
| Google Analytics | Pending GA Measurement ID wiring |
| Legal Pages | Placeholder pages in place |

Core flows, design system, and all 20+ pages are live and functional. Remaining items are configuration and content tasks, not architectural gaps.

---

## What This Project Demonstrates

- **Full-stack Next.js** — App Router, server components, API routes, dynamic metadata
- **Design system thinking** — consistent tokens, fluid scales, documented component library
- **Animation engineering** — production-quality motion without performance regressions
- **SEO & performance best practices** — structured data, caching, format optimization
- **Third-party integrations** — transactional email (Resend), analytics (GA4)
- **Deployment infrastructure** — Netlify with custom headers, caching rules, and plugin config
- **TypeScript discipline** — strict types across components, API handlers, and data models
- **Scalable architecture** — clean separation of pages, components, utilities, and API routes

---

*Built by Siam Sadman Azad*
