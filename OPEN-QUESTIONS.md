# Open Questions

Unresolved questions requiring Major or Zach. Mirrors the new decisions in `decisions/decision-register.md`. Nothing here should be silently resolved in documentation.

## Requiring Major

- **D1 — Customer mix.** Confirm the canonical first-1,000 mix. Proposed: 40 high-touch / 160 assisted / 300 channel / 500 self-serve. (Podcasts propose different splits.)
- **D2 — Agentic Company Launch.** Keep it excluded from the active portfolio (Decision 11) despite the Blueprint promoting it as one of the "Three Undeniable Entry Offers"?
- **D3 — Pricing.** Confirm the two-contract structure as working hypothesis: Phase A ≈ $12,000–$20,000; Phase B ≈ $8,000–$15,000. (Do not merge into a single band.)
- **D4 — Qualification floor.** Set the minimum monthly AI + cloud spend to qualify for the diagnostic: $10K, $20K, or $25K+/mo.
- **D5 — Phase A success signal.** Confirm Phase A has no minimum-savings success threshold. Approve an internal "identified savings ≥ X%" *qualification signal* only if you want one — it must never become a success gate or external guarantee.
- **D7 — Case-study naming.** May the regulated capital-markets modernization case study be named or attributed commercially, given (a) the Compendium keeps it anonymized and (b) the verbal account describes the engagement ending badly? Client permission likely required. (Joint with Zach.)
- **D11 — Docs-only PR gate.** For documentation-only PRs, may Tests and Observability be marked "N/A — documentation" with rationale while the Data/PII checks are still completed?

## Requiring Zach

- **D6 — Enso data governance (blocks Phase B sale).** Does customer usage influence shared Enso model weights? Provide, in writing: opt-in/opt-out controls, retention, deletion, tenant isolation, and prohibited-data handling. This resolves the direct contradiction between "Enso retrains daily on anonymized usage" and the sovereignty promise.
- **D8 — Enso evidence package.** What reproducible benchmark artifacts can you produce now (methodology, model configs, reproducibility instructions)? This is the path to moving Enso performance claims from Founder-Reported toward Verified.
- **D9 — Phase A mechanics.** Confirm Phase A is deliverable with metadata only (billing exports + inference-log metadata, no prompt payloads), and confirm whether the shadow/replay routing simulation exists as tooling or must be run manually.

## Requiring Major (operational / repo)

- **D10 — Repo write access.** Both repositories exist and are readable. Cowork's environment currently has **no authenticated write access** (public read succeeds; push fails — no credentials, no `gh`, no token). To let Cowork create the branch and PR directly, provide an authenticated path (e.g., a GitHub connector with write scope, or a token/credential method). Until then, PR #1 is delivered as an applyable patch/bundle. This is an **authentication** limitation, not a repository-existence issue.

## Open contradictions (see decision register Part 2)

C-01 mix · C-02 agentic launch placement · C-03 savings figures · C-04 retraining vs sovereignty · C-05 model-quality claims · C-06 code volume · C-07 commit counts · C-08 diagnostic pricing · C-09 company-creation pricing · C-10 timeline · C-11 qualification floor · C-12 case-study identity.
