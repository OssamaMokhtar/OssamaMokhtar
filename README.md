<h1>Ossama Mokhtar</h1>

<p><strong>Founder &amp; Principal, BubblesUPs · AI Product Leader</strong><br>
Dubai, UAE — building across GCC, EU, and US markets</p>

<p><em>I lead AI product portfolios and still write the prototype. The combination is the point:<br>
strategy that survives contact with implementation, because the same person did both.</em></p>

---

## Flagship

### [PolySync](https://github.com/OssamaMokhtar/PolySync) — AI coaching for hybrid athletes, where the model cannot prescribe

Endurance and strength training interfere with each other. Most apps run two plans in parallel and leave the athlete to absorb the collision. In PolySync a **deterministic engine owns every load prescription**. The LLM explains and *proposes* changes, and each proposal must clear a bounds checker before it reaches an athlete. Anything blocked goes to a human coach.

- **Built:** engine, bounds checker (9 rules: days, time, injury, volume jumps, unknown exercises…) and routing, all in one repo with the design docs.
- **Measured (safety layer, every push):** 0 contraindicated exercises in 8,640 generated plans; 2,067 of 2,067 unsafe proposals blocked and escalated to the coach; 194 of 194 safe substitutions accepted.
- **Not yet measured:** model proposal quality, coach minutes per athlete, real users. The rules are v0 and not yet coach-signed. [GAPS.md](https://github.com/OssamaMokhtar/PolySync/blob/main/docs/GAPS.md) lists what's open, ranked.

[Decision log](https://github.com/OssamaMokhtar/PolySync/blob/main/docs/10-decision-log.md) · [Eval results](https://github.com/OssamaMokhtar/PolySync/tree/main/evals) · [Architecture](https://github.com/OssamaMokhtar/PolySync/tree/main/docs)

---

## Selected work

Public prototypes, each with CI that can actually fail. Status is stated per project: none of these has users yet.

| Project | What it is | Honest status |
|---|---|---|
| **[Fluvio](https://github.com/OssamaMokhtar/Fluvio)** | AI pronunciation and fluency coach (Whisper → GPT-4o), 13 practice languages | Deployed on Vercel. Logs cost per scored utterance. Scores are model judgements, not acoustic measurement, and the product says so |
| **[Product Leadership OS](https://github.com/OssamaMokhtar/product-leadership-os)** + **[PolyVerses](https://github.com/OssamaMokhtar/PolyVerses)** | 189 ranked, deduplicated agent skills (Claude Code skills + Obsidian graph), and the workbench where they run | Library validated in CI. Workbench runs 5 agent modes; agent output quality not yet evaluated |
| **[RLens](https://github.com/OssamaMokhtar/RLens)** | Explainable alternative-data credit scoring for GCC thin-file borrowers, AR/EN | Reference architecture (12 docs) plus a clickable UI on sample data. No trained models |
| **[Youna](https://github.com/OssamaMokhtar/youna)** | AI wellness companion: check-ins, mood, journaling. Not a therapist | Pre-release. Crisis logic is deterministic and tested on a golden set in CI |
| **[Hirena](https://github.com/OssamaMokhtar/Hirena)** | Skills self-assessment and gap analysis for PMs, MENA-first | Prototype. Text only: facial and voice emotion analysis removed (EU AI Act Art. 5(1)(f)) |

---

## How I Work

**Unit economics before features.** Cost per successful outcome is a product decision before it is a finance one. An AI feature whose inference cost scales with engagement has inverted SaaS margins, and that belongs in the spec, not the post-mortem.

**Evals are the quality bar, not a demo.** If you cannot state what "good" means for a model's output and measure it on every change, you do not have a product. You have a prompt that worked once. Build evals that fail the build on a single missed critical case, never on over-caution. The asymmetry is the design.

**The model proposes; the system disposes.** Where being wrong hurts (training load, health, credit) the model never has the final write. Deterministic rules decide, and humans review what the rules block.

**Bilingual by construction.** In the GCC, Arabic/English is a structural constraint, not a localization ticket. RTL that mirrors *structurally*, rather than a translated LTR page, is table stakes.

**The trade-off is the decision.** I document trade-offs before roadmaps. A roadmap without a stated non-goal is a wish list.

---

## Client and employer outcomes

Outcomes from engagements I led as a consultant at BubblesUPs (since 2022) and in earlier roles. These are **not** from the portfolio prototypes above, which have no users yet. Engagement details are available on request.

| Outcome | Context |
|---|---|
| **$1.5M ARR** | AI-native product portfolio, multi-market |
| **+30% YoY revenue** | B2B/B2C commerce suite, 3 markets in 6 months |
| **22% → 34%** | Repeat purchase rate on that suite |
| **−45% design-to-code** | AI-assisted engineering workflow |
| **78% beta retention** | LLM knowledge system; relevancy +25%, ROUGE > 0.65 |
| **NPS 66 → 78** | CarTrawler |
| **+67% retention · +44% acquisition** | MoneyBekia, customer-centric redesign |

Earlier: Performance Manager at Vodafone, leading a 30-person cross-functional team; credit analyst at CIB.

---

## Working in the open

Every project repository runs CI on each push and pull request, and no step is allowed to pass on failure. Depending on the repo, that covers typecheck, lint, tests, build and a high-severity dependency audit. Where a project makes a safety or honesty claim, CI checks that claim too: PolySync's safety evals, Youna's crisis golden set, Hirena's "no emotion inference" test, and Fluvio's documented-claims verifier.

In September 2026 I audited my own portfolio against the standard I'd hold a team to. It found builds that were red on `main`, CI steps that could never fail, and code that contradicted its own design docs. The fixes are in each repo's history.

---

## Stack

**AI systems:** LLM APIs (Gemini, GPT-4o, Whisper) · evals and scorecards · RAG · multi-model routing and fallbacks · deterministic guardrails · cost telemetry
**Build:** TypeScript · React · Node.js/Express · Next.js · Python · PostgreSQL · Firestore
**Cloud:** Vercel · GCP/Firebase · AWS
**Product:** RICE · unit economics · experiment design · ADRs with reversal triggers

---

## Currently

Founder & Principal at **BubblesUPs**. MBA at **Gies College of Business, University of Illinois Urbana-Champaign** (expected Nov 2026).

**Open to** Principal PM, Group PM, Director and Head of Product roles in AI products: GCC, EU, US or remote. Also advisory.

[LinkedIn](https://www.linkedin.com/in/ossama-mokhtar/) · [X](https://x.com/OsamaElMokhtar) · ossamaelmokhtar@outlook.com
