# Example: B2B SaaS Team Running Standing Competitor Monitoring

A worked example showing how a growth-stage SaaS team uses these prompts as a repeatable monitoring and enablement system — not a one-off project.

## The scenario

**Northwind** is a 40-person B2B SaaS company selling a customer-onboarding platform to mid-market ops teams. They have three named competitors, a sales team that keeps losing deals to one of them, and a PMM, **Devin**, who owns competitive intelligence on top of his day job. He needs a system, not heroics.

Here's the cadence Devin builds with this library.

## Weekly: the market brief

Every Monday, Devin runs the [weekly market brief](../prompts/agents/weekly-market-brief.md) agent. He pastes in the week's competitor changelogs, funding news, a few LinkedIn posts from rival execs, and recent G2 reviews.

The output is a scannable, newspaper-style edition: a front-page story (this week, a competitor shipped an AI feature), competitor moves, market trends, voice-of-customer signals, and an editor's take with one recommended action. He forwards it to the leadership channel. It takes 15 minutes.

## Per-release: track product moves

When a competitor ships, Devin runs the [release notes analysis](../prompts/product/release-notes.md) prompt to log it with a threat level and a recommended response (match / counter-position / ignore). Over a quarter, these logs feed the [changelog velocity analysis](../prompts/product/changelog-analysis.md) prompt, which reveals that the deal-stealing competitor has *doubled* their shipping pace since a recent raise — and is concentrating on enterprise features.

He then runs [roadmap inference](../prompts/product/roadmap-inference.md), feeding in the competitor's job postings (they're hiring SSO and audit-log engineers). The agent predicts, with stated confidence, an enterprise-security push next quarter. Northwind decides to get ahead of it.

## Monthly: refresh sales enablement

Because sales keeps losing to one competitor, Devin runs the [win/loss analysis](../prompts/sales/win-loss-analysis.md) prompt on the last 10 closed deals. The pattern isn't price (as reps claimed) — it's that the competitor's onboarding *demo* feels faster. That's a messaging and demo problem, not a product gap.

He turns that insight into an updated [battlecard](../prompts/competitor-analysis/battlecard.md) and a refreshed [objection analysis](../prompts/sales/objection-analysis.md), giving reps an honest response to "but {competitor}'s setup looks quicker" — plus a landmine question that exposes the competitor's weaker post-onboarding support.

## Quarterly: zoom out

Once a quarter, Devin runs the [competitive intelligence agent](../prompts/agents/competitive-intelligence-agent.md) as a full sweep across all three competitors, and the [emerging trends](../prompts/market-intelligence/emerging-trends.md) prompt for the category. This catches the slow-moving shifts (a new entrant, a pricing-model trend toward usage-based billing) that the weekly cadence misses.

## The result

Northwind now has: a weekly brief leadership actually reads, a per-release threat log, a roadmap prediction that shaped their own planning, and sales enablement grounded in real win/loss data instead of rep folklore. One PMM, a few hours a week.

## Where it strains — and what they automate

The system works, but it leans entirely on Devin remembering to gather sources and run the prompts. When he's heads-down on a launch, the monitoring lapses — and that's exactly when a competitor moves. The gathering-and-watching layer (continuously pulling competitor changelogs, news, LinkedIn, Reddit, and review sites, deduplicating them, and flagging what changed) is what Northwind hands to [IntelCue](https://www.intelcue.ai). It even connects to Claude via MCP, so Devin can ask *"what did our competitors do this week?"* in his AI assistant and get an answer from live data — then use the prompts in this library for the deep analysis on top.
