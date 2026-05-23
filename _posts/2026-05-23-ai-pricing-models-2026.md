---
layout: post
title: "AI Pricing Models: Per-Seat vs Per-Use vs Outcome (2026)"
canonical_url: "https://korixinc.com/learning-center/ai-pricing-models-2026"
description: "AI pricing models explained for 2026: per-seat, per-token, per-ticket, per-resolution (outcome-based), hybrid, and bespoke. Pick on TCO, not the trial."
tags: ["AI", "Enterprise AI", "B2B"]
date: 2026-05-23 09:00:00 +0000
---

> **This article was originally published on [korixinc.com](https://korixinc.com/learning-center/ai-pricing-models-2026).**
> Read the canonical version at: <https://korixinc.com/learning-center/ai-pricing-models-2026>

# AI Pricing Models: Per-Seat vs Per-Use vs Outcome (2026)

_AI pricing models explained for 2026: per-seat, per-token, per-ticket, per-resolution (outcome-based), hybrid, and bespoke. Pick on TCO, not the trial._

![AI Pricing Models: Per-Seat vs Per-Use vs Outcome (2026)](https://korixinc.com/wp-content/uploads/2026/05/ai-pricing-models-2026-v1.png)

**AI pricing in 2026 splits into six models: per-seat, per-token (usage), per-ticket, per-resolution (outcome-based), hybrid (base + overage), and bespoke (capex). Per-seat is collapsing — 21% to 15% of SaaS in 12 months. Hybrid is the new industry standard at 41% adoption. The cheapest model at trial is rarely the cheapest at 12-month or 36-month scale.**

I've spent 19 years building software systems, the last several focused on AI implementation for service businesses with 20-150 staff. The single most expensive mistake buyers make in 2026 is choosing an AI tool on the trial-month price rather than the 36-month total cost of ownership. The pricing model determines the cost shape — linear, sub-linear, step-function, or capex — and the cost shape determines whether you're saving money or quietly hemorrhaging it.

This article walks through the six pricing models, where each one wins, what to ask vendors before signing, and how to calculate the all-in cost at scale. The data backing each section: [Bessemer Venture Partners' 2026 AI Pricing Playbook](https://www.bvp.com/atlas/the-ai-pricing-and-monetization-playbook) tracks the shift across 200+ AI vendors and reports that hybrid pricing rose from 27% to 41% adoption in 12 months while pure per-seat fell from 21% to 15%. [BCG's 2026 AI Value Capture research](https://www.bcg.com/capabilities/artificial-intelligence) backs the alignment conclusion: vendors that align pricing to outcome capture more total revenue at higher buyer satisfaction than vendors that anchor on seats or tokens alone. [MIT NANDA's 2025 State of AI Report](https://nanda.mit.edu/) separately found that only 5% of AI projects reach production — and pricing-model mismatch is one of the most common reasons projects stall before deployment, because the buyer's CFO never sees a path from "trial cost" to "scale cost" they can defend at the board.

The six models below are how the 2026 AI vendor market is structured. Each has a specific cost shape, lock-in dynamic, and incentive alignment. Get this wrong and the AI line item compounds quietly into a number nobody planned for.

## The Six Pricing Models

Every AI vendor in 2026 picks one of six pricing approaches. The model determines the cost shape at scale, the lock-in dynamics, and the alignment between vendor incentives and buyer outcomes.

### 1. Per-Seat — $50-200/seat/month

**How it works:** Flat monthly fee per human user with access to the AI. Common for IDE-style developer assistants, design tools, and CRM-embedded AI.

**Cost shape at scale:** Linear with team size. Adding a 50th seat costs the same as adding a 5th seat.

**When it wins:** Internal tools where one human is genuinely the bottleneck. Developer assistants (GitHub Copilot, Cursor) and design tools (Figma AI) are the clearest fit. Per-seat is also right for products where usage is highly correlated with seat count anyway.

**When it breaks:** When [AI agents](https://korixinc.com/agents) do work that would otherwise require multiple humans. If one seat with an AI assistant handles 3× the workload of one seat without, per-seat pricing leaves 67% of the value on the table — and forward-thinking vendors are abandoning the model.

**Trend:** Pure per-seat fell from 21% to 15% of SaaS companies between 2025 and 2026, per [Bessemer's tracking](https://www.bvp.com/atlas/the-ai-pricing-and-monetization-playbook). Most vendors are moving to hybrid (per-seat plus usage overage) rather than killing per-seat entirely.

### 2. Per-Token (Usage-Based) — $0.0001 to $0.10 per 1,000 tokens

**How it works:** The buyer pays for raw computational input — every word the AI reads or writes generates a per-token charge. Standard for foundation-model APIs (OpenAI, Anthropic, Google) and API-first AI infrastructure products.

**Cost shape at scale:** Linear with usage. Predictable but punishing at high volume.

**When it wins:** API-level products where the buyer is building their own application on top. Predictable for prototyping and low-volume use cases.

**When it breaks:** At high volume, per-token costs can dominate the AI line item. A customer support agent handling 100,000 conversations per month at GPT-4 pricing can land in the five-figure range monthly without optimisation.

### 3. Per-Ticket — $0.30-1.00 per inbound conversation

**How it works:** Fixed fee per inbound conversation regardless of resolution outcome. Common in customer support and chatbot deployments.

**Cost shape at scale:** Linear with conversation volume.

**When it wins:** When conversation volume is predictable and resolution rates are uniformly high. Buyer can budget cleanly because cost = volume × rate.

**When it breaks:** When the AI's resolution rate is variable. Buyer pays for every conversation including the ones the AI fails to handle, which is the worst alignment of the six models.

### 4. Per-Resolution (Outcome-Based) — $0.50-2.00 per resolved conversation

**How it works:** Vendor charges only when the AI delivers a specific business outcome — a resolved customer conversation, a qualified lead, a closed ticket. Failed attempts cost nothing.

**Cost shape at scale:** Linear with outcomes, but only with successful outcomes — sub-linear if the buyer drives resolution rate up over time.

**Real numbers (May 2026):** Intercom charges $0.99 per resolved conversation. HubSpot's Customer Agent dropped to $0.50 per resolved conversation in April 2026 (from $1.00). Salesforce's Agentforce uses similar outcome-based pricing for specific workflows.

**When it wins:** For customer-support, sales-qualification, and ticket-resolution use cases where the outcome is clearly defined and the resolution rate is the variable that matters. This is the most aligned model — vendor only gets paid when the AI actually solves the buyer's problem.

**When it breaks:** When the definition of "resolution" varies between vendors or can be gamed. Specify resolution criteria contractually before signing — including what happens for "false positive" resolutions where the AI claims success but the customer follows up.

[Andrew Ng](https://www.deeplearning.ai/) has been making the broader argument behind outcome-based pricing for years: AI value is best measured against business metrics that matter, not against engineering metrics that don't. Pricing models that anchor to outcomes force both vendor and buyer to keep that focus.

### 5. Hybrid (Base + Usage Overage) — variable

**How it works:** A base subscription fee covers a defined volume of usage; overage fees apply beyond the included tier. Now the dominant industry-standard model in 2026.

**Cost shape at scale:** Step function (constant within tier, jumps at tier boundary, then linear in overage).

**Trend:** Hybrid pricing rose from 27% to 41% of AI vendors between 2025 and 2026, per Bessemer. The reason: hybrid gives vendors a stable revenue floor while letting them capture upside as buyer usage scales.

**When it wins:** When buyer volume is somewhat predictable but with growth upside. The base covers committed usage; overage fees scale only when value-delivery scales.

**When it breaks:** When overage rates are punitively higher than included-tier rates. Some vendors charge 2-3× more per unit on overage than within the included tier — a hidden cost that compounds at growth.

### 6. Bespoke / Capex One-Time — fixed-scope build

**How it works:** The buyer pays a one-time build fee for a deployed AI system, with full code ownership transferred. No recurring platform fee, no per-seat, no per-token. Maintenance and feature additions are separately scoped.

**Cost shape at scale:** Capex (one-time). After the build, marginal cost is the underlying compute (LLM API calls, infrastructure) only.

**Real numbers:** A [KORIX 21-Day AI Pilot](https://korixinc.com/ai-pilot) typically lands between $15,000-$40,000 for a single deployed agent or workflow with full ownership transfer. Compare that to the five-year cumulative cost of any subscription model at meaningful volume.

**When it wins:** At scale (5,000+ workflow runs/month or 50+ active workflows), or for service businesses past the size threshold where licensing economics flip. [Our breakdown of the capability cliff](https://korixinc.com/learning-center/top-ai-workflow-automation-tools-2026) covers this in detail. Also wins for any regulated environment where the buyer needs to own every line of code.

**When it breaks:** For very-low-volume use cases where a SaaS subscription would cost less than the build fee for the first 12-18 months. [BYOS deployment](https://korixinc.com/byos) is the right answer past a specific threshold, not on Day 1 for a single small workflow.

## Cost Shape: The Comparison That Matters

The trial-month price is misleading. The 12-month and 36-month total cost at scale is what determines whether you're saving money or hemorrhaging it. The table below shows projected cost for a representative customer-support workflow handling 5,000 conversations/month, scaling to 25,000/month over three years.

- **Per-Seat (15 seats)** · *Year 1 cost:* $18,000 · *Year 3 annual:* $22,500 · *3-yr total:* ~$60,000 · *Cost shape:* Linear (team size)
- **Per-Ticket ($0.50)** · *Year 1 cost:* $30,000 · *Year 3 annual:* $150,000 · *3-yr total:* ~$280,000 · *Cost shape:* Linear (volume)
- **Per-Resolution ($0.99 @ 70%)** · *Year 1 cost:* $41,580 · *Year 3 annual:* $207,900 · *3-yr total:* ~$390,000 · *Cost shape:* Linear with successful outcomes
- **Hybrid (base + overage)** · *Year 1 cost:* $24,000 · *Year 3 annual:* $72,000 · *3-yr total:* ~$170,000 · *Cost shape:* Step function
- **Bespoke (KORIX BYOS )** · *Year 1 cost:* $30,000 + ~$5K LLM · *Year 3 annual:* ~$25K LLM only · *3-yr total:* ~$95,000 · *Cost shape:* Capex + marginal compute

*Pricing as of May 2026; figures are illustrative based on stated vendor list pricing and BYOS one-time build cost. Actual costs vary by negotiated terms and underlying infrastructure choices.*

The pattern: at low volume in Year 1, per-seat looks cheapest. By Year 3 at 25,000 conversations/month, bespoke is the dominant cost-winner. [Cassie Kozyrkov](https://kozyrkov.medium.com/), former Chief Decision Scientist at Google, frames this kind of decision bluntly: *"The bottleneck is not the AI technology. The bottleneck is knowing which problem to give it."* Pricing-model selection is just a specific case — pick on the right problem framing (cost at projected scale, not at trial), and the right model becomes obvious.

## The Five Questions to Ask Every AI Vendor on Pricing

Before committing to any AI tool, walk every prospective vendor through these five questions. Their answers — or refusal to answer — predict whether you're being sold a sustainable solution or a one-year honeymoon followed by a cost surprise.

1. **What's the all-in cost at 10× current volume?** If the answer is "let's discuss enterprise pricing", you're getting a vague number that protects vendor optionality at your expense. Push for a written quote at projected Year-3 volume.
2. **What's the overage rate?** For hybrid and tiered models, the per-unit cost of going over the included tier is often 2-3× the in-tier rate. This is where surprise bills come from.
3. **How is "outcome" defined for outcome-based pricing?** Get the resolution criteria in writing. If the vendor's definition of "resolved conversation" includes cases where the customer follows up, you're paying for false positives.
4. **What happens to my data and workflows if I leave?** Lock-in cost is hidden until you try to leave. Ask: can I export my workflows? My data? My configuration? [The full cost of vendor lock-in compounds over 3-5 years.](https://korixinc.com/learning-center/hidden-costs-wrong-partner)
5. **Can you show me a comparable buyer's actual 36-month TCO?** Not a marketing case study. The actual quarterly invoice trajectory for a similar buyer over three years. Vendors who can produce this are confident in their pricing model. Vendors who can't are hoping you don't ask.

According to [Atlassian's 2026 State of Product survey](https://www.atlassian.com/state-of-teams), 46% of operations teams cite integration as the single biggest barrier to scaling AI automation — but pricing surprise comes second. Buyers who calculate TCO at projected scale before signing avoid the surprise.

![AI Pricing Models: Per-Seat vs Per-Use vs Outcome (2026)](https://korixinc.com/wp-content/uploads/2026/05/ai-pricing-models-2026-v1-1024x614.png)

AI Pricing Models: Per-Seat vs Per-Use vs Outcome (2026) — at a glance.

## Three Pricing Failures I've Seen

Pattern recognition from inheriting AI projects. Names disguised; numbers exact.

### Failure 1: The per-token surprise

A B2B services firm built a customer-support AI on a foundation-model API at per-token pricing. Trial month cost: $300. Month 12 cost: $14,000 — driven by a feature launch that increased conversation volume 40× in two weeks. The team had no cost cap, no usage alerts, no fallback to a smaller model for low-stakes queries. The fix was a six-week re-architecture with model-tier routing (cheap model for FAQ, GPT-4 for complex cases) and per-conversation cost caps. The right design from Day 1 would have been hybrid pricing with a per-conversation budget rather than raw per-token.

**Lesson:** Per-token pricing is fine for prototyping. For production, wrap it in a per-conversation budget with tier-routing — or move to a hybrid plan that caps your downside.

### Failure 2: The per-seat trap

A 60-person firm bought a per-seat AI assistant at $80/seat/month for 60 seats, projecting "everyone uses AI". Year-end usage data: 12 of 60 seats accounted for 95% of the value. The other 48 seats were near-dormant — sometimes used once a quarter. The firm was paying $46K/year for usage worth $9K/year if priced honestly. The fix was renegotiating to a tiered hybrid plan: $30/seat base + per-conversation overage for power users.

**Lesson:** Per-seat pricing assumes uniform usage. AI tools rarely have uniform usage. Track actual usage for 60 days before committing to per-seat at scale; renegotiate when usage is concentrated.

### Failure 3: The bespoke project that should have been SaaS

A mid-market firm built a fully bespoke API service for a workflow that any of three SaaS platforms would have handled. Year 1 build cost: $45K. Year 1 ongoing infrastructure + maintenance: $20K. The same workflow on a hybrid SaaS plan would have cost roughly $9K/year. Two years later, the firm migrated to the SaaS option and ran the workflow at one-third the cost.

**Lesson:** Bespoke is the right answer when no platform fits or when scale flips the economics. It's the wrong answer when a platform would fit but the team has internal resistance to "using a tool". Validate against existing platforms before committing to bespoke.

## Why Pricing Models Are Shifting in 2026 — and What It Means for Buyers

The 26-percentage-point swing from per-seat to hybrid in 12 months isn't random. Three forces are driving it.

**Force 1 — Per-seat under-prices AI value.** When one human with an AI assistant produces three humans' worth of output, the vendor charging per-seat is leaving roughly 67% of the buyer's value on the table. Forward-thinking vendors restructured to capture more of that upside, which they can do legitimately by sharing the productivity gain. [Bessemer's research](https://www.bvp.com/atlas/the-ai-pricing-and-monetization-playbook) tracks the model shift across the 200 fastest-growing AI vendors — and the leaders are almost uniformly on hybrid or outcome-based pricing, not per-seat.

**Force 2 — Outcome-based pricing increases buyer trust.** When a vendor says "I only get paid when the AI actually solves your problem," the buyer's purchasing risk drops to near zero. [Deloitte's 2026 State of Generative AI in the Enterprise](https://www.deloitte.com/global/en/our-thinking/insights/topics/digital-transformation/ai-dossier.html) found 72% of enterprise AI projects exceed their original budget by at least 30%, and outcome-based pricing is one of the few defenses against that overrun pattern — because the buyer literally pays nothing for the failure modes.

**Force 3 — Hybrid is the rational compromise.** Pure outcome-based pricing creates revenue volatility for vendors that VCs don't fund well. Hybrid (base + overage) gives vendors a stable revenue floor and gives buyers a predictable bill, with both sides participating in the upside as usage scales. That's why 41% of AI vendors landed there in 2026 — it satisfies both incentive structures.

For service businesses with 20-150 staff, the practical implication is simple: **be skeptical of any AI vendor still pushing pure per-seat in 2026 as their only option**. The vendors who haven't moved off per-seat by now either don't have the data to back the shift or are protecting old revenue at the expense of new value-alignment. Either way, they're not the vendors you want for your next three years of AI deployment.

 

## The Honest Recommendation

For your first AI deployment at small volume, hybrid pricing on a major platform (Zapier, Make, Intercom, HubSpot) is almost always the right starting point. Predictable base cost, scales gracefully, no commitment beyond the monthly plan.

For customer-support and ticket-resolution use cases at moderate volume, per-resolution outcome-based pricing aligns vendor and buyer incentives best. Get the resolution definition in writing before signing.

For internal-tools use cases (developer assistants, design tools) where one human is genuinely the bottleneck, per-seat continues to work — but only if usage is uniform across seats.

At scale (5,000+ workflow runs/month or 50+ active workflows), or for any regulated environment, bespoke deployment via [KORIX BYOS](https://korixinc.com/byos) typically wins on 36-month TCO and on the ownership/governance dimensions that matter most. The [21-Day Pilot](https://korixinc.com/ai-pilot) is the structured engagement we recommend for validating the use case and the deployment model in one bounded scope.

For the broader question of which AI workflow tool fits which use case at which scale, our breakdown of [the 8 best AI workflow tools and where each one breaks](https://korixinc.com/learning-center/top-ai-workflow-automation-tools-2026) covers the platform comparison side. For "what does AI implementation actually cost?", see [our full cost breakdown](https://korixinc.com/learning-center/ai-implementation-cost).

KORIX defines AI pricing as *the long-tail cost shape, not the short-tail trial price — a tool that costs $50/month at trial and $5,000/month at scale is more expensive than a tool that costs $200/month at trial and $300/month at scale*. Most buyers in 2026 still optimise on the trial price and discover the scale cost months after lock-in. Don't.

The Bottom Line

## Six AI pricing models exist in 2026. The cheapest at trial is rarely the cheapest at scale — pick on *cost shape*, not on starting price.

Per-seat pricing is collapsing (21% → 15% of SaaS in 12 months). Hybrid (base + usage overage) is the new industry standard at 41% adoption. Per-resolution outcome-based pricing aligns vendor and buyer incentives — Intercom charges $0.99 per resolved conversation; HubSpot dropped to $0.50 in April 2026. The cheapest model at the trial-month price is rarely the cheapest at 12-month or 36-month scale. Pick on the cost shape (linear, sub-linear, step-function) at projected volume — not the headline number on the pricing page.

FAQ

## Common questions about
*Costs & Pricing.*

Have a question not listed here?

[Ask us directly →](https://korixinc.com/contact)What is the most common AI pricing model in 2026?

Hybrid pricing — a base subscription plus usage overage — is now the industry standard, adopted by 41% of AI vendors per Bessemer Venture Partners' 2026 AI Pricing Playbook (up from 27% in 2025). Pure per-seat pricing has fallen from 21% to 15% in the same period because it no longer reflects the value AI delivers when one seat can handle 10× the volume of work. Pure usage-based pricing (per token, per call) is most common for API products. Outcome-based pricing (per resolution) is rising fast for customer-support and sales agents.

How does outcome-based AI pricing work?

Outcome-based pricing charges only when the AI delivers a specific business outcome — typically a resolved customer conversation, a qualified lead, or a closed ticket. Intercom charges $0.99 per resolved conversation; HubSpot dropped its Customer Agent pricing to $0.50 per resolved conversation in April 2026. The buyer pays nothing for AI attempts that fail or get escalated to a human. This aligns vendor and buyer incentives because the vendor only gets paid when the AI actually solves the problem. The risk for buyers is that 'resolution' definitions vary between vendors and can be gamed if not contractually specified.

Is per-seat AI pricing dying?

Pure per-seat pricing is shrinking but not dying. Per-seat fell from 21% to 15% of SaaS companies in 12 months according to industry tracking. The reason: AI agents make seat-based pricing absurd. If one human seat with an AI assistant handles the workload of three humans, the vendor charging per-seat is leaving 67% of the value on the table. Hybrid pricing (base seat + usage overage) is replacing pure per-seat. For internal tools and IDE-style products where one human is genuinely the bottleneck (developer assistants, design tools), per-seat continues to make sense.

What's the difference between per-token and per-resolution pricing?

Per-token pricing charges for the raw computational input: every word the AI reads or writes generates a per-token charge (typically $0.0001 to $0.01 per 1,000 tokens depending on model). Per-resolution pricing charges only when the AI completes a specific business outcome. Per-token works for API-level products where the buyer integrates the AI into their own application. Per-resolution works for end-user products where the AI is the application. Per-token is cheaper at low volume; per-resolution is cheaper if the AI's resolution rate is high and the buyer would otherwise pay for many failed attempts.

How do I calculate true AI cost across pricing models?

Compare on 12-month and 36-month total cost at projected scale, not on the trial-month price. The five inputs you need: (1) volume — how many users, conversations, tokens, or resolutions per month at year 1, year 2, year 3? (2) cost per unit at each tier; (3) overage rates if volume exceeds plan; (4) any hidden costs (data egress, integration fees, professional services); (5) lock-in implications (multi-year contract discounts vs flexibility cost). The headline price on the pricing page rarely matches the all-in 36-month TCO. For bespoke deployment models like KORIX BYOS, the calculation is simpler — capex one-time build, no recurring platform fee — which is why bespoke wins at scale.


---

*Originally published at [korixinc.com](https://korixinc.com/learning-center/ai-pricing-models-2026) — read with the full design + comments.*


*Tags: AI, Enterprise AI, B2B*


**IMPORTANT: in Medium → Story Settings → 'More options' → set canonical URL to:**
`https://korixinc.com/learning-center/ai-pricing-models-2026`