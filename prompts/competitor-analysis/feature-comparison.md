# Feature Comparison Matrix

## Goal
Generate a side-by-side feature comparison across several competitors so you can see where you lead, where you trail, and where the whole category is converging.

## Best for
Product planning, sales enablement, "vs." pages, and finding differentiation that's actually defensible.

## Prompt
```text
You are a product analyst building a feature comparison matrix for the {market} category.

Compare these products: {your_company}, {competitor_1}, {competitor_2}, {competitor_3}.

Steps:
1. Derive 12-20 evaluation criteria that matter to buyers in this category. Group them into themes (e.g., Core capabilities, Integrations, Pricing & packaging, Security & compliance, Support & onboarding, AI features).
2. For each product × criterion, mark one of: Yes / Partial / No / Unknown. Add a one-line note with the evidence or caveat.
3. Pull evidence from product pages, docs, changelogs, review sites, and pricing pages. Do not assume parity — verify each cell or mark it Unknown.
4. Flag any criterion where the category is clearly converging (everyone has it) vs. where there's real differentiation (only one or two have it).

Output a Markdown table with products as columns and criteria as rows, then a short analysis.
Be conservative: when in doubt, mark Unknown rather than guessing.
```

## Output format
- **Comparison table** — Markdown, products as columns, grouped criteria as rows, cells = Yes/Partial/No/Unknown.
- **Where {your_company} leads** — criteria you uniquely or strongly cover.
- **Where {your_company} trails** — gaps to close or consciously ignore.
- **Table stakes** — criteria everyone has (don't over-invest in marketing these).
- **Differentiators** — criteria few have (where positioning can win).
- **Unknowns to verify** — cells that need a hands-on check or sales-call confirmation.

## Optional inputs
- Your own feature list (so the model doesn't have to infer your side).
- The buyer persona to weight criteria by what *they* care about.
- Links to each competitor's docs/changelog for more accurate cells.

## Notes
Treat every "Yes" you didn't personally verify as "Unknown." Marketing pages overstate; docs and changelogs are more honest. This matrix pairs well with the [battlecard](battlecard.md) (for sales) and [product teardown](product-teardown.md) (for depth on a single rival). Refresh it whenever a competitor ships a major release.
