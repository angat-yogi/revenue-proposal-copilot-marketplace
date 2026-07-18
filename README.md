# Revenue Proposal Copilot

Revenue Proposal Copilot is a Codex plugin that helps consultants, agencies, freelancers, and technical service teams turn discovery notes into scoped, priced proposals and SOW drafts.

## Who It Is For

- Consultants who need faster first drafts after sales calls.
- Agencies packaging custom work into clear tiers.
- Technical leads creating implementation proposals from loose requirements.
- Freelancers who want stronger assumptions, exclusions, and scope boundaries.

## What You Get

- Proposal drafting workflow for Codex.
- Three-tier pricing structure guidance.
- Scope, assumptions, exclusions, milestones, and acceptance criteria.
- Internal risk review before sending a proposal.
- Offer worksheet template.

## Install From This Marketplace

Clone this repository, add this repository root as a Codex plugin marketplace, then install the plugin:

```bash
git clone https://github.com/angat-yogi/revenue-proposal-copilot-marketplace.git
cd revenue-proposal-copilot-marketplace
codex plugin marketplace add "$(pwd)"
codex plugin add revenue-proposal-copilot@revenue-proposal-copilot
```

## Try It

After installing, start a new Codex thread and try:

```text
Turn these discovery notes into a priced proposal:

Client: Acme Dental Group
Goal: automate patient intake and reduce front-desk manual entry
Need: online forms, CRM sync, status dashboard, staff training
Timeline: wants launch in 6 weeks
Budget: says they can approve under $25k without board review
Risk: HIPAA concerns, current CRM API is unclear
```

## Monetization

This repository is structured for distribution, but payment handling is separate. Practical launch options:

- Sell access through a Gumroad, Lemon Squeezy, Stripe Payment Link, or private GitHub access workflow.
- Offer paid setup packages for teams that want proposal templates customized to their niche.
- Keep this public repo as the demo channel and move premium templates into a private repo.

Suggested early pricing:

- Beta license: USD 49 to USD 99.
- Annual seat: USD 149 to USD 299.
- Custom setup: USD 300 to USD 1,000.

## Repository Layout

```text
.agents/plugins/marketplace.json
plugins/revenue-proposal-copilot/
examples/
```

## Status

This is an MVP. Review the legal, privacy, and payment terms before selling it commercially.
