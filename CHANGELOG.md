# Changelog

All notable changes to the AMA Capability Commercialization System are recorded here. Format loosely follows Keep a Changelog. This repository is documentation-first; entries describe knowledge and governance changes, not software releases.

## [Unreleased] — branch `docs/governance-foundation-v1`

### Added — Governance foundation (PR #1)
- `README.md` — repository purpose, map, source-authority order, and claim-handling summary.
- `docs/claim-governance.md` — evidence status (five canonical values: Verified / Demonstrated / Founder-Reported / Roadmap / Unknown) kept separate from publisher/provenance (e.g. Hanzo-Published) and a per-claim unverified sub-status; banned-claim list; strongest-defensible-version rule.
- `docs/evidence-registry.md` — every material Hanzo/Enso/Lux claim with five orthogonal fields (evidence status, publisher/provenance, independent verification, unverified sub-status, required artifact). No claim classified Verified at this stage (expected).
- `research/source-manifest.md` — all sources with authority tier and permitted/prohibited uses, including the Hanzo Compendium (tier 3, company-published) and the "7 AI Agents" report (low-authority market research).
- `decisions/decision-register.md` — Current Decisions 1–13, twelve preserved contradictions, and new decisions DR-1…DR-12.
- `OPEN-QUESTIONS.md` — unresolved questions for Major and Zach.
- `CHANGELOG.md` — this file.

### Notes
- Compendium reviewed and integrated; recorded in the publisher/provenance field as Hanzo-Published (not an evidence status). Company publication never raises evidence status; no Compendium claim auto-upgraded to Verified.
- Case-study figures reconciled to the Compendium account and recorded Hanzo-Published / Founder-Reported pending evidence; commercial-use permission remains open (DR-7).
- Scope limited to the governance foundation. Doctrine, positioning, offer portfolio, ICP framework, cohorts, escalation policy, and the 90-day validation plan follow in a later PR after their dependent decisions are resolved.
- No changes to `AMA-Rabbit-Delivery-System` in this PR.
