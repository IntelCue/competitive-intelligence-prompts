# Content Gap Analysis

## Goal
Find the topics and queries your competitors cover (and likely rank for) that you don't — and prioritize which gaps are worth closing.

## Best for
Building a content roadmap that targets winnable, high-intent demand instead of writing into a void.

## Prompt
```text
You are an SEO content strategist running a content gap analysis for {your_company} against {competitor_1}, {competitor_2} (and others if named) in the {market} market.

Steps:
1. INVENTORY: From each competitor's blog, resources, docs, and content hubs, list the major topics and content types they cover.
2. OUR COVERAGE: From {your_company}'s site, list what we already cover.
3. GAPS: Identify topics competitors cover that we don't, or cover poorly. Group into clusters.
4. PRIORITIZATION: Score each gap on three factors (High/Med/Low):
   - Buyer intent (how close to a purchase decision)
   - Strategic fit (how core to our positioning)
   - Winnability (can we realistically produce something better than what ranks?)
5. RECOMMENDATIONS: The top 8-12 content pieces to create, each with a working title, target intent, and the angle that would make ours the best result — not just another me-too post.

Rules: Be specific about topics, not generic ("write more blogs" is useless). Note where you're inferring coverage vs. confirming it. Don't fabricate rankings; this is gap discovery, validate volume separately.

Our site: {your_url}
Competitors: {competitor_1}, {competitor_2}
Market: {market}
```

## Output format
- **Coverage matrix** — topic clusters × who covers them (us vs. each competitor).
- **Priority gaps** — ranked, each scored on intent / fit / winnability.
- **Content recommendations** — 8-12 pieces: title, intent, differentiating angle.
- **Quick wins** — gaps that are high-intent and low-effort.
- **Skip list** — gaps that look tempting but aren't worth it, with the reason.

## Optional inputs
- Your sitemap and the competitors' sitemaps.
- Known keyword data to validate winnability.
- The persona or segment to bias the prioritization toward.

## Notes
The "skip list" matters as much as the gap list — chasing every competitor topic is how teams burn a year on low-intent traffic. The differentiating angle is the whole game: a gap is only worth filling if you can make the best result, not the tenth. Pair with [competitor keywords](competitor-keywords.md) (to find the gaps) and [topical authority](topical-authority.md) (to structure them into clusters).
