<h1>Ossama Mokhtar</h1>

<p><strong>Head of Product · AI-Native Product Leader</strong><br>
Dubai, UAE — building across GCC, EU, and US markets</p>

<p><em>I lead AI product portfolios and still write the prototype. The combination is the point:<br>
strategy that survives contact with implementation, because the same person did both.</em></p>

---

## What I'm Building Now

### [Youna](https://github.com/OssamaMokhtar/youna) — AI Therapist, Wellness Coach & Companion

**An AI-native emotional wellness platform.** Youna learns your personality, tracks your mood, guides your journaling, and stays present through daily check-ins — all wrapped in a safety-first architecture that never positions itself as a replacement for professional care.

**Phase One MVP is live** (Next.js 15, TypeScript, Tailwind CSS):

| Route | Purpose |
|-------|---------|
| `/` | Landing page — hero, features, how-it-works, safety, CTA |
| `/chat` | Full chat interface with Youna — text conversations, mood-aware AI, quick actions, mood check-in + journal prompt modals |
| `/assessment` | Personality assessment onboarding — Big Five axes, attachment style selector, goals input → personality profile |
| `/features` | Feature overview |
| `/about` | Mission, story, values, what Youna is / is not |

**What's in Phase One:**
- AI Chat Companion with emotional tone detection (stressed / sad / anxious / happy / neutral)
- Personality DNA Engine — Big Five + Attachment Theory, with MBTI/DISC/Enneagram in the architecture
- Conversational Memory (session-based)
- Mood Tracking UI with mood-aware chat
- Journaling — AI-guided prompts (gratitude, stress, reflection, goals, relationships)
- Daily Check-ins UI
- Goal & Habit Tracking UI
- Safety Layer — crisis detection keywords, "not a therapist" disclaimers on every screen, real crisis resources modal, professional referral pathway (designed)

**Roadmap:**
- **Phase Two** — Voice conversations (STT/TTS), advanced personality DNA (HEXACO, Enneagram, DISC, Jungian cognitive functions, Love Languages), real mood tracking with history + charts, real journaling with AI reflection, daily check-in streaks, safety layer hardening
- **Phase Three** — LLM integration with model routing + cost optimization + fallbacks, long-term memory (vector store + user context persistence), AI Coaching engine, social ecosystem integrations (LinkedIn, X, Instagram, calendars, health apps — explicit user consent only), enterprise B2B2C (corporate wellness, schools, telehealth partnerships)
- **Phase Four** — Predictive wellness AI, digital twin model, multi-agent AI team (Therapist Agent, Coach Agent, Wellness Agent, Goal Agent, Social Agent), global expansion + localization

### [Slang](https://github.com/OssamaMokhtar/Slang) — AI Language Learning Companion

AI-powered language learning companion. Personalized, conversational, adaptive — designed to make language learning feel natural and human.

### [Hirena](https://github.com/OssamaMokhtar/Hirena) — AI Skills Assessment Platform

OpenAI-powered skills assessment. Evaluates professional capabilities through AI-driven conversation and analysis. Bilingual AR/EN, MENA-first.

---

## Where I've Moved the Number

Four years leading product at BubblesUPs, across a portfolio of AI-native products in e-commerce, HR tech, and productivity — USA, UK, UAE, and GCC.

| Outcome | Context |
|---|---|
| **$1.5M ARR** | AI-native product portfolio, multi-market |
| **+30% YoY revenue** | B2B/B2C commerce suite, 3 markets in 6 months |
| **22% → 34%** | Repeat purchase rate on that suite |
| **−45% design-to-code** | AI-assisted engineering workflow, production discipline retained |
| **−30% time-to-hire · $200K saved** | Hirena, HR analytics; precision@10 68% → 85% |
| **78% beta retention** | LLM knowledge system; relevancy +25%, ROUGE > 0.65 |
| **NPS 66 → 78** | CarTrawler — top-decile for the industry |
| **+67% retention · +44% acquisition** | MoneyBekia, customer-centric redesign |

Earlier: Performance Manager at Vodafone leading a 30-person cross-functional team; credit analyst at CIB. Seven industries — banking, telecom, fintech, travel, mobility, HR tech, commerce.

---

## How I Work

**Unit economics before features.** Cost per successful outcome is a product decision before it is a finance one. An AI feature whose inference cost scales with engagement has inverted SaaS margins, and that belongs in the spec — not the post-mortem.

**Evals are the quality bar, not a demo.** If you cannot state what "good" means for a model's output and measure it on every change, you do not have a product — you have a prompt that worked once. Build evals that fail the build on a single missed critical case, never on over-caution. The asymmetry is the design.

