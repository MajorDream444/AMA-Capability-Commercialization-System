# Evidence Registry

Every material technical or commercial claim about Hanzo, Enso, or Lux, with **evidence state kept separate from source provenance.** No claim may be marketed unless its **Evidence status** is `Verified`, and then only within the exact scope of its supporting artifact. See `claim-governance.md` for definitions.

## How to read each entry

Each claim carries five orthogonal fields:

1. **Evidence status** — one of exactly five canonical values: **Verified · Demonstrated · Founder-Reported · Roadmap · Unknown/Requires Verification.**
2. **Publisher / provenance** — who asserts it and where (e.g., "Hanzo Compendium / Hanzo-Published," "Zach Kelling / meeting transcript," "AI Revolution X / promotional"). *This is a provenance label, not an evidence state.* Appearing in the Compendium makes a claim **Hanzo-Published in provenance** — it does **not** raise its evidence status.
3. **Independent verification** — Yes / No.
4. **Unverified sub-status** — for any claim not `Verified`, exactly one of: **Not yet evaluated · Evidence requested · Evidence reviewed but insufficient · Blocked by permission · Blocked by missing reproducibility · Roadmap only.** ("Not Verified" is never left as one undifferentiated bucket.)
5. **Required artifact** — the specific evidence that would move it toward Verified.

> Canonical spellings: Hanzo, Enso, Lux, AMA Solutions, Zach Kelling, MAIM.

---

## A. Enso — performance and routing

### A1 — "Enso is the number one AI in the world"
- Evidence status: **Founder-Reported**
- Publisher/provenance: Zach Kelling — meeting notes + transcript, 2026-07-21 (~00:15, 00:19)
- Independent verification: No
- Unverified sub-status: **Evidence reviewed but insufficient** (a live dashboard is not independent proof; the Compendium itself disclaims model supremacy)
- Required artifact: independent, reproducible benchmark suite with published methodology and third-party review
- Marketing: **BARRED**

### A2 — 75–90% cost savings while meeting/exceeding frontier performance
- Evidence status: **Founder-Reported**
- Publisher/provenance: Zach Kelling — transcript 2026-07-21 (~00:07); also listed on the Blueprint "awaiting evidence" slide
- Independent verification: No
- Unverified sub-status: **Blocked by missing reproducibility**
- Required artifact: reproducible cost + quality study on defined workloads with published methodology
- Marketing: **BARRED**

### A3 — #1 across all categories on 14 top benchmarks
- Evidence status: **Founder-Reported**
- Publisher/provenance: Zach Kelling — transcript (~00:07)
- Independent verification: No
- Unverified sub-status: **Blocked by missing reproducibility**
- Required artifact: independent benchmark runs with configs and results
- Marketing: **BARRED**

### A4 — Microsecond, CPU-only routing (no GPU)
- Evidence status: **Founder-Reported**
- Publisher/provenance: Zach Kelling — transcript (~00:04)
- Independent verification: No
- Unverified sub-status: **Evidence requested** (from Zach, per DR-8)
- Required artifact: reproducible latency benchmark with methodology and hardware

### A5 — Coordinates 400+ models in parallel per request
- Evidence status: **Founder-Reported**
- Publisher/provenance: Zach Kelling — transcript; Blueprint awaiting-evidence slide
- Independent verification: No
- Unverified sub-status: **Evidence requested**
- Required artifact: architecture document + reproducible trace

### A6 — Enso retrains daily / continuously on anonymized customer usage
- Evidence status: **Founder-Reported**
- Publisher/provenance: Zach Kelling — transcript (~00:18–00:19)
- Independent verification: No
- Unverified sub-status: **Blocked by missing reproducibility** — also a direct conflict with the sovereignty promise (OPEN-QUESTIONS D6)
- Required artifact: written data-governance spec — opt-in/out, tenant isolation, weight-influence policy, retention

