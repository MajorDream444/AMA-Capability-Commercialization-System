# Customer Cohort Definitions

How AMA reaches its first 1,000 paying customers without collapsing under a bespoke-delivery support burden. Uses the resolved mix (DR-1). Governed by `commercialization-doctrine-v1.md`.

> Canonical spellings: Hanzo, Enso, Lux, AMA Solutions, Zach Kelling, MAIM.

## 1. The scale architecture (DR-1, resolved)

The first 1,000 customers are a **blended architecture**, not a single sales motion — and explicitly **a scale architecture, not a promise to acquire 1,000 customers within 90 days** (Decision 12).

| Cohort | Count | Share | Acquisition motion | Delivery / support model |
|---|---|---:|---|---|
| **High-touch AMA** | 40 | 4% | Direct, founder-informed, qualified above the $20K floor | Bespoke diagnostics, vaults, and elephant engagements; core team involved |
| **Standardized assisted** | 160 | 16% | Outbound + inbound into productized offers | Delivered from an ironclad playbook by junior AMA architects; zero custom Hanzo code |
| **Channel / partner-delivered** | 300 | 30% | Recruit MSPs / agencies who own the end-client relationship | Partner delivers; AMA manages ~10–15 B2B partner relationships, not 300 end-clients |
| **Product-led self-serve** | 500 | 50% | No sales call; CLI, app builder, self-serve API | Fully self-service; frictionless billing, docs, onboarding — no senior-engineer tickets |
| **Total** | **1,000** | 100% | Blended | — |

## 2. Why this mix

- **The 40 high-touch fund and prove.** They provide high-margin upfront cash flow and the heavyweight case studies (e.g., the regulated-market modernization, citable only after DR-7 permission) that make the rest of the market believe the system works at scale.
- **The 160 assisted keep the lights on** at moderate margin and low technical friction — the "off-the-rack suits" built once and delivered many times from the playbook.
- **The 300 channel give leverage.** A local MSP already has trusted relationships with dozens of small firms; Hanzo silently powers the sovereign backend. AMA scales end-customers without scaling its own sales headcount.
- **The 500 self-serve are the only way to reach the volume** — pure product-led growth for developers, indie hackers, and technical 0-to-1 founders spending modest amounts on compute and Enso routing.

The bespoke-only alternative fails mathematically (doctrine §5): 1,000 × $50K direct sales would bankrupt the team on headcount long before it reached the number.

## 3. The existential dependency: frictionless self-serve

For the 500 self-serve and 300 channel end-users to be *profitable*, the platform must be genuinely frictionless. The failure mode is precise: a $200/month self-serve user hits a routing bug, files a ticket, and a senior Hanzo engineer earning six figures spends the day fixing it — the account's entire annual margin is gone in one afternoon. "We bleed to death from a thousand paper cuts."

Non-negotiable prerequisites before scaling cohorts 3 and 4:
- CLI, basic cloud/deploy workflows, and developer docs are self-service and stable;
- automated billing and onboarding require no human Tier-1 support;
- the Enso router and basic Git/app deployments run without Zach's involvement.

Until these hold, cohorts 3 and 4 are capped. This ties directly to the agency-trap doctrine (§4) and to the 90-day validation plan's day-1–30 lockdown.

## 4. Cohort routing rules

- **At or above the $20K/mo floor, strong pain, decision-maker access** → high-touch (cohort 1).
- **Productizable need, standard shape** → standardized assisted (cohort 2).
- **Reached via an MSP/agency, or small firms clustered under one partner** → channel (cohort 3).
- **Below the floor, self-directed, technical** → self-serve (cohort 4).
- **Below the floor but strategically valuable** (expansion, proprietary data, channel leverage, sovereign-mission relevance) → high-touch **only via an AMA-approved strategic exception** (see `icp-framework.md` §4).

No prospect is turned away for being below the floor; they are routed to the cohort whose unit economics fit.

## 5. Per-cohort support economics (guardrail)

| Cohort | Support intensity | Margin profile | Guardrail |
|---|---|---|---|
| High-touch | High | High upfront | Reserve for qualified, funded, expandable accounts |
| Assisted | Medium | Moderate | Must run from the playbook; escalate to core team only per `zach-escalation-policy.md` |
| Channel | Low (via partner) | Recurring, leveraged | AMA supports the partner, not the partner's clients |
| Self-serve | Near-zero human | Volume | Any human ticket that recurs is a product bug to fix, not a support process to staff |

The mix is the current resolved working architecture; it is revisited only with evidence, and any change is recorded in the decision register.
