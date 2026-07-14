# Hi, I'm Danil — I take a task and get it done.

Frontend developer · Saint Petersburg or remote · open to roles from July 2026

> Most of my commercial work lives in private GitLab, so this GitHub is mostly personal projects and experiments.

Most recently, frontend at Dancecolor web studio — commercial projects: features, payment widgets, design changes, fixes, content, the odd refactor.

---

## What I work on

**Spliteks** — industrial portal on Bitrix, legacy codebase. A large frontend refactor: the monolithic `main.js` / `main.css` split into SCSS modules and TypeScript, build moved to Gulp for Bitrix. Wrote my own module orchestrator (global + per-page) — a selector-driven registry that only boots the JS a page actually uses, isolates each module's crashes, and handles its own teardown. The heavier features live here too: a scroll-driven morph section and a hand-built drag carousel with inertia and rubber-band physics, on functional GSAP values so they hold up under zoom and resize. CSS **1.2 MB → 143 KB**, PageSpeed **69 → 89** (desktop); swapped ScrollSmoother for Lenis to kill ScrollTrigger race conditions.

**Apple Inside** — e-commerce on Bitrix. Built a small design system for rich-content product pages (atomic classes, tokens, docs) — assembling a new page dropped from ~12h to ~3h. Rebuilt the stories module on Swiper: lazy init, memory cleanup, fluid `clamp()` layout, stable height on iOS via the visualViewport API.

**Reckful** — e-commerce on a modern stack, in a small team. Catalog search, reviews with pagination, REST API integration.

**Legacy CRM (PHP)** — a run of mobile-responsive fixes and small features on a codebase with no version control and FTP-only access. Brought the mobile UI in line with the mockups (burger menu, toolbars, tables, modals), plus smaller fixes and a "quick actions" block. To work on an ungit'd FTP-only codebase sanely, I set up my own FTP auto-sync — a watcher plus a post-commit hook. Done.

Alongside these, a steady stream of smaller fixes across other projects.

---

## Outside the studio

Built a **CRM frontend from scratch** on Vue 3 + Pinia + TanStack Table (Laravel REST API, Shadcn UI), and a few **Telegram bots with payment integration** (aiogram, FSM, content delivery after purchase) here and there.

---

## How I work

I care about how the whole thing behaves — performance, different devices, how a form actually feels to use. I'm fine picking up incomplete or shifting requirements: I find out what's actually needed and get it done. I tend to look at the whole project rather than just my slice — lately that's been pulling me toward audits and the product side.

I run my own server — Gitea, Nginx, Cloudflare tunnel — not as a DevOps, just to stop depending on other people's infrastructure. It's where my clients' sites and bots live, and the deploy target for this site's CI/CD.

I work in Figma properly, not only reading specs — components, variants, design tokens. When there's no designer, I pick up the file and finish the job. And I use AI as a daily tool while keeping control over what lands in the code.

I also write about frontend, UX and shipping — [lyoraeth.art/writing](https://lyoraeth.art/writing).

---

## Stack

**Daily:** JavaScript / TypeScript · Vue 3 · Nuxt · Pinia · TanStack Table · SCSS / BEM · Tailwind · GSAP · Gulp · Vite · Git

**Also:** React · Node · REST API · Postman · Python (aiogram) · Docker · GitHub Actions · Figma

---

## Projects

**[lyoraeth.art](https://github.com/lyoraeth/lyoraeth-art)** — this site — the most involved thing I've built solo. Nuxt 4 SSR with clean hydration, a design system driven entirely by CSS tokens, Sanity CMS through Nitro server routes, self-hosted cookie-free analytics, and full CI/CD — Docker build to live in ~3 minutes on push. The design is dark and editorial — a Swiss-style grid, monospace labels, print detailing (figure captions, FPO covers), with frosted-glass chrome over flat, outlined content. → **[lyoraeth.art](https://lyoraeth.art)**

- [**Simple-Header**](https://github.com/lyoraeth/Simple-Header) — the test task that got me the Dancecolor role. React / TS / Framer Motion: a morphing menu button as a state machine, noise-driven background, and the iOS Safari fixes the spec didn't ask for.

Older work — different stack, different era, kept for the record:

- [**personal-portfolio-archived**](https://github.com/lyoraeth/personal-portfolio-archived) — client-side SPA with custom slide-like routing, GSAP, device-specific builds and localization. My first serious project — a month of late nights, and the one that taught me the most.
- [**aiogram-yoomoney-bot**](https://github.com/lyoraeth/aiogram-yoomoney-bot) — Telegram bot for selling digital content with payment integration. The early, simple base of what I now build for clients.
- [**ecommerce-portfolio-project**](https://github.com/lyoraeth/ecommerce-portfolio-project) — "Risa Mnogo": minimal e-commerce SPA (React, PHP, Tailwind).

---

## Contact

- Telegram — [@lyoraeth_art](https://t.me/lyoraeth_art)
- Email — lyoraeth@gmail.com
- LinkedIn — [in/lyoraeth](https://www.linkedin.com/in/lyoraeth/)
- GitLab — [gitlab.com/lyoraeth](https://gitlab.com/lyoraeth)
