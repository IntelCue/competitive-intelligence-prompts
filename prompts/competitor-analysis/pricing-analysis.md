# Pricing & Packaging Analysis

## Goal
Reverse-engineer a competitor's pricing strategy: their tiers, what gates each tier, their monetization model, and the psychology behind it.

## Best for
Pricing decisions, packaging redesigns, discount strategy, and understanding how a rival makes money (and where they leave it on the table).

## Prompt
```text
You are a pricing strategist. Analyze the pricing and packaging of {competitor} in the {market} market.

Cover:
1. PLANS: List every tier with price, billing period, and the headline limit/seat model. Note annual vs. monthly discounts.
2. VALUE METRIC: What do they charge by? (seats, usage, sources, contacts, revenue, flat) Is the metric aligned with customer value?
3. GATES: What's locked behind each tier? Which features force the upgrade from one tier to the next? Identify the "upgrade triggers."
4. ANCHORING & PSYCHOLOGY: How do they use anchoring, "most popular" badges, enterprise "contact us", free trials, freemium, or annual nudges?
5. POSITIONING: Are they priced as premium, mid-market, or value? How does the entry price compare to alternatives?
6. WEAK POINTS: Where is the pricing confusing, punitive, or vulnerable to a cheaper/simpler challenger?

Rules: Use only what's on their pricing page, docs, and public sources. If a price is "contact sales" or hidden, say so and estimate a range only if you flag it as an estimate. Quote exact numbers where available.

Competitor: {competitor}
Pricing page: {pricing_url}
Our pricing (optional): {your_pricing}
```

## Output format
- **Plan table** — tier, price (monthly/annual), value metric, key gates.
- **Monetization model** — how they make money and what they're optimizing for.
- **Upgrade triggers** — the specific limits/features that push customers up a tier.
- **Pricing psychology** — anchoring, badges, trials, and nudges in play.
- **Vulnerabilities** — where their pricing is exploitable.
- **Implications for {your_company}** — packaging moves to consider.

## Optional inputs
- Your own pricing, for a direct contrast.
- Target segment (SMB vs. enterprise changes the read entirely).
- Screenshots or pasted text of the pricing page if the model can't browse.

## Notes
Pricing pages change quietly and often — date your analysis and re-check before any big decision. Watch for "hidden" enterprise pricing; the absence of a number is itself a signal (usually: high ACV, sales-led). Pair with [messaging analysis](messaging-analysis.md) to see whether their price matches the value story they tell.
