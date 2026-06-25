# Hi, I'm Danil — I take a task and get it done.

Frontend developer · Saint Petersburg or remote · open to roles from July 2026

> Most of my commercial work lives in private GitLab, so this GitHub is mostly personal projects and experiments.

Frontend at **Dancecolor** web studio, where I take the frontend on commercial projects end to end — legacy rebuilds, feature work, and the parts nobody scoped. Focus: pixel-perfect implementation, performance engineering, and untangling legacy into something maintainable.

---

## What I work on

**Spliteks** — industrial portal on Bitrix, legacy codebase. Rewrote the frontend: split the monolithic `main.js` / `main.css` into SCSS modules, moved critical parts to TypeScript, migrated the build to Gulp tuned for Bitrix. Cut CSS from **1.2 MB → 143 KB**; PageSpeed **69 → 89** (desktop). Swapped ScrollSmoother for Lenis to kill ScrollTrigger race conditions; GSAP animations and pin-sections that survive zoom and resize.

**Apple Inside** — e-commerce on Bitrix. Built a small design system for rich-content product pages (atomic classes, tokens, docs) — assembling a new page dropped from ~12h to ~3h. Rebuilt the stories module on Swiper: lazy init, memory cleanup, fluid `clamp()` layout, stable height on iOS via the visualViewport API.

**Reckful** — e-commerce on a modern stack, in a small team. Catalog search, reviews with pagination, REST API integration.

**Legacy CRM (PHP)** — currently untangling a large, undocumented legacy CRM: no version control, FTP-only access, and a tangled stylesheet (heavy on `!important`) to rebuild from scratch with no docs to lean on. The kind of task with no clean entry point — the job is to find one.

Alongside these, a steady stream of smaller fixes across other projects — I'm usually the one dropped in when something needs solving.

Outside the studio I build **Telegram bots with payment integration** (aiogram, FSM, offer-agreement step, content delivery after purchase) for private clients, and built a **CRM frontend from scratch** on Vue 3 + Pinia + TanStack Query (Laravel REST API, Shadcn UI).

---

## How I work

I care about how the whole thing behaves — performance, different devices, how a form actually feels to use. I'm fine picking up incomplete or shifting requirements: I find out what's actually needed and get it done. I tend to hold the whole project in my head rather than just my slice, which is how I catch things outside my immediate scope — and lately that's been pulling me toward audits and product-side thinking.

I run my own server — Gitea, Nginx, Cloudflare tunnel — not as a DevOps, just to stop depending on other people's infrastructure. It's where my clients' sites and bots live, and the deploy target for this site's CI/CD.

I work in Figma properly, not only reading specs — components, variants, design tokens. When there's no designer, I pick up the file and finish the job. And I use AI as a daily tool while keeping control over what lands in the code.

---

## Stack

**Daily:** JavaScript / TypeScript · Vue 3 · Nuxt · Pinia · TanStack Query · SCSS / BEM · Tailwind · GSAP · Gulp · Vite · Git

**Also:** React · Node · REST API · Postman · Python (aiogram) · Docker · GitHub Actions · Figma

---

## Projects

**[lyoraeth.art](https://github.com/lyoraeth/lyoraeth-art)** — this site, and my most technically demanding project to date — in some ways more than the legacy rebuilds at the studio. Nuxt 4 SSR with clean hydration, a design system driven entirely by CSS tokens, Sanity CMS through Nitro server routes, self-hosted cookie-free analytics, and full CI/CD — Docker build to live in ~3 minutes on push. The visual concept is atmospheric minimalism: depth from light and blur, not shadows on buttons. → **[lyoraeth.art](https://lyoraeth.art)**

- [**Simple-Header**](https://github.com/lyoraeth/Simple-Header) — recent React / TS / Framer Motion piece: a morphing menu button built as a state machine, noise-driven background motion, iOS fixes.

Older work — different stack, different era, kept for the record:

- [**ecommerce-portfolio-project**](https://github.com/lyoraeth/ecommerce-portfolio-project) — "Risa Mnogo": minimal e-commerce SPA (React, PHP, Tailwind).
- [**personal-portfolio-archived**](https://github.com/lyoraeth/personal-portfolio-archived) — client-side SPA with custom slide-like routing, GSAP, device-specific builds and localization. My first serious project — a month of late nights, and the one that taught me the most.
- [**aiogram-yoomoney-bot**](https://github.com/lyoraeth/aiogram-yoomoney-bot) — Telegram bot for selling digital content with payment integration. The early, simple base of what I now build for clients.

---

## Contact

- Telegram — [@lyoraeth_art](https://t.me/lyoraeth_art)
- Email — lyoraeth@gmail.com
- LinkedIn — [in/lyoraeth](https://www.linkedin.com/in/lyoraeth/)
- GitLab — [gitlab.com/lyoraeth](https://gitlab.com/lyoraeth)
