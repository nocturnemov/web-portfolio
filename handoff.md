# Personal Web Projects & Hobbyist Developer Portfolio — Handoff

**Date:** September 20, 2026  
**Developer / Owner:** Tareeq Faraji  
**Workspace:** `D:\VE port`  
**GitHub Repository:** [`nocturnemov/web-portfolio`](https://github.com/nocturnemov/web-portfolio)  
**Preserved Video Portfolio Repository:** [`nocturnemov/nocturnemov.github.io`](https://github.com/nocturnemov/nocturnemov.github.io)  
**Production Live URL:** [https://web-portfolio-amber.vercel.app](https://web-portfolio-amber.vercel.app)  

---

## 1. Project Overview & Persona Calibration

The website represents a personal portfolio centered on a **self-driven hobbyist builder, creative tinkerer, and web enthusiast**. The copy across the entire site has been calibrated away from corporate, enterprise, and academic jargon to a genuine, conversational, hobby-focused tone:

### Site-Wide Hobbyist Positioning
- **Header & Hero:** 
  - Tag updated to `HOBBYIST BUILDER` (replaced `STUDENT PORTFOLIO`).
  - Nav label changed to `Toolkit` (replaced corporate `Competencies`).
  - Status beacon: `Building for fun · Tinkering with web projects` (replaced `Open for Internships & Projects`).
  - Role: `Hobbyist Web Developer · Code Tinkerer & UI Enthusiast`.
  - Tagline: Focuses on building digital tools for the joy of creating, late-night experiments, and turning ideas into live realities.
- **About Me Section:**
  - Status badge: `STATUS: Hobbyist Coder & Tinkerer`.
  - Narrative: Positions coding as an addictive creative playground rather than a corporate ladder or academic requirement. Celebrates the thrill of breaking CSS layouts, late-night curiosity, and building things from scratch.
  - Stats: `2+ Live Projects Shipped`, `100% Self-Taught & Curious`, `99+ Lighthouse Speeds`, `100% Built for the Fun of It`.
  - Spec bar: Relabeled to `My · Toolkit`, focusing on `Snappy Speeds · Clean UX · Accessible UI`.
- **Projects Section:**
  - Section title: `Things I've Built`.
  - HR Space: Reframed from an enterprise consultancy case study to an engaging, real-world build featuring an interactive candidate matching visualizer.
  - Faith Victory: Reframed from an institutional portal to a community streaming and sermon platform built to bring people together.
  - Tab labels: Replaced corporate `Architecture` with `How It's Built` and `Key Highlights`.
- **Toolkit & Skills (03):**
  - Section title: `What I Like Building With`.
  - Reframed categories from corporate competencies into `Snappy Interfaces`, `Backend & Logic`, `Speed & Smoothness`, and `Good Habits & UX`.
- **Why I Love Building (04):**
  - Section title: `Why I Love Building` (replaced `Academic Philosophy`).
  - Cards: `Learning by Breaking & Building` and `Crafting for the Joy of It`.
- **Contact & Footer (05):**
  - CTA: `Got a cool idea? Let's chat.`
  - Friendly invitation to connect, swap ideas, or collaborate on fun projects.
  - Footer: `Tareeq Faraji · Handcrafted for fun with Next.js & TypeScript © 2026 · Built out of curiosity · EOF`.

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
