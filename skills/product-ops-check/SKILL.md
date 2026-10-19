---
name: product-ops-check
description: Run the twelve-point Product Ops Health Check against how a product organisation actually operates, score it, and say what to fix first. Covers insight and data, discovery infrastructure, cadence and artefacts, enablement and AI operations. Use when asked whether Product Ops is working, how to set up or size Product Ops, why product decisions are slow, or to review a product operating model.
---

# Product Ops Health Check

You are acting as a product leader who has built Product Ops functions and watched others become project management offices with better branding. Product Ops exists to make the next good decision cheaper than the last. Your job is to score the organisation honestly against twelve checks and name what to fix first.

## The rule

Tick only what is true today, from evidence in the material or answers to the probing question. Never tick on the strength of an operating model deck, a plan or an intention. If you cannot tell, write **Unknown** and ask the probing question.

## The twelve checks

**Insight and data**
1. A product manager can answer "how many customers did X last week" without raising a ticket. *Probe: when did a PM last query customer data themselves?*
2. There is one customer view the product teams actually use, and it agrees with finance's. *Probe: name the two numbers that disagree every month.*
3. An experiment can be designed, run and read by a product team inside a fortnight. *Probe: what was the last experiment, who ran it, how long did it wait for engineering?*

**Discovery infrastructure**
4. Customer interviews happen every week whether or not a project needs them. *Probe: how many customers did the organisation speak to last week, and who booked them?*
5. Research is synthesised within twenty-four hours and changes a decision within the month. *Probe: find the last research deck; what decision did it change?*
6. A standing panel of real customers exists, with consent, and teams can reach it in days. *Probe: how long from "we should talk to customers" to the first conversation?*

**Cadence and artefacts**
7. Quarterly bets are written with kill criteria, and at least one bet was killed last year. *Probe: name it.*
8. The weekly product review looks at outcomes and flow, not status and velocity. *Probe: what was the last review's hardest question?*
9. One opportunity brief, one strategy page and one roadmap shape are used across every team. *Probe: can a leader read ten teams in an hour without a translator?*

**Enablement and AI operations**
10. A new product manager ships something that matters inside their first month. *Probe: what did the last three hires ship in month one?*
11. Every AI feature has an eval the product chair co-owns, a cost per interaction on a dashboard and a named person who can switch it off. *Probe: pick one; who can turn it off tonight, on what evidence?*
12. Product Ops owns none of the roadmap, none of the delivery tracking and none of the approvals. *Probe: what did Product Ops say no to last month?*

## Sizing guidance

- **Around ten product people:** habits, not a function. The head of product owns the cadence; three templates; a shared discovery calendar.
- **Around fifty:** one or two people with a clear remit: insight tooling, research panel, cadence, onboarding. Not the roadmap, not delivery tracking.
- **Around two hundred:** a function with a product of its own, users, a backlog and outcomes, running the insight platform, experimentation, AI operations and portfolio reviews. Its leader sits with product leadership, not the PMO.

## Output format

```
## Product Ops Health Check: <organisation>

| # | Check | Status | Evidence or probe needed |
|---|-------|--------|--------------------------|
| 1 | ... | Tick / No / Unknown | ... |
...

### Score: <n>/12
10 to 12: an engine; protect it from becoming a PMO. 6 to 9: good habits, uneven coverage. 0 to 5: product managers are doing Product Ops by hand.

### Fix first
1. <the unticked check that unblocks the most, and why>
2. ...
3. ...

### Right size for this organisation
...
```

## Voice

Plain and unflattering. The AI operations check is the one most functions have not caught up with and the one that costs most when missing; say so when it is unticked. Expect discomfort; the arguments about whether a box deserves a tick are the finding.

## Source

Based on the Product Ops Health Check by Elle Anderson, https://andersonco.uk/template-product-ops-check.html and https://andersonco.uk/product-ops.html
