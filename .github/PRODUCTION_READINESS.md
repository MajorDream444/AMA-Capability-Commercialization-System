# Production Readiness Gate

Every product classified as a Rabbit, Elephant, or Whale must pass this gate before demo, sale, deployment, or handoff.

## Tests

- [ ] Changed behavior and critical journeys have automated coverage.
- [ ] Failure, retry, timeout, invalid-input, and authorization paths are covered where relevant.
- [ ] CI passes using synthetic or irreversibly anonymized data.

Evidence:

> Add commands, CI links, coverage, and exceptions.

## Observability

- [ ] Structured, privacy-safe logs and error capture exist.
- [ ] Health, latency, error rate, dependency signals, and alerts exist where relevant.
- [ ] Alerts and rollback/containment have named owners.
- [ ] No secrets, prompt contents, or unnecessary PII reach telemetry.

Evidence:

> Add dashboards, alerts, sanitized sample events, owner, and rollback path.

## Data and PII

- [ ] Inputs, purpose, storage, processors, outputs, retention, and deletion are mapped.
- [ ] Collection is minimized and sensitive fields are encrypted.
- [ ] Access is least-privilege and auditable.
- [ ] PII is redacted from prompts, logs, traces, analytics, fixtures, screenshots, and support artifacts.
- [ ] Model providers and other subprocessors are approved and documented.
- [ ] Consent, export, correction, deletion, and incident obligations are handled where applicable.

Data flow:

> Source → processing → storage → subprocessors → output → retention/deletion.

## Decision

- [ ] PASS
- [ ] EXCEPTION — owner, risk acceptance, compensating control, and expiry recorded
- [ ] BLOCKED — do not commercialize or deploy

Codex, Claude Code, and other coding agents must treat this gate as part of every task and may not claim completion without evidence.


## 2026-11-19 Hanzo README badge — scoped evidence

Scope: README-only external badge and repository-specific editor link; no application code or deployment configuration changed.
- Tests: badge Markdown and encoded repository target checked; existing README preserved. Runtime, failure-path and E2E tests are not applicable because executable behavior is unchanged.
- Observability: Git commit records this documentation change. New production logs, metrics and alerts are not applicable; no production path added.
- Data/PII: public badge SVG is served through GitHub image handling. Clicking the editor link sends the public repository URL to Hanzo; no credentials, customer data, API calls, authorization changes or automated import added. Any later workspace creation requires the visitor's action and Hanzo account policies.
- Decision: documentation-only update; this does not certify or change product production readiness, deployment or commercial approval.
