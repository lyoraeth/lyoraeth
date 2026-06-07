# Hi, I'm Danil

Frontend developer. I build interfaces and small web products end to end — markup, animation, performance, build setup.

**Open to frontend roles** (Saint Petersburg or remote) from July 2026.

> Most of my commercial work lives in private GitLab, so this GitHub is mostly personal projects and experiments.

## What I've been working on

At **Dancecolor** (a web studio) I worked on a few commercial projects:

- **Spliteks** — industrial portal on Bitrix, legacy codebase. Rewrote the frontend: split the monolithic `main.js/main.css` into SCSS modules, moved critical parts to TypeScript, migrated the build to Gulp tuned for Bitrix. Cut CSS from 1.2 MB to 143 KB; PageSpeed 69 → 89 (desktop). Swapped ScrollSmoother for Lenis to kill ScrollTrigger race conditions; GSAP animations and pin-sections that survive zoom and resize.
- **Apple Inside** — e-commerce on Bitrix. Built a small design system for rich-content product pages (atomic classes, tokens, docs) — assembling a new page dropped from ~12h to ~3h. Rebuilt the stories module on Swiper: lazy init, memory cleanup, fluid `clamp()` layout, stable height on iOS via the visualViewport API.
- **Reckful** — e-commerce on a modern stack, in a small team. Catalog search, reviews with pagination, REST API integration.

Outside the studio I build **Telegram bots with payment integration** (aiogram, FSM, offer-agreement step, content delivery after purchase) for private clients, and built a CRM frontend from scratch on **Vue 3 + Pinia + TanStack Query** (Laravel REST API, Shadcn UI).

## A bit about how I work

I care about how the whole thing behaves — performance, different devices, how forms actually feel to use. I'm fine picking up incomplete or shifting requirements: I ask what's actually needed and get it done.

I run my own server — Gitea, Vaultwarden, mail, Nginx, Cloudflare tunnel. Not a DevOps, just got tired of depending on other people's infrastructure. It's also where my clients' sites and bots live.

I work in Figma properly, not only reading specs — components, variants, tokens. And I use AI as a tool day to day, keeping control over what ends up in the code.

## Stack

**Daily:** JavaScript / TypeScript · Vue 3 · Pinia · TanStack Query · SCSS / BEM · GSAP · Gulp · Vite · Git

**Also:** React · Tailwind · REST API · Postman · Python (aiogram) · Figma

## Selected projects

- [**personal-portfolio-archived**](https://github.com/lyoraeth/personal-portfolio-archived) — client-side SPA with custom slide-like routing, GSAP, device-specific builds and localization. My first serious project; a month of nights, and the one that pushed me the most.
- [**aiogram-yoomoney-bot**](https://github.com/lyoraeth/aiogram-yoomoney-bot) — Telegram bot for selling digital content with payment integration. The early, simple base of what I now build for clients.
- [**Simple-Header**](https://github.com/lyoraeth/Simple-Header) — small React / TS / Framer Motion piece: a morphing menu button built as a state machine, noise-driven background motion, iOS fixes.

## Contact

- Telegram — [@lyoraeth_art](https://t.me/lyoraeth_art)
- LinkedIn — [in/lyoraeth](https://www.linkedin.com/in/lyoraeth/)
- GitLab — [gitlab.com/lyoraeth](https://gitlab.com/lyoraeth)
- Email — lyoraeth@gmail.com
