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

## Free And Open Source

Revenue Proposal Copilot is free to use under the MIT License.

You can still offer paid services around it, such as custom proposal templates, team setup, training, or workflow consulting, but the plugin itself is free.

## Usage Analytics

Because this plugin is a local Codex plugin with no hosted backend, it does not phone home or track individual installs.

What you can see from GitHub:

- Repository traffic: views and unique visitors.
- Clone counts: how many times the repo was cloned.
- Stars, forks, issues, and pull requests.
- Release asset download counts, if you attach packaged release files.

Where to check:

- GitHub repo page: `Insights` -> `Traffic`.
- GitHub release page: download counts on release assets.

If you need exact install or active-use analytics later, add an optional hosted service with clear user consent. Do not add hidden telemetry.

## Repository Layout

```text
.agents/plugins/marketplace.json
plugins/revenue-proposal-copilot/
examples/
```

## Status

This is an MVP. Review the legal, privacy, and payment terms before selling it commercially.
