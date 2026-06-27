# SERP Analysis

## Goal
Break down a specific search results page — what's ranking, what intent Google is rewarding, which SERP features dominate, and what it would actually take to rank.

## Best for
Deciding whether a keyword is worth pursuing, and reverse-engineering the content that wins for it.

## Prompt
```text
You are an SEO analyst dissecting the search results for the query: "{keyword}" (region: {region}).

Analyze the SERP (from your browsing, or from the results I paste below):

1. SEARCH INTENT: What does Google think the searcher wants? (informational / commercial / transactional / navigational, and any sub-intent). What does the mix of ranking pages reveal?
2. RANKING PAGES: For the top results, note the page type (blog, product, listicle, comparison, tool, video), the domain type (brand, publisher, aggregator), and the apparent angle.
3. SERP FEATURES: What features are present? (AI Overview, featured snippet, People Also Ask, video, images, shopping, local pack, sitelinks). Who owns them?
4. CONTENT PATTERN: What format and depth do the winners share? (word count range, structure, media, freshness)
5. DIFFICULTY READ: How hard does this look to rank for, and why? (domain strength of incumbents, content quality bar, intent match required)
6. WINNING ANGLE: If {your_company} wanted to rank, the specific content type, angle, and must-have elements to beat what's there — plus how to win the AI Overview / featured snippet.

Rules: Be explicit when you're inferring vs. reading live results. Don't fabricate exact positions or metrics. Recommend validating difficulty with a real tool.

Keyword: {keyword}
Region: {region}
Our site (optional): {your_url}
Pasted SERP (optional): {paste_results}
```

## Output format
- **Intent verdict** — what Google rewards for this query.
- **Ranking-page breakdown** — page types, domains, angles in the top results.
- **SERP feature map** — which features are present and who owns them.
- **Winning content pattern** — the shared format/depth of what ranks.
- **Difficulty read** — how hard, and why.
- **Your play** — the angle and must-haves to rank, including the snippet/AI-Overview strategy.

## Optional inputs
- The pasted SERP (if your model can't browse).
- Your domain, to assess realistic chances.
- A cluster of related keywords to analyze together.

## Notes
Intent match beats raw effort — if the SERP is all listicles and you publish a product page, you won't rank no matter how good it is. Paste in the live SERP for the most accurate read, since models can't reliably see current results. Use alongside [content gap](content-gap.md) and [topical authority](topical-authority.md) to turn a single SERP win into a cluster strategy.
