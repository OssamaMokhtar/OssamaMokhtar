<h1>Ossama Mokhtar</h1>

<p><strong>Head of Product · AI-Native Product Leader</strong><br>
Dubai, UAE — building across GCC, EU, and US markets</p>

<p><em>I lead AI product portfolios and still write the prototype. The combination is the point:<br>
strategy that survives contact with implementation, because the same person did both.</em></p>

---

## Where I've moved the number

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

## How I work

**Unit economics before features.** Cost per successful outcome is a product decision before it is a finance one. An AI feature whose inference cost scales with engagement has inverted SaaS margins, and that belongs in the spec — not the post-mortem.

**Evals are the quality bar, not a demo.** If you cannot state what "good" means for a model's output and measure it on every change, you do not have a product — you have a prompt that worked once. [My triage eval suite](https://github.com/OssamaMokhtar/Tabibi/tree/main/evals) fails the build on a single missed emergency, and never on over-caution. The asymmetry is the design.

**Security is a product surface.** Key handling, data boundaries, and access rules get designed alongside the interface. I have shipped Firestore rulesets with ownership verification and field-level immutability, and I have caught client-side key exposure in my own code and fixed it before deploy.

**Bilingual by construction.** In the GCC, Arabic/English is a structural constraint, not a localisation ticket. RTL that mirrors *structurally* rather than a translated LTR page — [see it side by side](https://github.com/OssamaMokhtar/Tabibi).

**The tradeoff is the decision.** I document tradeoffs before roadmaps. A roadmap without a stated non-goal is a wish list.

---

## Selected work

Public prototypes and architecture, built to think through problems I care about. Live links where deployed.

### Financial services
**[RiskFree](https://github.com/OssamaMokhtar/RiskFree)** — AI credit scoring for GCC lending
Expatriates with thin bureau files and SMEs with informal cash flow are invisible to conventional scoring. PD/LGD models, AML screening, an LLM copilot over regulatory policy, and an AR/EN tone system. **[11 architecture documents](https://github.com/OssamaMokhtar/RiskFree/tree/main/docs)** — data model, ML pipeline, RAG design, scoring logic, security posture. · [Demo](https://ossamamokhtar.github.io/RiskFree/)

**[ServeMe](https://github.com/OssamaMokhtar/ServeMe-Projects)** — QR split-by-item restaurant checkout
Even-split apps get it wrong when one person had tap water. Each diner settles only what they ordered.

### Healthcare
**[Tabibi](https://github.com/OssamaMokhtar/Tabibi)** — bilingual AI family health advocate for MENA
Schema-constrained triage returning a defined `SELF_CARE` / `GP_CONSULT` / `EMERGENCY` enum, so an emergency is a hard UI path rather than prose a frightened user skims. Recall on `EMERGENCY` is the gate; a single miss fails the build.

### AI product tooling
**[Product Leadership OS](https://github.com/OssamaMokhtar/product-leadership-os)** — an operating system for product leadership
189 specialist agent skills, deduplicated from a ~250-name brief and ranked by leverage. The deduplication *is* the product: a library with three agents that write the same memo is worse than one that writes it well. Ships as Claude Code skills, an Obsidian knowledge graph, and an interactive explorer. · [Explore](https://ossamamokhtar.github.io/product-leadership-os/)

**[PolyVerses](https://github.com/OssamaMokhtar/PolyVerses)** — agentic PM workbench
Orchestration console, agent network diagram, observability. The interesting question is never what the model said — it is which agent ran, on what input, and why.

### Hospitality · Education · Careers
**[Avera AI](https://github.com/OssamaMokhtar/Avera-AI)** — yield optimisation for GCC hospitality. RevPAR/ADR/RevPASH with Ramadan, Eid, and the Fri–Sat weekend as first-class demand inputs, not anomalies.

**[Slang](https://github.com/OssamaMokhtar/Slang)** — pronunciation coach with per-phoneme scoring. Most language apps grade vocabulary because it is easy to score; pronunciation is where adult learners actually stall. · [Live](https://slang-ossamamokhtars-projects.vercel.app)

**[CareerOracle](https://github.com/OssamaMokhtar/OS3)** — career platform built on measured signal rather than self-report. · [Live](https://os-3-ossamamokhtars-projects.vercel.app)

---

## Working in the open

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

Working on: multi-agent orchestration and handoff accountability · LLM evaluation for safety-critical output · the economics of agent-heavy products.

**Open to** Principal PM, Group PM, Director, and Head of Product roles — GCC, EU, US, or remote. Also advisory.

[LinkedIn](https://www.linkedin.com/in/ossama-mokhtar/) · [X](https://x.com/OsamaElMokhtar) · ossamaelmokhtar@outlook.com
