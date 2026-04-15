# Hey, I'm Engr Ahtesham Ahmad 👋

**AI Automation Architect** — I build systems where AI agents run businesses, not just answer questions.

```
Ingest → Classify → Orchestrate → Review → Execute → Observe
```

## What I Build

🤖 **Gogaa CLI** — Claude Code alternative (v0.9.1)
- Full AI coding agent: 11 providers, auto-fallback, React Ink TUI
- Aider parity: repo map (tier-aware), SEARCH/REPLACE edits, watch mode (`// AI!`), LLM commit messages
- Plugin marketplace TUI, parallel agent panes, scheduled triggers, branch checkpoints
- 1418 passing tests · built because nothing else had everything

🔍 **CodeLens** — AI code review engine (v0.3.3)
- 305 patterns across 9 stacks (TypeScript, Python, Go, Java, Ruby, PHP, Next.js, FastAPI, Spring Boot)
- Guardian mode: injects pattern library into Claude Code, Cursor, Windsurf, Copilot — prevents bugs before they're written
- Security taint tracking, PR Risk Score (1-10), zero runtime dependencies, <1 second reviews
- Tested against: vercel/next.js, discourse/discourse, monicahq/monica, spring-petclinic

🏢 **OpenEvent** — AI-powered event management platform (production SaaS)
- React + TypeScript + Supabase + Stripe
- AI orchestration: email → classification → task extraction → workflow execution → auto-approval

🛠️ **Command Center** — Personal AI operations PWA (private)
- Unified email/calendar/task interface with Claude API + Google Gemini + Supabase

## Architecture Patterns I Use

```
┌─────────────┐     ┌──────────────┐     ┌─────────────┐
│  AI Agents  │────▶│ Orchestrator │────▶│  Execution   │
│  (classify) │     │  (plan/route)│     │  (tools/DB)  │
└─────────────┘     └──────────────┘     └─────────────┘
       │                    │                     │
       └────────────────────┼─────────────────────┘
                            ▼
                    ┌──────────────┐
                    │   Observe    │
                    │ (learn/adapt)│
                    └──────────────┘
```

## Tech Stack

**AI:** Claude API, OpenAI, Groq, LangChain, RAG pipelines, multi-provider routing
**Frontend:** React, Next.js, TypeScript, Tailwind, shadcn/ui, React Ink (TUI)
**Backend:** Supabase (PostgreSQL, Edge Functions, Auth, Storage), Node.js, Python
**Infrastructure:** GitHub Actions, Docker, Cloudflare, n8n automation
**Dev Tools:** Claude Code, CodeLens, gogaa (my own CLI)

## Currently Building

- 🏗️ **Gogaa Architect Mode** — two-model split: planner + coder. No other open-source CLI has this.
- 🔗 **Spec-to-Code Traceability** — link requirements to implementation. The unclaimed layer in the agentic coding stack.
- 🌳 **CodeLens v0.4** — tree-sitter AST integration for true semantic analysis

## Links

🌐 [Portfolio](https://portfolio-site-4nb.pages.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/muhammad-ahtesham-ahmad-a153801b5) · 📧 iamshami1996@gmail.com

---

*"The best engineers don't just write code — they design systems that make decisions."*
