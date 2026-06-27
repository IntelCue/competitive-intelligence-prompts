# Investor & Funding Analysis

## Goal
Analyze the capital flowing into a market: who's raising, who's writing checks, what theses are forming, and what the money signals about where the category is going.

## Best for
Fundraising prep, competitive intelligence on rivals' war chests, and reading the market through its capital flows.

## Prompt
```text
You are a venture analyst studying funding activity in the {market} market over the {timeframe}.

Analyze the funding landscape:

1. NOTABLE ROUNDS: Recent raises in the space — company, round, amount, lead investor, date. Note any that stand out by size or signal.
2. ACTIVE INVESTORS: Which funds/angels are repeatedly investing in this category? What does their portfolio reveal about their thesis?
3. THESIS PATTERNS: What are investors collectively betting on? Which sub-segments are getting funded vs. starved?
4. VALUATION & DEAL CLIMATE: Is capital flowing freely or tightening? Up rounds vs. down rounds vs. flat? Bridge activity?
5. WAR CHESTS: Which competitors now have the capital to be aggressive (hiring, pricing, M&A)? What might they do with it?
6. WHAT THE MONEY SIGNALS: The strategic read — where smart money thinks this market is heading.

Rules: Cite specific rounds and sources. Distinguish confirmed funding from rumored. Mark each figure [reported] or [estimated]. Don't fabricate amounts — if unknown, say so.

Market: {market}
Timeframe: {timeframe}
Companies of interest (optional): {competitors}
```

## Output format
- **Recent rounds** — table: company, round, amount, lead, date, source.
- **Active investors** — who's deploying and their apparent thesis.
- **Thesis map** — what's getting funded vs. ignored.
- **Deal climate** — hot/cooling, with evidence.
- **War-chest watch** — competitors now armed to be aggressive.
- **Signal** — what the capital flows say about the market's direction.

## Optional inputs
- A list of competitors to focus the funding history on.
- A specific sub-segment or geography.
- Pasted funding-news items or a database export for grounding.

## Notes
Funding amounts are frequently misreported or inflated — always tag figures as reported vs. estimated, and treat unconfirmed numbers with skepticism. A big raise is a capability signal, not a success signal. The most actionable output is the war-chest watch: it tells you which competitor is about to get aggressive. Combine with [startup monitoring](startup-monitoring.md) and [emerging trends](emerging-trends.md).
