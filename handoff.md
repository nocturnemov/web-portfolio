# Academic Web Engineering Portfolio — Handoff

**Date:** September 19, 2026  
**Workspace:** `D:\VE port`  
**New GitHub Repository:** [`nocturnemov/web-portfolio`](https://github.com/nocturnemov/web-portfolio)  
**Previous Video Portfolio Repository:** [`nocturnemov/nocturnemov.github.io`](https://github.com/nocturnemov/nocturnemov.github.io)  
**Production Live URL:** [https://web-portfolio-amber.vercel.app](https://web-portfolio-amber.vercel.app)  

---

## 1. Project Overview & Transformation

The video editing portfolio was transformed into an **Academic Web Development & Software Engineering Portfolio** tailored for school presentations, technical evaluations, and internship applications.

### Design System Preserved & Adapted:
- **Visual Aesthetic:** Technical blueprint theme with interactive dot-grid canvas, crosshair markers, and measurement ruler section dividers (`.ruler`).
- **Typography:** `IBM Plex Mono` (code/eyebrows/specs), `Crimson Text` (editorial headlines), and `Hanken Grotesk` (high-readability sans body).
- **Styling Architecture:** Zero-dependency semantic HTML5 & modern CSS custom properties, zero border-radius sharp geometry, and offset box-shadow hover states (`6px 6px 0 var(--ink)`).
- **Safety:** Original video portfolio backed up locally at [`index.video-portfolio.backup.html`](file:///D:/VE%20port/index.video-portfolio.backup.html) and permanently preserved on GitHub under `nocturnemov/nocturnemov.github.io`.

---

## 2. Showcased Web Applications

The portfolio features two real-world full-stack web platforms built with Next.js and TypeScript:

### 1. HR Space — Executive Recruitment & HR Consultancy Platform
* **Live Site:** [https://hrspace.vercel.app](https://hrspace.vercel.app)
* **Scope:** Enterprise client platform for a Dar es Salaam consultancy.
* **Architecture:** Next.js App Router, Turbopack, Space Grotesk/Inter fluid typography, CSS Grid responsive layout.
* **Key Features:**
  - Interactive candidate matching visualizer with SVG blueprint aperture animations.
  - Comprehensive service breakdowns (HR Compliance, Background Checks, Team Training, CSR Career Services).
  - Multi-channel client consultation booking workflows.
* **Portfolio Presentation:** Includes interactive browser chrome mockup with tabs for **Overview**, **Architecture**, and **Key Features**.

### 2. Faith Victory International Church — Community & Media Platform
* **Live Site:** [https://faithvictorytz.org](https://faithvictorytz.org)
* **Scope:** Full-stack community portal with high media throughput.
* **Architecture:** Next.js 15, React, TypeScript, Tailwind CSS, SSR/SSG pre-rendering, automated OpenGraph metadata.
* **Key Features:**
  - Dedicated `/watch-live` streaming integration with status indicators.
  - Dynamic sermon archive and spiritual media library.
  - Digital community engagement (prayer requests, event reservations, online giving).
  - Internal administrative staff portal (`/admin`).
* **Portfolio Presentation:** Includes interactive browser chrome mockup with tabs for **Overview**, **Architecture**, and **Key Features**.

---

## 3. Deployment & Repository Infrastructure

| Resource | Target | Status |
| :--- | :--- | :--- |
| **New GitHub Repository** | [`https://github.com/nocturnemov/web-portfolio`](https://github.com/nocturnemov/web-portfolio) | Created & Pushed (`main` branch) |
| **Vercel Project** | `web-portfolio` (Account: `daniel101`) | Created & Linked |
| **Production Deployment** | [https://web-portfolio-amber.vercel.app](https://web-portfolio-amber.vercel.app) | Live & Verified (HTTP 200) |
| **Inspector Dashboard** | [Vercel Deployment Inspector](https://vercel.com/daniel101/web-portfolio) | Ready |

---

## 4. Git Remote Structure

* `origin` → [`https://github.com/nocturnemov/web-portfolio.git`](https://github.com/nocturnemov/web-portfolio.git) (Primary development remote)
* `github-io` → [`https://github.com/nocturnemov/nocturnemov.github.io.git`](https://github.com/nocturnemov/nocturnemov.github.io.git) (Preserved previous video editing portfolio)

---

## 5. Ongoing Maintenance

To push future updates:
```powershell
# Commit changes
git add .
git commit -m "feat: your update message"
git push origin main

# Deploy to Vercel production
vercel --prod
```
