# Organizational Positioning

How the entities in the ecosystem relate, who does what, and how AMA positions the whole to a buyer. This document is descriptive positioning; all performance claims remain governed by `claim-governance.md` and `evidence-registry.md`.

> Canonical spellings: Hanzo, Enso, Lux, AMA Solutions, Zach Kelling, MAIM.

## 1. The five roles

| Entity | Role | One-line responsibility |
|---|---|---|
| **AMA Solutions** | Capability architect / commercial layer | Client relationship, discovery, engagement design, productization, delivery management; decides which problem to solve, what the client must see to trust it, and when engineering involvement is justified. |
| **Hanzo** | Sovereign operating system / technical foundation | AI, agents, engineering, cloud, security, and operational infrastructure. |
| **Enso** | Intelligence-selection / routing / consensus layer | Evaluates a task on cost, capability, and quality; routes to (and can combine) the best model(s); is **not** "another model." |
| **Lux** | Coordination / provenance / settlement | Network coordination, blockchain, asset provenance, settlement. Kept in the background during the initial go-to-market. |
| **Client** | Domain owner | Domain expertise, proprietary information, operating authority, and — always — legal and financial accountability. |

AMA's mandate is an **executive function**: not reselling Hanzo, but deciding which bounded problem to solve, what proof the client needs, and when direct engineering is economically justified. (Source: Sovereign OS Blueprint, "Ecosystem Responsibilities & The Role of the Capability Architect"; AMA strategic analysis.)

## 2. What we are selling

We are **not** commercializing 700 disconnected repositories. We are commercializing **one vertically integrated system whose repositories are its component inventory** (Sovereign OS Blueprint, "The Central Realization"). But customers do not buy architectures — they buy solutions to immediate problems. So AMA packages the vertical as an *integrated institution-to-infrastructure stack* and sells entry through a single bounded outcome.

The competitive frame: most competitors own one slice — automation agencies own the workflow, model labs own intelligence, cloud providers own compute, cyber firms own security, blockchains own settlement. The Hanzo ecosystem's positioning is that it addresses the **entire chain, from institution to infrastructure**. This is a positioning statement about scope of coverage; specific capability claims within it carry their own evidence status in `evidence-registry.md`.

## 3. The three market tiers

From the Sovereign OS Blueprint ("Precision Positioning Across Three Market Tiers"):

- **Level 1 — Public / Simple.** Hanzo gives an organization everything needed to build and operate an AI-powered company in one sovereign environment. Entry point for rabbits and self-serve.
- **Level 2 — Enterprise.** An integrated AI control plane and sovereign cloud combining model routing, engineering agents, organizational memory, and post-quantum security. Elephant territory.
- **Level 3 — Government & Critical Infrastructure.** Self-hostable, post-quantum, audit-ready AI for disconnected environments, with no dependence on closed AI providers. Whale territory; Lux and the full security stack come forward here.

These tiers map to the rabbit/elephant/whale commercial motion in `commercialization-doctrine-v1.md`.

## 4. Positioning Enso: the intelligent transmission

The most effective, defensible way to explain Enso to a non-technical buyer is the **transmission analogy** (from the pressure-test material and the Sovereign OS explainer):

> Enso is not a brand-new engine we claim is faster than a Ferrari. Enso is a highly advanced automated transmission. You already own the engines — your API keys for the frontier models, your cloud. Enso sits in the middle and shifts gears between them automatically, based on real-time conditions, so you never burn premium fuel on a task that doesn't need it.

Key positioning discipline:
- Enso commoditizes the frontier-model race rather than competing in it. It treats frontier models as continuously-changing components while preserving the option to use owned Zen/Tinker models.
- Enso gives the operator **control over the cost-versus-quality tradeoff**, presented as a single unified model experience (evaluate → invoke multiple models → judge → synthesize).
- What AMA may **not** say: that Enso is the number-one AI, guarantees a savings percentage, or routes in microseconds — all barred pending evidence (`evidence-registry.md` A1–A5). AMA sells the *transmission and the control it gives*, not a benchmark claim.

## 5. Positioning against the obvious objection ("why not AWS Cost Explorer / Datadog?")

The defensible distinction: passive observability tools *report* that you overspent; Enso is *active* — it routes traffic in real time and provides the underlying sovereign compute. Cost Explorer is a mechanic telling you the engine is inefficient; Hanzo is the mechanic installing an intelligent transmission that fixes the inefficiency while you drive. This is a positioning contrast, not a performance guarantee; the reproducible proof that Enso actually reduces a given client's spend is exactly what the paid diagnostic establishes, per client.

## 6. Positioning sovereignty honestly

Hanzo's durable moat is **deployment and control**, and AMA states it exactly as the Compendium does — as a claim about *where and how you run AI*, not about model supremacy. Defensible, provenance-tagged positioning points (all Hanzo-Published; see `evidence-registry.md` §B):
- Owned, inspectable model weights (Zen family) versus non-transferable closed weights.
- Self-hostable, edge, or air-gapped deployment a metered cloud cannot offer by construction.
- Post-quantum and FHE-native security; auditability.

AMA must **not** assert blanket "zero data egress" or "no customer data influences shared weights" as universal properties — each is deployment-specific and, for Enso specifically, unresolved pending Zach's data-governance statement (OPEN-QUESTIONS D6).

## 7. Where the whale story lives — and stays, for now

Post-quantum cryptography (ML-KEM-768 + ML-DSA-65; FIPS 203/204/205), FHE, the 50 Lean proofs, ZAP, Lux settlement, and the regulated-market case study are the **expansion and whale narrative**. They are real positioning assets at Level 3, carried as Hanzo-Published pending independent evidence. They are deliberately *not* the first sales explanation (doctrine §3), and Lux stays in the background until a stable base is established. The regulated case-study figures may be cited only after client permission (DR-7).

## 8. Relationship between Major and Zach (positioning of the humans)

Major Dream Williams owns relationships, commercial discovery, productization, storytelling, and closing qualified engagements. Zach Kelling is the primary technical founder and frontier-systems architect. Positioning implication for buyers: AMA is the accountable commercial counterpart; deep engineering is engaged only when an opportunity is qualified and proprietary capability materially affects the sale (see `zach-escalation-policy.md` (forthcoming, PR #3)). This protects the scarcest resource and keeps the buyer's primary relationship with AMA.
