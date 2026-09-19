# Web Engineering & Developer Portfolio — Handoff

**Date:** September 20, 2026  
**Developer / Owner:** Tareeq Faraji  
**Workspace:** `D:\VE port`  
**GitHub Repository:** [`nocturnemov/web-portfolio`](https://github.com/nocturnemov/web-portfolio)  
**Preserved Video Portfolio Repository:** [`nocturnemov/nocturnemov.github.io`](https://github.com/nocturnemov/nocturnemov.github.io)  
**Production Live URL:** [https://web-portfolio-amber.vercel.app](https://web-portfolio-amber.vercel.app)  

---

## 1. Project Overview & Evolution

The portfolio represents an end-to-end transformation from a video editing showcase into a **Modern Web Engineering & Full-Stack Developer Portfolio**.

### Perspective & Persona Refinement
- **Hobbyist Builder Perspective:** The narrative in the **About** section has been calibrated to reflect a self-driven hobbyist builder and creative tinkerer. Rather than framing work strictly around formal academic coursework or corporate routines, it highlights:
  - Intrinsic curiosity and late-night experimentation with code, design, and web interfaces.
  - Joy of turning creative concepts into smooth, interactive, real-world tools.
  - Uncompromising craftsmanship: type-safe architectures, sub-second performance, and accessible UI engineering.
- **Section Headers & Status:**
  - Section heading updated to **About Me**.
  - Metadata badge: `STATUS: Hobbyist Developer & Builder` (Location: `Dar es Salaam / Global`).
  - Stats highlight: `100% Passion Driven` alongside `2+ Live Production Apps`, `100% TypeScript & Next.js`, and `99+ Lighthouse Scores`.

### Design System Architecture
- **Visual Theme:** Technical blueprint aesthetic featuring an interactive radial dot-grid canvas, crosshair alignment markers, and measurement ruler dividers (`.ruler`).
- **Typography:** `IBM Plex Mono` (specs/eyebrows/code), `Crimson Text` (editorial headlines), and `Hanken Grotesk` (clean sans-serif body).
- **Styling Standards:** Zero-dependency semantic HTML5 & modern CSS custom properties, zero border-radius sharp geometry, and offset box-shadow hover states (`6px 6px 0 var(--ink)`).
- **Safety & Backups:** Original video editing portfolio preserved locally at [`index.video-portfolio.backup.html`](file:///D:/VE%20port/index.video-portfolio.backup.html) and on GitHub under `nocturnemov/nocturnemov.github.io`.

---

## 2. Showcased Web Applications

The portfolio highlights two production-grade full-stack web platforms built with Next.js and TypeScript:

### 1. HR Space — Executive Recruitment & HR Consultancy Platform
* **Live Site:** [https://hrspace.vercel.app](https://hrspace.vercel.app)
* **Scope:** Enterprise client platform for a Dar es Salaam recruitment and management consultancy.
* **Architecture:** Next.js App Router, Turbopack, Space Grotesk/Inter fluid typography, responsive CSS Grid layout.
* **Key Features:**
  - Interactive candidate matching visualizer with SVG blueprint aperture animations.
  - Comprehensive service breakdowns (HR Compliance, Background Checks, Team Training, CSR Career Services).
  - Multi-channel client consultation booking workflows.
* **Case Study UI:** Embedded interactive browser mockup with tabbed navigation (**Overview**, **Architecture**, **Key Features**).

### 2. Faith Victory International Church — Community & Media Platform
* **Live Site:** [https://faithvictorytz.org](https://faithvictorytz.org)
* **Scope:** Full-stack community portal with high media throughput and live service streaming.
* **Architecture:** Next.js 15, React, TypeScript, Tailwind CSS, SSR/SSG pre-rendering, automated OpenGraph metadata.
* **Key Features:**
  - Dedicated `/watch-live` streaming hub with dynamic status indicators.
  - Dynamic sermon archive and spiritual media library.
  - Digital community engagement (prayer requests, event reservations, online giving).
  - Administrative staff dashboard (`/admin`).
* **Case Study UI:** Embedded interactive browser mockup with tabbed navigation (**Overview**, **Architecture**, **Key Features**).

---

## 3. Infrastructure & Deployment

| Resource | Target | Status |
| :--- | :--- | :--- |
| **GitHub Repository** | [`https://github.com/nocturnemov/web-portfolio`](https://github.com/nocturnemov/web-portfolio) | Active (`main` branch) |
| **Vercel Project** | `web-portfolio` (Account: `daniel101`) | Linked & Automated |
| **Production Deployment** | [https://web-portfolio-amber.vercel.app](https://web-portfolio-amber.vercel.app) | Live & Healthy (HTTP 200) |
| **Active Deployment ID** | `dpl_EPhMn4nnyCvv9RLYH77Tc2FGSkKD` | Succeeded |
| **Vercel Inspector** | [Deployment Inspector](https://vercel.com/daniel101/web-portfolio) | Verified |

---

## 4. Git Remote Structure

* `origin` → [`https://github.com/nocturnemov/web-portfolio.git`](https://github.com/nocturnemov/web-portfolio.git) (Active development remote)
* `github-io` → [`https://github.com/nocturnemov/nocturnemov.github.io.git`](https://github.com/nocturnemov/nocturnemov.github.io.git) (Preserved video portfolio remote)

---

## 5. Recent Commit Milestones

* `21bcd5b` — `feat: update about description to reflect a hobbyist perspective`
* `995f6cc` — `chore: update portfolio name to Tareeq Faraji`
* `39238f8` — `feat: transform into academic web engineering portfolio showcasing Faith Victory and HR Space`
* `357b68f` — `Set browser tab title to Nocturne`
* `77ded4b` — `Nocturne portfolio site`

---

## 6. Maintenance & Deployment Commands

To deploy future updates:

```powershell
# 1. Check status and stage changes
git status
git add .

# 2. Commit changes
git commit -m "feat: your feature or update description"

# 3. Push to GitHub
git push origin main

# 4. Deploy to Vercel production
vercel --prod
```
