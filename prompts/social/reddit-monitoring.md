# Reddit Monitoring

## Goal
Mine Reddit for the unfiltered truth: what real users say about your category, your competitors, and the problems they're trying to solve — including the complaints they'd never put in a review.

## Best for
Voice-of-customer research, finding unmet needs, spotting competitor weaknesses, and sourcing brutally honest product feedback.

## Prompt
```text
You are a voice-of-customer researcher analyzing Reddit discussion about {topic_or_product} in the {market} space.

From the threads, comments, and subreddits I provide (or that you can access), extract:

1. PAIN POINTS: The recurring frustrations and unmet needs people express. Rank by how often and how intensely they come up. Quote representative comments.
2. COMPETITOR SENTIMENT: What's said about specific competitors — praise, complaints, switching stories ("I moved from X to Y because..."). Note the reasons.
3. DESIRES & WORKAROUNDS: What people wish existed, and the hacks/workarounds they've built to cope (a goldmine for product gaps).
4. LANGUAGE: The actual words and phrases real users use to describe the problem (invaluable for messaging and SEO).
5. DECISION DRIVERS: What makes people choose, stay, or churn in this category.
6. EMERGING COMPLAINTS: Any newly rising gripes that could signal a shift or an opening.

Rules: Quote real comments (paraphrase if needed for length) and note the subreddit. Distinguish a one-off rant from a recurring pattern — only flag something as a "pattern" if multiple people echo it. Don't fabricate threads.

Topic/product: {topic_or_product}
Market: {market}
Subreddits/threads (optional): {paste_or_links}
```

## Output format
- **Top pain points** — ranked, with representative quotes.
- **Competitor sentiment** — per competitor: what people love, hate, and switch over.
- **Unmet desires & workarounds** — product-gap signals.
- **Customer language** — verbatim phrases for copy and SEO.
- **Decision drivers** — why people choose / churn.
- **Rising complaints** — new signals worth watching.

## Optional inputs
- Specific subreddits or thread URLs to focus on (most accurate).
- Competitor names to track sentiment for.
- A product area you most want feedback on.

## Notes
Reddit is the closest thing to an unfiltered focus group — but it skews toward power users and the loudly unhappy, so weight findings accordingly and confirm patterns across multiple threads. The "customer language" output is uniquely valuable: it gives you the exact words for messaging and search content. Pair with [feature-request analysis](../product/feature-request-analysis.md) to turn complaints into a prioritized demand list.