**Safety is a product surface.** For AI products in wellness, health, and coaching, safety architecture is not a compliance checkbox — it is the core product. Crisis detection, professional referral pathways, clear AI/human boundaries, consent-first integrations: these are designed alongside the interface, not bolted on after.

**Bilingual by construction.** In the GCC, Arabic/English is a structural constraint, not a localization ticket. RTL that mirrors *structurally* rather than a translated LTR page is table stakes.

**The tradeoff is the decision.** I document tradeoffs before roadmaps. A roadmap without a stated non-goal is a wish list.

---

## Selected Work

Public prototypes and architecture, built to think through problems I care about. Live links where deployed.

### AI Wellness & Companion (current focus)

**[Youna](https://github.com/OssamaMokhtar/youna)** — AI Therapist, Wellness Coach & Companion Platform
AI-native emotional wellness: personalized conversation, personality DNA, mood tracking, journaling, daily check-ins, clinical safety. Phase One MVP live.

**[PolySync](https://github.com/OssamaMokhtar/PolySync)** — AI coaching for hybrid athletes, human coach in the loop
Endurance and strength adaptations interfere with each other. Mainstream apps run two plans in parallel and let the athlete absorb the collision. A deterministic engine owns every load prescription; the LLM explains and *proposes* adaptations as structured deltas, each of which must clear a bounds checker before it reaches an athlete. Prompt injection cannot change training load, and a provider outage degrades the explanation rather than the training. [12 architecture documents](https://github.com/OssamaMokhtar/PolySync/tree/main/docs) — programming engine, RAG grounding, evaluation harness, and a decision log where every ADR carries a reversal trigger.

### Financial Services

**[RLens](https://github.com/OssamaMokhtar/RLens)** — AI credit scoring & risk platform for GCC lending
Expatriates with thin bureau files and SMEs with informal cash flow are invisible to conventional scoring. PD/LGD models, AML screening, an LLM copilot over regulatory policy, and an AR/EN tone system.

### Health · Human Performance

**[Fluvio](https://github.com/OssamaMokhtar/Fluvio)** — AI pronunciation & fluency coach
Real-time phonetic analysis, per-phoneme scoring, and articulation visualization. Most language apps grade vocabulary because it is easy to score; pronunciation is where adult learners actually stall.

### AI Product Tooling

**[PolyVerses](https://github.com/OssamaMokhtar/PolyVerses)** — agentic PM workbench + 183-skill agent library
Orchestration console, agent network diagram, observability dashboard, and a deduplicated skill library of 183 specialist agent skills from Product Leadership OS — ranked by leverage and wired into a dependency graph. Ships as a React/Firebase app and a Claude Code-ready skills layer. The interesting question is never what the model said — it is which agent ran, on what input, and why. · [Explore skills](https://github.com/OssamaMokhtar/PolyVerses/blob/main/SKILLS_INDEX.md)

### Hospitality · Education · Careers

**[Hirena](https://github.com/OssamaMokhtar/Hirena)** — AI-powered skills assessment & career pathing
Assess your skills against any job. See your gap. Find your path. Bilingual AR/EN, MENA-first. · [Live](https://hirena-ossamamokhtars-projects.vercel.app)

---

## Working in the Open

Every repository here runs CI on each push — typecheck, build, and a high-severity dependency audit. That gate has already caught real problems: a critical advisory, an incompatible dependency bump, and a serverless function that would have crashed at cold start.

I would rather a public repository show a strict gate that occasionally fails than a green badge that checks nothing.

---

## Stack

**AI systems** — LLM APIs · RAG · embeddings & vector search · prompt orchestration · multi-model routing · evals & scorecards · MLOps · model governance
**Build** — Python · TypeScript · React · Node.js · PostgreSQL · Firestore · REST APIs
**Cloud** — AWS · GCP · Vercel · serverless
**Product** — RICE · unit economics · experiment design · journey mapping · Mixpanel · Amplitude

---

## Currently

Head of Product at **BubblesUPs**. MBA at **Gies College of Business, University of Illinois Urbana-Champaign** (2026).

Working on: multi-agent orchestration and handoff accountability · LLM evaluation for safety-critical output · the economics of agent-heavy products · **Youna: AI Therapist, Wellness Coach & Companion Platform — Phase One MVP live, Phase Two in build.**

**Open to** Principal PM, Group PM, Director, and Head of Product roles — GCC, EU, US, or remote. Also advisory.

[LinkedIn](https://www.linkedin.com/in/ossama-mokhtar/) · [X](https://x.com/OsamaElMokhtar) · ossamaelmokhtar@outlook.com
