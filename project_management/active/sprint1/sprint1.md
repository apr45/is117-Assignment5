## Sprint 1: The "Hello World" Pipeline (Infrastructure)

**Goal:** Establish the CI/CD pipeline so every save is live.

* **In-Scope:** Vite initialization, GitHub Repository setup, GitHub Actions deployment.
* **Out-of-Scope:** Custom CSS, content writing, or assets.
* **Tasks:**
    1. Run `npm create vite@latest . -- --template vanilla`
    2. Initialize Git and push to a new GitHub repo.
    3. Configure `.github/workflows/deploy.yml` for GitHub Pages.
    4. Enable GitHub Pages in settings (source: GitHub Actions).
* **Files:** `package.json`, `index.html`, `.github/workflows/deploy.yml`
* **Acceptance Criteria:** The default Vite "Vite + JS" page is visible at your `*.github.io` URL.
* **Avoid:** Spending time picking colors or fonts yet.
* **Evidence:** A live URL showing the Vite starter page.