# Agent Consent Evidence Receipt Field Guide

This repo accompanies the Substack post:

https://ankitkumar3514.substack.com/p/agent-consent-evidence-receipt

It provides a small, reusable starter kit for producing an agent consent and evidence receipt: a compact record of what an agent was authorized to do, which sources it used, what it changed, and what still needs human review.

## What A Human Can Use

- Start with `checklists/receipt-readiness-checklist.md` before shipping an agent workflow.
- Use `templates/agent-consent-evidence-receipt.example.json` as a model receipt.
- Adapt `schemas/agent-consent-evidence-receipt.schema.json` for internal validation.
- Read `docs/receipt-taxonomy.md` to distinguish traces, logs, receipts, and audit archives.

## What An Agent Can Do

An agent can read `AGENTS.md`, inspect workflow notes or run logs, and produce a receipt that conforms to the schema. The agent should preserve uncertainty, link evidence, and flag missing consent or verification fields instead of inventing them.

## Where To Start

1. Read the Substack post.
2. Open the readiness checklist.
3. Copy the example JSON.
4. Replace example values with one real workflow.
5. Validate against the schema.

## Intentionally Excluded

- No private logs, cookies, tokens, or Substack draft data.
- No raw traces from a live product.
- No claim that this schema is a compliance standard.
- No vendor-specific dependency.

## Files

- `AGENTS.md`: instructions for coding agents using this repo.
- `agent/manifest.json`: machine-readable navigation.
- `schemas/agent-consent-evidence-receipt.schema.json`: starter JSON schema.
- `templates/agent-consent-evidence-receipt.example.json`: example receipt.
- `checklists/receipt-readiness-checklist.md`: practical review checklist.
- `docs/receipt-taxonomy.md`: short taxonomy.
- `sources.md`: source links used by the article.
