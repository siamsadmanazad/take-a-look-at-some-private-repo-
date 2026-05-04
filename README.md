# Take a Look at Some Private Repo

Welcome! This is a **public showcase** of a curated selection of projects from my private repository.

## About This Repo

The live demos and projects you see here represent just a few highlights from a much larger body of work that lives in a private repository. They've been made public so you can explore them freely.

> **Note:** The remaining projects in the private repository are confidential and not publicly available.

## What's Here

These projects span various domains and technologies — feel free to browse, explore the code, and reach out if anything catches your eye.

---

### DK Atelier — Slow Fashion E-Commerce

**Live Demo:** [storefront-three-wheat.vercel.app](https://storefront-three-wheat.vercel.app)

A full-featured e-commerce storefront for a slow-fashion knitwear brand based in Dhaka, Bangladesh. Built with **Next.js** and **React**, the site goes beyond a typical shop — it tells the story of each garment: the artisan who made it, the organic materials (GOTS certified), and the solar-powered, LEED Gold certified facility behind it.

**Highlights:**
- Product catalogue with filtering, wishlist, and dynamic collections (SS26)
- Artisan profiles and brand journal — editorial-style storytelling woven into the shopping experience
- Sustainability-first brand identity with full supply-chain transparency built into the UI
- Deployed on Vercel with optimised image delivery via Next.js image pipeline

A love project — built with care, much like the garments it sells.

---

### NIIRMAAN — B2C Marketplace for Local Home Services

**Live Demo:** [niirmaan-webfront.netlify.app](https://niirmaan-webfront.netlify.app)

A service marketplace platform built for the Bangladesh market (Dhaka-focused), connecting homeowners and businesses with verified local technicians and service vendors. Covers 12+ service categories — plumbing, electrical, AC repair, carpentry, deep cleaning, appliance repair, and more.

Built around two core user journeys: customers who need reliable professionals fast, and skilled technicians/vendors who want a trusted channel to reach clients.

**Highlights:**
- Searchable, filterable service catalog with professional profiles, ratings, and pricing ranges
- Guided 4-step booking flow (search → compare → book → confirm)
- Dedicated onboarding flows for technicians and vendors
- Transactional email via Resend, Google Analytics 4, and a live Design System page
- Apple-inspired minimal-premium UI — glass morphism nav, fluid typography via CSS `clamp()`, Framer Motion scroll-triggered animations and parallax hero
- Next.js Image Optimization (AVIF/WebP), SWC minification, 1-year immutable cache headers, Bundle Analyzer
- JSON-LD structured data, dynamic sitemap/robots, full Open Graph and Twitter Card meta — complete SEO foundation
- Security headers configured at the Netlify layer (HSTS, X-Frame-Options, CSP, nosniff)

**Stack:** Next.js 14.2 (App Router) · TypeScript 5.3 · React 18 · Tailwind CSS 3.4 · Framer Motion 11 · Resend · Netlify

Pre-launch, ~82% production-ready — all 20+ pages and core flows are live and functional. Remaining items are configuration and content tasks, not architectural gaps.

---

### NIIRMAAN — Web Admin Panel

**Live Demo:** [niirmaan-admin-panal.vercel.app](https://niirmaan-admin-panal.vercel.app)

The operations control center for the entire Niirmaan marketplace. Operators use it to verify users, moderate content, resolve disputes, monitor system health, and extract business intelligence — all from a single interface. The demo runs against a live staging dataset of 1,000+ seeded users.

| Role | Email | Password |
|------|-------|----------|
| Demo Viewer (read-only) | viewer@niirmaan.com | Niirmaan@2026 |

**Highlights:**
- Real-time KPI dashboard with live-updating charts (active users, pending bookings, daily revenue, open disputes)
- Unified user management for all three roles — Customers, Professionals, and Vendors — with search, filter, status management, and KYC review
- Vendor verification queue — structured approve/reject workflow with document review and internal notes
- Review moderation queue with approve/remove/escalate actions and full audit trail
- Booking lifecycle management with calendar interface and Kanban-based dispute resolution
- Nine purpose-built analytics dashboards: Overview, User Analytics, Revenue, Geographic (demand heatmaps), Customer Intelligence, Financial Intelligence, Cohort Analysis, Real-time, and Executive
- System monitoring: service health checks, metrics (latency, error rates, throughput), alert management, and a structured log viewer
- RBAC administration, feature flags, team management, audit logs, and a custom report builder

**Stack:** React 18 + TypeScript · Material UI v5 · React Query + Zustand · Vite · Supabase Edge Functions + Realtime · Supabase Auth (JWT / RBAC)

**GitHub (private):** `github.com/siamsadmanazad/Niirmaan_admin_panal`

---

### NIIRMAAN — Vendor Portal

**Live Demo:** [niirmaan-vendor-portal.vercel.app](https://niirmaan-vendor-portal.vercel.app)

A self-service portal for material suppliers on the Niirmaan marketplace. Vendors manage their product catalog, process incoming orders, track earnings, configure their storefront, and analyse sales performance — all without platform-operator involvement.

| Role | Email | Password |
|------|-------|----------|
| Active Vendor | v001@niirmaan.com | Niirmaan@2026 |

**Highlights:**
- Animated KPI dashboard with guided onboarding checklist for new vendors
- Seven-page inventory management suite: Product Dashboard, Product List, Stock Management, Price Management, Stock Alerts, Bulk CSV Upload, and Multi-Location Inventory
- Inbound order workflow — inbox view, individual order drill-down, and delivery tracking
- Full shop profile management: operating hours, delivery zones, payment methods, and location settings
- Earnings & finance: period-over-period revenue, payout schedule, commission breakdown, and a full transaction ledger
- Six analytics views: Executive Summary, Sales Analytics, Product Performance, Customer Analytics, Advanced Analytics, and a Custom Report Builder
- Review dashboard with aggregate rating trends and moderation flagging
- Vendor-to-customer messaging inbox, subscription tier management, and team sub-accounts

**Stack:** React 18 + TypeScript · Material UI v5 · Zustand + React Query · Vite · Supabase Edge Functions + Realtime · Supabase Auth · Vitest (31 test files, 300+ cases)

**GitHub (private):** `github.com/siamsadmanazad/Niirmaan_vendor_portal`

---

## Private Repo

The full portfolio includes many more projects across different stacks and problem spaces. If you're a collaborator, recruiter, or someone I've invited directly, you may have access to the private repository.

---

*The live demos shown here are some of many projects present in my private repo. The rest are confidential.*
