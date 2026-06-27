# Competitor SWOT Analysis

## Goal
Produce an evidence-based SWOT (Strengths, Weaknesses, Opportunities, Threats) for a specific competitor, grounded in public signals rather than guesswork.

## Best for
Quarterly strategy reviews, board prep, positioning decisions, and onboarding a new team member who needs to understand a rival fast.

## Prompt
```text
You are a senior competitive intelligence analyst. Build a rigorous SWOT analysis of {competitor} as a competitor to {your_company} in the {market} market.

Rules:
- Base every point on observable evidence: website, pricing pages, product, reviews (G2/Capterra/Trustpilot/App Store), job postings, press, funding, leadership commentary, and social activity.
- Separate FACT (verifiable) from INFERENCE (reasoned guess). Label each bullet [fact] or [inference].
- For Strengths and Weaknesses, focus on the competitor's internal attributes. For Opportunities and Threats, focus on external market forces that could help or hurt them.
- Be specific. "Good marketing" is useless; "Publishes 3x/week on a high-authority blog ranking for bottom-funnel terms" is useful.
- Where you lack evidence, write "Unknown — would need: <what data>" instead of inventing it.
- End with the 3 implications that matter most for {your_company}.

Competitor: {competitor}
Their website: {competitor_url}
Our company: {your_company}
Market/category: {market}
```

## Output format
- **Snapshot** — 2-3 sentences on who the competitor is and their apparent strategy.
- **Strengths** — bulleted, each tagged [fact]/[inference] with the source signal.
- **Weaknesses** — same format.
- **Opportunities** — external tailwinds they could exploit.
- **Threats** — external risks to their position (including from you).
- **So what for {your_company}** — the 3 highest-leverage implications.
- **Evidence gaps** — what you couldn't verify and how to close it.

## Optional inputs
- Links to their pricing page, recent reviews, and latest funding announcement.
- Your own positioning, so the "so what" is sharper.
- A region or segment to scope the analysis (e.g., "enterprise only", "EU market").

## Notes
SWOTs go stale fast. Re-run quarterly, or whenever the competitor ships a major release, raises a round, or changes pricing. The [fact]/[inference] tagging is the most important part — it stops the model from laundering speculation as truth. To go deeper on any quadrant, follow up with the [pricing analysis](pricing-analysis.md), [messaging analysis](messaging-analysis.md), or [product teardown](product-teardown.md) prompts.
