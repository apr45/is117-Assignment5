# AI Portfolio Build Checklist

Use this checklist to verify that the generated code aligns with the `master_spec.md` requirements for the NJIT Technical Portfolio.

## 🏗️ 1. Architecture & Tech Stack
- [ ] **Framework:** Vite with Vanilla JS template used.
- [ ] **Hosting:** Configured for GitHub Pages (Static build).
- [ ] **CI/CD:** `.github/workflows/deploy.yml` included for automated builds.
- [ ] **Speed:** No heavy libraries; optimized for <2s load time.

## 🎨 2. Design Rules (Terminal Minimalist)
- [ ] **Colors:** Background `#121212`, Accent `#00FFAB`, Secondary Text `#94A3B8`.
- [ ] **Typography:** `JetBrains Mono` or `Fira Code` for headers; `Inter` for body.
- [ ] **Layout:** 12-column grid; mobile-first single-column stack.
- [ ] **Sidebar:** Fixed left-hand navigation with a vertical scroll-progress indicator.
- [ ] **Components:** "Terminal Hero" typing effect and "Receipt Cards" with hover lift.

## 📝 3. Content Model & "Receipts"
- [ ] **Identity:** Header displays NJIT major and expected graduation year.
- [ ] **STAR Method:** Project descriptions structured as Situation/Task, Action, and Result.
- [ ] **Verification:** Every project contains `[View Source]` and `[Live Demo]` links.
- [ ] **Evidence:** Results section includes a quantifiable technical metric (e.g., latency, %, or score).

## ✅ 4. Acceptance Criteria
- [ ] **Performance:** Google Lighthouse Performance score $\ge 95$.
- [ ] **Accessibility:** Contrast ratio $\ge 4.5:1$ and full keyboard (TAB) support.
- [ ] **Responsiveness:** Layout is verified for mobile devices and 1080p desktop.
- [ ] **Assets:** Functional link to a downloadable `resume.pdf`.

## 🚫 5. Non-Goals (Strict)
- [ ] **No Backend:** Verified no Node.js/Express server-side runtime.
- [ ] **No CMS:** Content is local JSON/Markdown only; no external database.
- [ ] **No Bloat:** No tracking scripts, analytics, or complex JS animations.