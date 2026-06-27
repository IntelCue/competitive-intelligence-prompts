# Competitor Keyword Strategy

## Goal
Infer the keywords and search strategy a competitor is targeting — by intent, funnel stage, and theme — so you can decide what to compete for and what to cede.

## Best for
SEO and content teams planning a roadmap, and marketers who want to understand a rival's organic playbook without paid tools.

## Prompt
```text
You are an SEO strategist reverse-engineering the keyword strategy of {competitor}.

Analyze their site structure, page titles, H1s, blog topics, navigation, and any visible content hubs. Then infer:

1. CORE KEYWORD THEMES: The 5-8 topic clusters they're clearly targeting. For each, the apparent head term and example pages.
2. INTENT MIX: Roughly how their content splits across informational / commercial / transactional / navigational intent.
3. FUNNEL COVERAGE: Where they're strong (top/middle/bottom funnel) and where they're thin.
4. BRANDED vs. NON-BRANDED: How much they rely on their own brand terms vs. competing for category demand.
5. PROGRAMMATIC / SCALED PAGES: Any templated page patterns (e.g., "/alternatives/", "/vs/", location or integration pages) that suggest a scaled SEO play.
6. KEYWORD GAPS THEY'RE IGNORING: High-intent themes in this market they don't seem to cover.

Rules: This is inference from on-page signals, not rank data — be explicit that you're estimating. Don't invent search volumes. Where a real keyword tool would be needed, say so. Quote real page titles/URLs as evidence.

Competitor: {competitor}
URL: {competitor_url}
Our market: {market}
```

## Output format
- **Keyword theme clusters** — table: theme, apparent head term, example pages, intent.
- **Intent & funnel read** — where they invest and where they're thin.
- **Branded vs. non-branded** — their reliance on brand demand.
- **Scaled-page patterns** — programmatic templates spotted.
- **Gaps to attack** — themes they ignore that you could own.
- **Caveats** — what needs a real keyword tool to confirm.

## Optional inputs
- Their sitemap.xml URL (a goldmine for page patterns).
- Your own target keywords, to find overlap and gaps.
- Exported keyword data, if you have a tool — paste it for accuracy.

## Notes
LLMs can't see live rankings or search volume — this is structural inference, and you should treat it as a hypothesis to validate with a keyword tool (Search Console, Ahrefs, Semrush). The sitemap and URL patterns are the highest-signal inputs. Feed the gaps into the [content gap](content-gap.md) and [topical authority](topical-authority.md) prompts to turn them into a plan.
