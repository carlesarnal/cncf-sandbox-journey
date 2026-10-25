# Presentation guide

Preparing a CNCF Sandbox Application: A Maintainer's View from Apicurio Registry

## Audience and central claim

In January 2024, I closed Apicurio Registry’s earlier Sandbox application while branding questions were resolved and the project explored its relationship with xRegistry. The public comment is useful because it records a decision, not a retrospective invented to make acceptance look inevitable.

## 30-minute run of show

### 0:00 — The documented 2024 deferral

In January 2024, I closed Apicurio Registry’s earlier Sandbox application while branding questions were resolved and the project explored its relationship with xRegistry. The public comment is useful because it records a decision, not a retrospective invented to make acceptance look inevitable.

Open application #72 at the January 2024 deferral comment.

### 4:00 — Define project scope and ecosystem fit

The renewed application identifies repository scope and describes the consolidation of Studio functionality. It distinguishes a runtime implementation from a neighboring specification and describes alignment work. These are application statements: a reader should not turn intended conformance or ecosystem positioning into independently verified technical guarantees.

Compare the repository scope and xRegistry discussion in application #461.

### 9:00 — Separate the vote from onboarding

The March 2026 vote passed. A later comment explicitly required the contribution agreement before onboarding, and issue #495 lists project and foundation tasks. Keeping those stages distinct helps maintainers assign work realistically. The public record does not establish that I personally completed every task or that a particular code change caused acceptance.

Show the passed vote, the contribution-agreement requirement and onboarding issue #495.

### 15:00 — Turn claims into an evidence worksheet

For each application question, write the claim, a public reference, what it actually proves, the remaining gap and an owner. Recheck current requirements before applying. The durable takeaway is evidence organization and stewardship, rather than a permanent checklist of foundation rules or a promise that membership creates a contributor community.

Fill one row of worksheet.md with a claim, source, unresolved gap and owner.

### 21:00 — Give each gap an owner

Summarize the decision the example supports and the assumptions behind it.

Ask which project responsibility continues after the acceptance milestone.

### 26:00 — Questions and buffer

Ask what the demonstration establishes and what it leaves open. Do not add another feature if time is short.

## Setup and fallback

```sh
Read worksheet.md alongside the linked public application records
```

Public application #72, renewed application #461 and onboarding #495 inspected. No software execution needed. Historical decisions are evidence; no causal claim about acceptance or contributor growth.

Prebuild/download dependencies. Keep a recording of an actual successful run; if unavailable, use the documented walkthrough and say it is not live execution. Never substitute fabricated success output.

## Questions to prepare

- What is the simplest alternative?
- Which failure was actually exercised?
- Which guarantee belongs to the application rather than the infrastructure?
- Which result changes with versions or workload?

## 25-minute adaptation

Use one central trace, shorten setup and reserve three minutes for questions. Move the secondary implementation example to backup.
