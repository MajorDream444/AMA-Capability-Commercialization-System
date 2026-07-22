# Claim Governance

This document defines how AMA Solutions classifies, labels, and uses every material technical or commercial claim about Hanzo, Enso, and Lux. It is the spine of the commercialization system: no positioning, offer, proposal, or marketing asset may state a claim that has not cleared these rules.

## 1. Why this exists

The strongest go-to-market risk is not weak technology — it is over-claiming. A single unsupported superlative ("the number-one AI in the world," "guaranteed 90% savings") will end an enterprise procurement conversation and can breach a contract. AMA's credibility as a **capability architect** depends on saying only what can be defended.

## 2. Evidence status vs. provenance (keep them separate)

A claim has **two independent attributes**. Never collapse them.

### 2a. Evidence status — exactly one of five canonical values

| Evidence status | Meaning | Marketable? |
|---|---|---|
| **Verified** | Supported by reproducible, independent evidence (third-party audit, reproducible benchmark with published methodology, or client-attested record AMA can show). | Yes, within the exact scope of the evidence. |
| **Demonstrated** | Shown working in a live system or dashboard, not independently reproduced or audited. | Only as a live demo, explicitly labeled — never as proof. |
| **Founder-Reported** | Stated by Zach Kelling or another founder, not yet independently validated. | No. |
| **Roadmap** | Planned, experimental, or incomplete. | No. |
| **Unknown / Requires Verification** | Encountered but unconfirmed. | No. |

### 2b. Publisher / provenance — who asserts it, and where

Provenance is recorded separately (e.g., "Hanzo Compendium / **Hanzo-Published**," "Zach Kelling / meeting transcript," "AI Revolution X / promotional"). **`Hanzo-Published` is a provenance label, not an evidence status.** A claim appearing in the company-published Compendium is *Hanzo-Published in provenance* and typically *Founder-Reported in evidence status with Independent verification = No*. Company publication never raises evidence status.

### 2c. Sub-status for anything not Verified

"Not Verified" is never one undifferentiated bucket. Every non-Verified claim also carries exactly one sub-status: **Not yet evaluated · Evidence requested · Evidence reviewed but insufficient · Blocked by permission · Blocked by missing reproducibility · Roadmap only.**

### Non-negotiable rules

1. **Never raise evidence status without new independent evidence.** Appearing in a company-published paper does **not** make a claim Verified — that is provenance, not verification.
2. **Founder-Reported claims are never converted to Verified** by restatement, confidence, or repetition.
3. **Preserve all five fields** in `evidence-registry.md`: evidence status, publisher/provenance, independent verification (Yes/No), unverified sub-status, and required artifact.
4. **Company-published ≠ independent.** The Compendium is authoritative for Hanzo's *official positioning*; it does not independently verify performance claims.

## 3. Claims that may never be marketed

Regardless of internal belief, the following MUST NOT appear in any AMA outbound material, proposal, deck, or pilot agreement until and unless they reach **Verified** with scoped evidence:

- "Number-one AI in the world" / benchmark supremacy / "best on every benchmark."
- Guaranteed savings percentages (e.g., "50–90% savings"), including as a promise of pilot outcome.
- Guaranteed performance improvements.
- Unsupported benchmark leadership of any kind.
- "Fully autonomous companies" or legally autonomous AI entities (see `zach-escalation-policy.md` and the human-governance rule).
- Absolute privacy or "zero data egress" **without deployment-specific proof** for the specific architecture sold.

## 4. Use the strongest *defensible* version

Replace superlatives with a scoped, testable statement.

> **Do not write:** "Enso will reduce your AI expenditure by 75–90%."
>
> **Write:** "AMA establishes your current cost, latency, and quality baseline, identifies and categorizes cost drivers, and — only where justified — tests whether Enso can reduce expenditure without degrading agreed performance. A legitimate result is that no economically meaningful pilot is warranted."

## 5. Dashboards and demos

A live command-center dashboard, cost slider, or routing demo is **Demonstrated**, not Verified. It is valuable to *show*, but it is not reproducible independent evidence and may not be cited as proof in a proposal or pilot agreement.

## 6. Sovereignty and data claims

Do not claim tenant isolation, "no customer data influences shared model weights," or "zero data leaves the environment" as a blanket property. Each is deployment-specific and must be backed by the architecture actually sold and documented in the relevant delivery module's `security-and-access.md`. The tension between Enso's reported continuous retraining and the sovereignty promise is an **open, unresolved** governance question (see `OPEN-QUESTIONS.md`, D6) and blocks any Enso-pilot sale until resolved in writing by Zach.

## 7. Applying this document

- When drafting any external asset, cross-check each factual claim against `evidence-registry.md`.
- If a claim is not in the registry, it may not be used until it is logged and classified.
- Preserve disagreements: if sources conflict, record both in `decisions/decision-register.md` rather than silently choosing one.
