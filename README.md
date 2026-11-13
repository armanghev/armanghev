# Arman Ghevondyan

**Full-stack / product engineer** based in Los Angeles, CA  
[armanghev.com](https://armanghev.com) · [arman@armanghev.com](mailto:arman@armanghev.com) · Available for hire

---

## About

I build developer tools, AI infrastructure, and full-stack products, from native macOS apps to multi-agent coordination platforms. I gravitate toward local-first, self-hostable tools that give developers real ownership over their stack.

---

## Tech Stack

**Frontend:** React, Next.js, TypeScript, Tailwind CSS, Vite  
**Backend:** Node.js, Fastify, Python, Django, FastAPI  
**Native:** Swift, SwiftUI, Expo, Tauri  
**Databases:** PostgreSQL, Supabase, Neon, SQLite, Drizzle ORM  
**Infrastructure:** Vercel, Railway, Cloudflare, AWS, DigitalOcean  
**AI/Agents:** Claude API, MCP, Claude Code, multi-provider LLM routing, agentic workflows

---

## What I'm building now

### [Onsen](https://getonsen.app)
A study app for high school and college students on iPhone, iPad, and the web. Add your classes and test dates and it builds a countdown plan for each test, schedules flashcards and quizzes with spaced repetition (FSRS), and gives you a Socratic tutor that makes you think instead of handing you answers. The waitlist is open. *Expo · Next.js · Hono · Cloudflare Workers · Claude API*

### [Envy](https://armanghev.com/projects/envy)
A native macOS app and CLI (also on Linux) that moves `.env` files out of the repo and into the Keychain, then injects the right variables when you run `pnpm dev`, `python`, `cargo`, or `docker compose` in a project folder. Git-aware worktrees and branch variables, a pre-commit secret guard, Touch ID-protected production values, and reviewed sync with Vercel, GitHub Actions, Cloudflare, AWS, and more. *Swift · SwiftUI*

---

## Shipped

### [orchestrat](https://github.com/armanghev/orchestrat)
A self-hosted coordination plane for one developer and several coding agents. Claude Code, Codex, Cursor, and Antigravity connect through a CLI and MCP bridge to claim tasks, hand off work, and share versioned docs and project chats, with branches that follow Git. Runs as one Docker image next to PostgreSQL. Source-available (ELv2), docs at [orchestrat.dev](https://orchestrat.dev). *Fastify · PostgreSQL · React · MCP · Docker*

### [pai](https://github.com/armanghev/pai)
A Telegram assistant running a Claude tool loop. It plans study time around a full-time job, watches Canvas for new work and grade changes, reads email and voice notes, and runs recurring jobs, with a hard daily spending cap. *Python · Claude API · Telegram · SQLite*

---

## Open source

### [modelport](https://github.com/armanghev/modelport)
A local-first AI proxy that translates between OpenAI and Anthropic request formats, keeps provider keys in one vault, and makes routing, usage, and cost observable.

### [mock-ai-api](https://github.com/armanghev/mock-ai-api)
A deterministic local test double for the OpenAI and Anthropic APIs. Simulate streams, tool calls, rate limits, and provider failures without spending a token. Published on PyPI.

### [chargen](https://github.com/armanghev/chargen)
AI character generator that produces portraits and metadata with Google Gemini. Built with Next.js, Clerk, Neon, and Cloudflare R2.
