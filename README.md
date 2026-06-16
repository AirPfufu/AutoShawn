# Self-Funding Agent Ops

This repository contains the operating system for a self-funding agent experiment.

The current commercial route is a B2B lead research and personalized outreach preparation service. The agent sources public opportunities, scores leads, drafts outreach, and runs weekly reviews. The user approves externally visible actions, account creation, payments, and any workflow that requires legal identity or verification.

## Contents

- `docs/superpowers/specs/`: design decisions and operating constraints.
- `docs/superpowers/plans/`: implementation and execution plans.
- `operations/self-funding-agent/`: service package, lead scorecard, channel keywords, outreach templates, pipeline, and weekly review template.

## Rules

- Do not commit passwords, cookies, session exports, recovery codes, or API keys.
- Prefer HTTP/API workflows over WebSocket integrations unless real-time behavior is required.
- Do not automate spam, impersonation, fake testimonials, or unsupported claims.
- Pause for user approval when KYC, phone verification, captcha, platform account creation, public outreach, contracts, or payment setup is required.

