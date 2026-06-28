# X (Twitter) Monitoring

## Goal
Track competitors, founders, and category narratives on X — the announcements, the discourse, the sentiment shifts, and the memes that move a market.

## Best for
Real-time competitive awareness, catching launches and controversies early, and reading the mood of a category.

## Prompt
```text
You are a social intelligence analyst monitoring X (Twitter) for the {market} space.

Track {targets} (competitors, founders, key voices) and the broader conversation over the {timeframe}. From the posts I provide (or that you can access), extract:

1. ANNOUNCEMENTS & LAUNCHES: Product news, features, partnerships, fundraises, or events — with dates and links.
2. NARRATIVE & DISCOURSE: The active debates and talking points in the category. Who's shaping the narrative? What framing is winning?
3. SENTIMENT: Overall mood toward the category and specific players — and any notable swings (e.g., a backlash, a viral win, an outage thread).
4. ENGAGEMENT PATTERNS: What kinds of posts are resonating (format, hook, topic). What's the audience rewarding?
5. EARLY SIGNALS: Rumors, hints, "soon" teasers, and quiet hires/announcements that precede bigger moves.
6. INFLUENCE MAP: The accounts that actually move opinion in this niche.

Then summarize the most important signal for {your_company}.

Rules: Quote posts and note the handle and rough date. Separate confirmed news from rumor. Don't fabricate post metrics or quotes.

Targets: {targets}
Market: {market}
Timeframe: {timeframe}
Posts (optional): {paste_content}
Our perspective: {your_company}
```

## Output format
- **Announcements log** — dated, with links.
- **Narrative read** — the live debates and who's winning the framing.
- **Sentiment** — mood and any notable swings.
- **What's resonating** — post patterns the audience rewards.
- **Early signals** — teasers and rumors worth tracking.
- **Influence map** — the accounts that matter.
- **Top signal** — the one thing to act on or watch.

## Optional inputs
- A list of handles to track (companies + founders + analysts).
- Specific hashtags or search terms for the category.
- Pasted posts/threads if your model can't access X.

## Notes
X moves fast and rewards hot takes — distinguish a genuine signal from a passing pile-on, and confirm "news" before you act on it. The early-signals section is the real value: launches and controversies often surface here first. Tracking it continuously is impractical manually; platforms like [IntelCue](https://www.intelcue.ai) monitor social and news sources together so signals aren't missed. Feed launches into [release notes](../product/release-notes.md) tracking.
