## Project Overview
This portfolio is a high-performance, single-page technical showcase designed specifically for an NJIT student to secure professional internships. It utilizes a "Terminal Minimalist" aesthetic to signal technical competency and logic to engineering recruiters and faculty.

---

## The Tech Stack
* **Build Engine:** Node.js with Vite (Vanilla JS template) for rapid development and optimized bundling.
* **Deployment:** GitHub Actions automated pipeline.
* **Hosting:** GitHub Pages (Static site delivery).
* **Version Control:** Git/GitHub with a `main` branch trigger for CI/CD.

---

Pages & Sections Structure

| Section | Purpose | Key Components |
| :--- | :--- | :--- |
| **Hero** | Identity & Intent | Terminal prompt `whoami`, Role Status Badge, NJIT Graduation Date. |
| **Toolstack** | Skills | Categorized pill-grid (Languages, Frameworks, DevOps). |
| **Projects** | Proof of Work | Receipt-first project cards with STAR-method descriptions. |
| **Experience** | Professional History | Minimalist vertical timeline. |
| **Contact** | Conversion | Plain-text email link, LinkedIn, GitHub, Resume PDF. |

---

## Design Rules
### Typography
* **Headers/Accents:** `JetBrains Mono` or `Fira Code` (Monospace) to reinforce the technical "IDE" aesthetic.
* **Body Text:** `Inter` (Sans-Serif) for high readability and WCAG accessibility compliance.

### Color Palette
* **Primary Background:** `#121212` (Deep Charcoal).
* **Highlight/Action:** `#00FFAB` (Neon Mint).
* **Secondary Text:** `#94A3B8` (Slate Grey).

### Spacing/Grid
* **Structure:** 12-column CSS Grid system for desktop.
* **Mobile-First:** Single-column vertical stack for mobile devices with a bottom-docked navigation bar.
* **Navigation:** Fixed left-hand sidebar on desktop featuring a vertical scroll-progress indicator.

### Components:
* **Badges:** Monospace text with `#00FFAB` border.
* **Sidebar:** Left-aligned, fixed width on desktop, bottom-docked on mobile.

---

## Content Model
Every project entry must include the following fields to satisfy the "Receipt-First" requirement:
* **Title:** Name of the project or NJIT coursework.
* **TL;DR:** A one-sentence summary of the core technology and objective.
* **The Challenge (S/T):** Problem statement with a link to the original prompt or repository.
* **The Action (A):** Technical implementation details with a link to specific code modules or schematics.
* **The Result (R):** Outcome quantified by a specific metric (e.g., "<500ms latency").
* **Links:** Mandatory buttons for `[View Source]` and `[Live Demo/Documentation]`.

---

## Acceptance Criteria (Testable)

### Per Page (Home)

* [ ] Hero section displays NJIT affiliation and "Available for Internship" status.
* [ ] All project cards contain at least two clickable "Receipt" links.
* [ ] Navigation sidebar correctly highlights the active section during scroll.

### Per Deployment Step

* [ ] **Build:** Vite successfully compiles assets into `/dist` in under 30 seconds.
* [ ] **Performance:** Google Lighthouse score for "Performance" is $\ge 95$ on mobile.
* [ ] **Accessibility:** No WCAG 2.1 AA errors found in automated audits.

---

## Non-Goals
* **No CMS:** Content is hard-coded in JSON or Markdown; no external database connection.
* **No Backend Runtime:** No live Node.js/Express server; strictly static files.
* **No Contact Backend:** No PHP or server-side mailers; use simple `mailto:` or 3rd-party form redirects.
* **No Complex Motion:** No heavy JavaScript parallax or physics-based animations that degrade performance.