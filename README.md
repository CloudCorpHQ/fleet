# CloudCorp Fleet: Hosted Platform

**We run and secure the agents writing your code.**

This repo is the public home of the hosted CloudCorp fleet platform. The engines are already shipped as open source MCP tools. This is where the hosted layer lives: what it is, how pilots work, and where each fleet tool lives today.

## What the hosted layer is

One install, three agent lines, running continuously:

- **PR and Contribution Ops:** policy gating for agent-written pull requests, claim tracking, review triage, and contribution gates
- **Agent-Stack Security:** continuous audit of MCP servers, hooks, GitHub Actions, dependencies, and data flow
- **Exposure Monitoring:** what your public surface hands to agents and anonymous visitors, checked on a schedule with alerts

Open source tools are scanners you run. The hosted platform is an agent workforce you employ: always on, org-wide, with history, alerting, and a dashboard.

## The fleet today

28 tools live on npm (`@reneturcios/*`) and the official MCP Registry (`io.github.CloudCorpRecords/*`), 20,749 downloads per month across 18 packages (verified October 26, 2026).

Start here:

- Greenlight: https://github.com/CloudCorpRecords/greenlight
- ProdForge, the catalog and connect spine: https://github.com/CloudCorpRecords/prodforge
- Wallcheck: https://github.com/CloudCorpRecords/wallcheck
- Security Wave: hookcheck, actionpin, injectcheck, mcpvet, depguard, flowcheck, tracewatch under https://github.com/CloudCorpRecords
- Contribution ops: claimcheck, prwatch, gatefile, shipcheck, cidiff, reprocheck, mcpaudit, inboxwatch

All fleet repos stay under CloudCorpRecords for now. MCP Registry namespaces and GHCR paths depend on those locations, so transfers are evaluated one tool at a time, later.

## Pilots

Paid pilots: $500 to $2,000 per month, 60 days, one agent line, converting to annual platform contracts.

To talk about a pilot, contact Rene Turcios, Founder, San Francisco, via GitHub at https://github.com/CloudCorpRecords

## Roadmap

- Hosted platform MVP across all three lines
- Fleet instrumentation: weekly active repos and retention instead of download counts alone
- 3 to 5 paid pilots to contract quality
- First $10K MRR within 12 months, reported against instrumented metrics

## Organization

This repo belongs to CloudCorpHQ, the official GitHub organization for CloudCorp Records. The organization is a company storefront. External open source contributions stay on the founder account, https://github.com/CloudCorpRecords, with its full history.

License: MIT for this documentation repo.
