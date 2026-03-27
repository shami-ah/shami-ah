# Hey, I'm Shami 👋

**AI Automation Architect** — I build systems where AI agents run businesses, not just answer questions.

```
Ingest → Classify → Orchestrate → Review → Execute → Observe
```

## What I Build

🔍 **[CodeLens](https://github.com/shami-ah/codelens)** — Open-source AI code review engine
- 154 patterns across TypeScript, Python, Go, SQL
- Security taint tracking (source → sink analysis)
- PR Risk Score (1-10 with transparent factors)
- Zero runtime dependencies, <1 second reviews
- Used in production across 300+ PRs

🏢 **OpenEvent** — AI-powered event management platform (production SaaS)
- React + TypeScript + Supabase + Stripe
- AI orchestration: email threads → task extraction → workflow execution → auto-approval
- Deployed on Hostinger VPS via GitHub Actions

🛠️ **[Command Center](https://github.com/shami-ah/shami-command-center)** — Dev command center
- Unified email/calendar/task interface
- Claude API + Google Gemini + Supabase

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

**AI:** Claude API, OpenAI, Groq, LangChain, RAG pipelines, prompt engineering
**Frontend:** React, Next.js, TypeScript, Tailwind, shadcn/ui
**Backend:** Supabase (PostgreSQL, Edge Functions, Auth, Storage), Node.js, Express
**Infrastructure:** GitHub Actions, Hostinger VPS, Cloudflare, Docker
**Tools:** Claude Code (2000+ hours), Git, Playwright, n8n automation

## Currently Building

- 🔬 **CodeLens v0.3** — Tree-sitter AST integration
- 🤖 **AI Agent Orchestrator** — Open-source multi-agent framework
- 📊 **LLM Observability Dashboard** — Self-hosted LLM monitoring

## Links

🌐 [Portfolio](https://portfolio-site-alpha.pages.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/muhammad-ahtesham-ahmad-a153801b5) · 📧 iamshami1996@gmail.com

---

*"The best engineers don't just write code — they design systems that make decisions."*
