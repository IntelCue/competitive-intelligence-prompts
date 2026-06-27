# YouTube Monitoring

## Goal
Extract competitive and market intelligence from YouTube — competitor demos and ads, creator reviews, tutorials, and the comments that reveal what users really think.

## Best for
Understanding how competitors demo their product, what reviewers praise and pan, and what content drives consideration in your category.

## Prompt
```text
You are a media intelligence analyst studying YouTube activity relevant to {market} and the competitor {competitor}.

From the videos, descriptions, transcripts, and comments I provide (or that you can access), extract:

1. COMPETITOR CONTENT: What is {competitor} (and the category) publishing? (demos, launches, webinars, ads, customer stories) What do they choose to show — and hide?
2. POSITIONING IN DEMOS: In their own videos, which features and use cases do they lead with? What's the implied ideal customer?
3. CREATOR / REVIEW COVERAGE: How do third-party reviewers and creators portray them? Recurring praise, recurring criticism, and any "X vs. Y" comparisons.
4. COMMENT INTELLIGENCE: From comments — the questions, objections, complaints, and feature requests viewers raise. What confuses or excites them?
5. CONTENT THAT WORKS: Which videos/topics drive the most views and engagement in this niche, and what format wins.
6. GAPS: Topics or questions the category isn't covering well that you could own.

Then summarize the top signal for {your_company}.

Rules: Reference specific videos/channels. Use transcripts and comments as evidence. Separate creator opinion from fact. Don't fabricate view counts or quotes.

Competitor: {competitor}
Market: {market}
Videos/channels (optional): {paste_or_links}
Our perspective: {your_company}
```

## Output format
- **Competitor content map** — what they publish and lead with.
- **Demo positioning** — the features/use cases they showcase.
- **Review coverage** — third-party praise and criticism, plus comparisons.
- **Comment intelligence** — viewer questions, objections, and requests.
- **What's working** — winning topics and formats in the niche.
- **Content gaps** — what you could own.
- **Top signal** — the most important takeaway.

## Optional inputs
- Specific video URLs or channel names (paste transcripts for accuracy).
- Competitor and reviewer channels to focus on.
- The product area you most want feedback on.

## Notes
YouTube comments and review videos are an underrated source of candid feedback — they capture the objections and confusion that polished reviews omit. How a competitor demos their product (what they lead with, what they skip) is a direct read on their positioning. Pair with [product teardown](../competitor-analysis/product-teardown.md) for a fuller product picture, and [feature-request analysis](../product/feature-request-analysis.md) for the demand signals in the comments.
