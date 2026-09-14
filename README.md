# Hi, I'm Danil.

Frontend developer — Vue 3, Nuxt, TypeScript.

> Most commercial work lives in private GitLab — this GitHub is mostly personal projects and experiments.

---

## What I work on

**CRM frontend (freelance, ongoing)** — Vue 3 + Pinia + TanStack Table on top of Laravel. The backend originally wanted full control over the frontend through Inertia.js, but the lack of a clear spec made the project unworkable that way — I pushed for splitting it into a separate SPA (migrated to Vue) and REST API, and the frontend has moved at its own pace since. Alongside it, a few Telegram bots with payment integration (aiogram, state machines, content delivery after purchase).

**Dancecolor** (Nov 2025 – Jul 2026) — frontend on four commercial projects, mixed stack.

- **Spliteks** — industrial portal on Bitrix, legacy `main.js`/`main.css`. Split it into SCSS modules and TypeScript, moved the build to Gulp. Wrote the GSAP animations myself — interactive sections, a smart header, a Lottie footer — first on ScrollTrigger-pin, rebuilt on native `sticky` after it stuttered on weaker devices. Also worked on code and media optimization. CSS **1.2 MB → 143 KB**, PageSpeed **69 → 89**.
- **Apple Inside** — e-commerce on Bitrix. The original repo lived in a former frontend developer's personal account and hadn't been updated in six months. Cloned it, brought it current, documented it, handed it back to the studio to maintain. Extracted design tokens from Figma files for rich-content product pages: assembling a new A+ landing dropped from ~2 days to 3–6 hours. Rebuilt the stories module on Swiper, added a swipe-through product preview, lazy-load and skeletons site-wide.
- **Legacy CRM** — plain PHP, no version control, FTP-only access. Set up a repo and an FTP auto-sync (watcher + post-commit hook) to get git history. A full pass on mobile responsiveness, 30+ fixes.
- **Reckful** — e-commerce, modern stack, team project. Catalog search, paginated reviews, REST API integration.

---

## How I work

Run my own server — Nginx, Docker, CI/CD; client sites and bots deploy there, and so does the build of my personal site. Also do design work in Figma — components, variants, tokens. Use AI in my workflow (Claude Code, Gemini, Qwen) with manual verification, alongside search, mostly against docs (Tailwind's, for instance). Keep up with new approaches through articles on Habr and Medium.

Also write about frontend, UX and development: [lyoraeth.art/writing](https://lyoraeth.art/writing).

---

## Stack

**Frontend:** TypeScript · JavaScript · Vue 3 · Nuxt · Pinia · TanStack Table · GSAP · Tailwind · SCSS
**Tooling:** Git · Gulp · Vite · Figma
**Also:** REST API · Python · Docker · GitHub Actions · React

---

## Projects

- **[lyoraeth.art](https://github.com/lyoraeth/lyoraeth-art)** — personal site, the most involved thing I've built solo. Nuxt 4 SSR, a design system driven entirely by CSS tokens, Sanity CMS through Nitro server routes, self-hosted cookie-free analytics, full CI/CD (push to live in ~3 minutes). → **[lyoraeth.art](https://lyoraeth.art)**
- **[Simple-Header](https://github.com/lyoraeth/Simple-Header)** — the test task that got me the Dancecolor role. React / TS / Framer Motion, a morphing menu button built as its own state machine.
- Currently building two utilities, **[carrier-pigeon](https://github.com/lyoraeth/carrier-pigeon)** and **[gostling](https://github.com/lyoraeth/gostling)** — their concept is written up in the repos.

Older, kept for the record:

- **[personal-portfolio-archived](https://github.com/lyoraeth/personal-portfolio-archived)** — my first serious overengineering exercise in full bloom: a hand-rolled SPA controller that made the site behave like a PowerPoint presentation, plus a pile of unjustified effects that made it heavy.
- **[aiogram-yoomoney-bot](https://github.com/lyoraeth/aiogram-yoomoney-bot)** — my first paid job building Telegram bots.
- **[ecommerce-portfolio-project](https://github.com/lyoraeth/ecommerce-portfolio-project)** — "Risa Mnogo": came up with the brand, design and positioning, tried to build it as a site. Later used the same project for my diploma defense.

---

## Contact

Telegram — [@lyoraeth_art](https://t.me/lyoraeth_art) · Email — lyoraeth@gmail.com · [LinkedIn](https://www.linkedin.com/in/lyoraeth/) · [GitLab](https://gitlab.com/lyoraeth)