### A7 — Enso is an intelligence-selection / routing / consensus layer (evaluate → invoke multiple models → judge → synthesize)
- Evidence status: **Demonstrated** (as a described/observed architecture)
- Publisher/provenance: Decision Register #3; Blueprint "Inside the Enso Routing System"; Sovereign OS explainer — Hanzo-Published + AMA decision
- Independent verification: No
- Unverified sub-status: **Not yet evaluated** (this is a positioning/description claim, usable as description, not as a performance claim)
- Required artifact: none for description; performance requires A2–A5 artifacts

### A8 — Internal Enso routing works (live command center, cost slider)
- Evidence status: **Demonstrated**
- Publisher/provenance: Zach Kelling / Hanzo — transcript; Blueprint bottom note
- Independent verification: No
- Unverified sub-status: **Evidence reviewed but insufficient** (demo only, not reproducible proof)
- Required artifact: reproducible evaluation; use as demo only, never as proof

---

## B. Compendium — cryptography, models, protocol

Provenance for all B-items: **Hanzo Technical Paper Compendium** (`hanzo-compendium.md`, HAI paper suite, Zach Kelling / Hanzo Industries, "approved for public release; distribution unlimited," papers.hanzo.ai) — **Hanzo-Published**. Independent verification: **No** for all. Marketing requires reaching Verified.

| # | Claim | Evidence status | Unverified sub-status | Required artifact |
|---|---|---|---|---|
| B1 | Owned Zen-family weights, 0.8B–1T+, inspectable | Founder-Reported (publisher: Hanzo) | Evidence requested | Third-party inspection / weight-availability confirmation |
| B2 | ML-KEM-768 + ML-DSA-65; FIPS 203/204/205 | Founder-Reported (publisher: Hanzo) | Blocked by missing reproducibility | Independent NIST KAT validation / third-party crypto review |
| B3 | 50 machine-checked Lean 4 proofs (ML-DSA EU-CMA, ML-KEM IND-CCA2, consensus safety/liveness) | Founder-Reported (publisher: Hanzo) | Blocked by missing reproducibility | Independent reproduction of the proof set |
| B4 | ZAP: 11.5M tx/s zero-copy PQ transport | Founder-Reported (publisher: Hanzo) | Blocked by missing reproducibility | Reproducible microbenchmark with methodology + hardware |
| B5 | FHE / CKKS confidential computation over ciphertext | Founder-Reported (publisher: Hanzo) | Evidence reviewed but insufficient | Independent evaluation on stated workloads |
| B6 | Positioning is deployment/control, not model supremacy; "not a claim our model is smarter than Claude" | Demonstrated (publisher: Hanzo — direct quote) | Not yet evaluated | Usable as positioning; note it *constrains* A1–A3 |

---

## C. Regulated capital-markets modernization case study

Provenance: **Hanzo Compendium** one-pager + "hanzo.ai vs claude.ai" case study (client anonymized; SOC 2; FINRA/SEC-approved) — **Hanzo-Published**. Also referenced with differing numbers in the ZK transcript. Independent verification: **No** for all. Not independently verified merely for appearing in a technical paper.

