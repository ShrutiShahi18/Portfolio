# Shruti Shahi — Portfolio

A single-page developer portfolio, styled as a futuristic system interface — skills as a "loadout," projects as "missions," experience as career progression, achievements as unlocked milestones.

**Live:** https://portfolio-gsx4.onrender.com/

## About

Full Stack & AI Systems Developer. MERN stack, production-grade LLM integrations, agentic development workflows (Claude, Codex, Cursor, Windsurf, Replit).

- GitHub: https://github.com/ShrutiShahi18
- LinkedIn: https://linkedin.com/in/shruti-shahi180803/
- Email: yoshruti18@gmail.com

## Sections

- **Profile** — summary, education, focus
- **Loadout** — skills, grouped by category, linked to the projects that actually use them
- **Missions** — OmniMarketX, AzzuroIQ, PitchPilot, with live/GitHub links and a full briefing modal
- **Experience** — Fareportal SDE internship, MLH Open Source Fellowship, Bruno & Cboard open-source contributions
- **Achievements** — DSA milestones, HackWithInfy, Gymkhana project, DevC, Enyugma

## Tech

Plain HTML/CSS/JS, animated with GSAP + ScrollTrigger. No build step, no dependencies — it's one self-contained `portfolio.html` file.

## Running it

Just open `portfolio.html` in a browser. To serve it locally:

```bash
npx serve .
```

## Editing content

All content lives in a few arrays near the top of the `<script>` block in `portfolio.html`:

```js
const skillCategories = [...]   // loadout
const projects        = [...]   // missions
const experience       = [...]  // career progression
const achievements     = [...]  // milestones
```

Edit an array, save, refresh — nothing else needs to change.
