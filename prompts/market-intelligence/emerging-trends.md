# Emerging Trends Detection

## Goal
Surface, rank, and pressure-test the emerging trends in a market — separating real, durable shifts from hype and noise.

## Best for
Strategy planning, content roadmaps, investor updates, and deciding which waves are worth riding.

## Prompt
```text
You are a market analyst tracking emerging trends in the {market} market for {region} over the {timeframe}.

Identify the 5-8 most significant emerging trends. For each, provide:

1. TREND: A concrete name and a one-sentence description.
2. EVIDENCE: 2-3 specific signals you can point to (new products, funding, search/social interest, regulatory moves, hiring patterns, notable launches, analyst commentary). Cite what and where.
3. MOMENTUM (1-5): How fast it's accelerating, with your reasoning.
4. MATURITY: Where it sits — emerging / early / mainstreaming / saturated.
5. HYPE vs. REAL: Is this a durable shift or a cycle peak? What would confirm or kill it?
6. SO WHAT: The implication for a company operating in this market.

Rank the trends by a combination of momentum and durability. Be skeptical — call out anything that looks like vendor-driven hype with thin underlying demand. Mark each signal [observed] or [inferred].

Market: {market}
Region: {region}
Timeframe: {timeframe}
Our angle (optional): {your_company_context}
```

## Output format
- **Trend ranking** — ordered list, strongest signal first.
- **Per-trend cards** — name, evidence, momentum (1-5), maturity, hype-vs-real, so-what.
- **Watch list** — weaker/earlier signals worth monitoring but not acting on yet.
- **Fading** — trends that are peaking or rolling over.
- **Recommended bets** — the 2-3 trends most worth your attention and why.

## Optional inputs
- Your company's positioning, to sharpen the "so what."
- A specific sub-segment or geography to narrow the scope.
- Recent source material (news, reports, posts) pasted in for grounding.

## Notes
The momentum score is only as good as the evidence behind it — push the model to cite real signals, not vibes. The "hype vs. real" test is what separates this from a buzzword list. Continuously tracking momentum across many sources by hand is exactly the kind of work [IntelCue](https://intelcue.ai) automates; this prompt is the manual, on-demand version. Pair with [startup monitoring](startup-monitoring.md) and [investor analysis](investor-analysis.md) to see who's betting on each trend.