| # | Figure (Compendium account) | Evidence status | Unverified sub-status | Required artifact |
|---|---|---|---|---|
| C1 | 334 repositories | Founder-Reported (Hanzo, client's own audit) | Blocked by permission | Client authorization to cite; audit workpapers |
| C2 | 31,058 total commits; 15,294 agentic commits | Founder-Reported (Hanzo) | Blocked by permission | Same; transcript's "15,000" differs — contradiction logged |
| C3 | 114M raw git-log lines; $0.0006/line; 81-day window | Founder-Reported (Hanzo) | Blocked by permission | Same; transcript "230–250M LoC" differs — contradiction logged |
| C4 | 200+ microservices (57 core) → 3 binaries | Founder-Reported (Hanzo) | Blocked by permission | Client authorization; architecture before/after |
| C5 | ~$35K/mo → ~$3.5K/mo (~90% cloud spend, ~$380K/yr) | Founder-Reported (Hanzo) | Blocked by permission | Billing records + client authorization. NOTE: this is **cloud-infrastructure** savings on one migration — NOT a general AI-inference guarantee (contrast A2) |
| C6 | 93 security findings closed; SOC 2 / FINRA/SEC production | Founder-Reported (Hanzo) | Blocked by permission | Client authorization; audit records |
| C7 | Permission to name / attribute the case study commercially | Unknown / Requires Verification (Independent verification: No) | **Blocked by permission** (OPEN-QUESTIONS D7) | Written client authorization |

---

## D. Engineering track record (verbal)

| # | Claim | Evidence status | Publisher | Unverified sub-status | Required artifact |
|---|---|---|---|---|---|
| D1 | 230–250M lines of code career; 30M to prod in 30 days | Founder-Reported | Zach Kelling / transcript | Evidence reviewed but insufficient (figures vary) | Reproducible metric definition + audit |
| D2 | FINRA-approved ATS stood up in 80–81 days | Founder-Reported | Zach Kelling + Hanzo (81-day window) | Blocked by permission | Client attestation; regulatory record |
| D3 | Scales to a billion users | Founder-Reported | Zach Kelling / transcript | Blocked by missing reproducibility | Load-test evidence with methodology — **BARRED as guarantee** |

## E. Platform readiness (verbal)

| # | Claim | Evidence status | Publisher | Unverified sub-status | Required artifact |
|---|---|---|---|---|---|
| E1 | Hanzo Cloud live, stable, self-service-ready | Founder-Reported | Zach Kelling / transcript | Evidence requested | QA sign-off; uptime/SLO evidence |
| E2 | CLI (`curl hanzo.sh`) production-ready; GitC/hosting/DNS/domains functional | Founder-Reported | Zach Kelling / transcript (~00:09–00:11) | Evidence requested | Working-path verification |
| E3 | Automated billing / self-serve onboarding ready | Unknown/Requires Verification | Zach Kelling / transcript | Not yet evaluated | System verification |
| E4 | 400+ models integrated w/ auto-onboarding; all modalities | Founder-Reported | Zach Kelling / transcript (~00:08) | Evidence requested | Inventory + verification |

## F. Legal / IP (verbal)

| # | Claim | Evidence status | Publisher | Unverified sub-status | Required artifact |
|---|---|---|---|---|---|
| F1 | Ownership/control of rollup fraud-proof patent; ~300 patents | Founder-Reported | Zach Kelling / transcript (~00:22–00:25) | Evidence reviewed but insufficient | Patent assignment records; counsel review — **BARRED; legal review required** |
| F2 | Threshold ML-DSA NIST package authorship | Founder-Reported | Zach Kelling / transcript (~00:26) | Roadmap only | NIST submission record |

## G. Commercial (verbal / promotional)

| # | Claim | Evidence status | Publisher | Unverified sub-status | Required artifact |
|---|---|---|---|---|---|
| G1 | Existing paying customers using the platform now | Founder-Reported | Zach Kelling / transcript (~00:09) | Blocked by permission | Reference-able customer records (with permission) |
| G2 | Republic campaign can raise $5M (needs 5 months runway first) | Founder-Reported | Zach Kelling / transcript (~00:20) | Not yet evaluated | Platform/campaign confirmation |
| G3 | Businesses pay $3,000–$10,000 per AI-agent build (+ retainers) | Unknown/Requires Verification | AI Revolution X — "7 AI Agents" report / promotional | Evidence reviewed but insufficient | Independent market-pricing study. **Promotional assertion, not verified market data** |

---

## Status summary

- **Verified:** none yet — correct at this stage. AMA sells the *diagnostic*, not the claims.
- **Highest-value moves toward Verified:** the Enso evidence package (A2–A5; sub-status *Evidence requested / Blocked by missing reproducibility*; owner Zach, DR-8) and the case study (C-series; sub-status *Blocked by permission*; DR-7).
- **Provenance reminder:** "Hanzo-Published" (Compendium) is recorded in the publisher/provenance field only. It never sets or raises evidence status, and independent verification remains "No" until an independent artifact exists.
