# ICP Framework

The ideal customer profiles AMA targets, the scoring rubric that qualifies a prospect, and the disqualifiers that protect focus. Governed by `commercialization-doctrine-v1.md`. Uses the resolved qualification floor (DR-4: $20,000/month combined AI + cloud spend).

> Canonical spellings: Hanzo, Enso, Lux, AMA Solutions, Zach Kelling, MAIM.

## 1. Ideal customer profiles

| ICP | Who | Size | Economic buyer | Champion | Primary offer |
|---|---|---|---|---|---|
| **ICP-1 — AI-native SaaS** | Mid-market software with heavy multi-model API + cloud spend | 50–500 employees | CFO | VP Eng / Head of AI | AI & Cloud Cost Diagnostic |
| **ICP-2 — Professional-services firm** | Law, accounting, consulting, advisory | 20–75 staff | Managing partner / founder | Same (buyer = champion) | Private Knowledge Vault |
| **ICP-3 — Family office / private advisory** | Family offices, PE, specialized funds | 10–75 staff | Principal / CIO | COO / chief of staff / CCO | Private Knowledge Vault / Governance Audit |
| **ICP-4 — Bloated growth company** | Series B/C tech with cloud + repo sprawl | 100–300 employees | CEO / board | CTO | Agentic Engineering Readiness Sprint (elephant) |
| **ICP-5 — Regulated fintech / digital-asset** | Regulated firms with sensitive data + audit burden | 20–300 employees | CTO / CISO / CFO | Head of platform / compliance | Governance Audit → Sprint → (whale later) |
| **ICP-6 — Channel partner (MSP / agency)** | IT MSPs and digital-transformation agencies reselling into their own client base | 10–150 staff | Founder / COO | Delivery lead | White-labeled Hanzo infrastructure |

Geographic priority: US and Canada first, then UK, UAE, Singapore, Australia; EU and other hubs secondary. Every campaign is segmented by geography, vertical, offer, triggering event, and buyer role — "global" is never permission for an unfocused list.

## 2. Triggering events (why they answer on a Tuesday)

- **ICP-1 — the "invoice shock":** a CFO opens the monthly bill and sees a frontier-model line item wildly out of proportion to the revenue the feature generates.
- **ICP-2 / ICP-3:** a painful, visible failure — a lost pitch because juniors couldn't retrieve precedent; a senior departure that walks institutional knowledge out the door.
- **ICP-4:** external pressure — a failed SOC 2, or a board mandate to cut engineering burn before the next raise.
- **ICP-5:** a rival's data breach, or a new compliance regime requiring immutable, auditable logs.
- **ICP-6:** margin pressure on bespoke delivery; wanting a sovereign backend they can white-label.

## 3. Qualification scorecard (0–100)

Score each prospect; the weights sum to 100.

| Dimension | Weight |
|---|---|
| Pain severity | 20 |
| Measurable financial impact | 15 |
| Urgency / triggering event | 15 |
| Offer fit | 15 |
| Budget capacity | 10 |
| Access to decision-maker | 10 |
| Technical readiness | 5 |
| Expansion potential | 5 |
| Proof availability | 5 |

**Tiers:** 80–100 → immediate personalized outreach · 65–79 → research and warm-up · 50–64 → nurture · below 50 → do not prioritize. A large company is not automatically qualified.

## 4. The qualification floor (DR-4, resolved: $20,000/month)

The standard ICP qualification floor is **$20,000/month in combined AI + cloud spend.** Below that, a 30–50% optimization may not cover a credible high-touch diagnostic fee. Rationale: $10,000 is often too small to support the diagnostic; $25,000 would unnecessarily restrict the early pipeline; $20,000 is the middle ground.

- **Below the floor:** organizations can still enter through **rabbit/self-serve** or **standardized assisted** offers — they are not turned away, just routed to a cohort whose economics fit (see `customer-cohort-definitions.md`).
- **Strategic exceptions** to the floor require **AMA approval**, justified by one of: expansion potential, proprietary-data value, channel leverage, or importance to the sovereign / critical-infrastructure mission.

The lead qualification question for the diagnostic: *"What is your current monthly spend on AI inference and cloud compute?"* If the answer is materially below $20,000 and no strategic exception applies, route rather than pursue high-touch.

## 5. Anti-ICP and disqualifiers

Deprioritize or decline prospects that:

- have negligible AI/cloud spend and no strategic-exception basis (can't sell a cost audit to someone with no costs);
- cannot provide baseline usage data (metadata, billing exports);
- are locked into large subsidized cloud-credit programs (they burn credits indiscriminately; efficiency doesn't matter yet);
- lack a real decision-maker or budget;
- want unpaid custom development, or expect guaranteed outcomes before discovery;
- want a **liability-free autonomous shell company** — disqualified on principle (human governance, Decision 10);
- expect production deployment without testing, observability, or security controls;
- seek unauthorized access, circumvention, or anything that fails KYC/KYB;
- demand Zach's involvement before commercial qualification.

## 6. Principal objections (per ICP) and honest responses

- **ICP-1 VP Eng — "we can't hand over API keys or raw prompts."** Correct — AMA ingests **metadata, not payloads**: read-only billing access plus a sample of inference-log metadata (token counts, endpoints, latency). No production code is touched.
- **ICP-2/3 partner — "too complex for my non-technical staff."** The deliverable is a simple, permissioned search experience mirroring the org chart, not a command line; success is measured against 100 firm-supplied benchmark questions.
- **ICP-4 CTO — "our architecture is too bespoke to audit."** The qualifying probe: are outsourced contractor costs exceeding internal engineering payroll? If so, the sprawl is exactly what the sprint addresses — but only as an elephant, after trust.
- **ICP-5 CCO — "is Hanzo training on our data?"** This is exactly the unresolved Enso data-governance question (D6). Until Zach's written statement exists, AMA does not promise anything here and does not sell the Enso pilot into regulated data.

Every objection response stays inside `claim-governance.md`: strongest defensible version, no barred claim, no guarantee before discovery.
