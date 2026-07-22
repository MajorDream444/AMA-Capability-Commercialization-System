# Source Manifest

All sources used to build this commercialization system, their authority tier, and their permitted and prohibited uses. When sources conflict, the disagreement is preserved in `decisions/decision-register.md` — never silently resolved.

## Authority order (highest first)

1. Current Decisions and explicit project instructions
2. Direct Zach / Hanzo meeting notes and verified Hanzo documentation
3. Hanzo Technical Paper Compendium (company-published)
4. AMA / Claude portfolio pressure-test analysis
5. AMA strategic analysis
6. Research reports
7. Podcast transcripts (creative adversarial material only)

## Source inventory

| ID | Source | Tier | Permitted use | Prohibited use |
|---|---|---|---|---|
| S1 | Current Decisions + project instructions | 1 | Canonical; governs all documents and overrides conflicts | — |
| S2 | ZK meeting notes + transcript (Gemini), 2026-07-21 | 2 | Founder-Reported claim entries; Enso architecture description; timeline/context; open questions | Do not treat performance/technical claims as verified; **exclude all personal commentary** unrelated to Hanzo/Enso/commercialization |
| S3 | **Hanzo Technical Paper Compendium** (`hanzo-compendium.md`; HAI paper suite, Zach Kelling / Hanzo Industries; "approved for public release; distribution unlimited"; published at papers.hanzo.ai) | 3 | Authoritative for Hanzo's **official positioning**; source of the reconciled case-study figures; cryptography/protocol/model claims logged **Hanzo-Published** with provenance | **Does not independently verify performance claims.** No auto-upgrade to Verified. Cite as "Hanzo publishes/states," never as independent fact |
| S4 | Hanzo published write-ups: "Hanzo's Sovereign Operating System for AI Agents," "Sovereign Operating System for Agentic Companies" | 3 | Positioning language and stack description | Same as S3 |
| S5 | AMA strategic analysis: `Rabbit Portfolio Pressure-Test`, `700 Repo Stack Review`, `Rabbit-Elephant-Whale Analysis`, `Our consolidated review of Claude and the podcasts`, `Comparing to Thinking Machines` | 4–5 | Doctrine, portfolio ranking, ICP shaping, contradiction identification | Analysis, not primary evidence; do not cite as proof of a Hanzo capability |
| S6 | Sovereign_OS_Blueprint.pdf (18 slides, NotebookLM) | 5 | Tier structure; offer framing; the deployable-vs-awaiting-evidence claim matrix; 8 strategic priorities | Numbers logged Founder-Reported; slide "Three Undeniable Entry Offers" conflicts with active portfolio — see decision register |
| S7 | Podcast transcript — "Winning 1000 Hanzo and Enso customers" | 7 | Objection libraries; discovery-call language; disqualification patterns; MVE structure ideas; ICP color | **No claim, price, readiness assessment, timeline, or customer target treated as fact** |
| S8 | Podcast transcript — "Hanzo roadmap to 1000 paying customers" | 7 | Same as S7; sovereignty-vs-retraining tension; 90-day framing | Same as S7 |
| S9 | "Sovereign OS for Agentic Companies" transcript + "How to Structure an Agentic Company" explainer/mp4 | 7 | Human-governance framing; transmission analogy for positioning | Same as S7 |
| S10 | **"7 AI Agents Businesses Are Paying $3,000–$10,000 For Right Now"** (AI Revolution X) | **Low — market research / promotional** | May inform: offer comparisons; SMB pricing **hypotheses**; recurring-revenue models; competitive positioning; Revenue Response System research; Document & Proposal Intelligence research; workflow-automation opportunity mapping | **Prices, demand claims, and statistics are promotional assertions — NOT independently verified market data.** Never cite as market fact |
| S11 | Hanzo Compendium — 22-paper suite (ZAP, FHE, Formal Verification, Autonomous Agentic AI, Edge AI/ML, Assured Networking, Counter-Exploitation, Quantum Sensing/QKD, T&E, etc.) | 3 | Capability depth for whale/elephant positioning | Hanzo-Published; not independent verification |

## Sources referenced but not treated as primary evidence

- **Audio/video duplicates** (`*.m4a`, `*.mp4`): identical content to the transcripts above; not separately mapped.
- **Non-Hanzo cache docs** (e.g., `Guochang_Gold_Transaction_Procedure`): out of scope for commercialization; not used.

## Notes

- The Compendium reconciles several figures that appear inconsistently in the verbal update (commit counts, lines of code). Where they differ, both are recorded in the decision register and the evidence registry rather than resolved.
- No confidential client information or credentials are stored in this repository from any source.
