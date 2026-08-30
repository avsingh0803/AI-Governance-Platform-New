# AI Governance Platform

An AI governance, risk, and compliance platform — use case registration, AI-assisted impact and risk assessment, dynamic governance committee approval, evidence-gated lifecycle progression, compliance framework tracking, guardrails, and continuous monitoring.

## What this is

`ai-governance-platform.html` is a single-file, self-contained web application (React, runs entirely in the browser — open it directly, no build step or server required). It calls the Anthropic API at runtime for AI-assisted assessments; all other data is stored in browser local storage.

**Read this before treating it as more than a demonstrator.** This is a governance blueprint and working prototype, not a production system:

- The governance workflow — use case lifecycle, dynamic committee routing, evidence gates, approvals, comments — is real and functional.
- Discovery, Agentic AI, and Guardian Agents currently use seed/simulated data. Nothing in the app connects to real external systems, scans a live environment, or enforces anything at runtime yet.
- There is no backend: no server-side auth, no persistent database, no real integrations. RBAC and audit logging are UI-level only.
- See `AI_Governance_Platform_Feature_Guide.pptx` for a feature-by-feature breakdown of what's real today versus what production would require.

## Contents

| File | Description |
|---|---|
| `ai-governance-platform.html` | The platform itself — open in any modern browser |
| `AI_Governance_Framework.docx` | Governance framework: principles, operating model, lifecycle, technical controls, regulatory mapping |
| `AI_Governance_Platform_Feature_Guide.pptx` | Feature-by-feature guide: how each capability works, and its current maturity |
| `Technical_Architecture_Document.docx` | Technical architecture |
| `AI_Governance_Developer_Production_Readiness_Guide.docx` | What's needed to take this from prototype to production |
| `ARCHITECTURE_AND_SECURITY_REVIEW.md` | Architecture and security review notes |

## Getting started

Open `ai-governance-platform.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/ai-governance-platform.html
```
