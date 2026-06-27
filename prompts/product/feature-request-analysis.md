# Feature-Request & Demand Analysis

## Goal
Surface unmet demand from public feature requests, reviews, and forums — what users are asking competitors for, and what that reveals about gaps you could fill.

## Best for
Product prioritization, finding wedges against competitors, and validating demand before you build.

## Prompt
```text
You are a product researcher mining public feature requests and unmet needs in the {market} space, focused on {competitor} and the category at large.

Sources: public roadmaps and request boards (Canny, Nolt, GitHub issues, community forums), review sites (G2, Capterra, Trustpilot, App Store), and social/Reddit threads. From what I provide (or that you can access), extract:

1. TOP REQUESTS: The most frequently and intensely requested features/changes. Rank by demand signal (frequency + intensity + recency). Quote representative asks.
2. UNMET NEEDS: Needs implied by complaints and workarounds, even if not phrased as a "request."
3. STATUS: For each, what the competitor has said (planned / declined / ignored / shipped). Acknowledged-but-not-shipped requests are prime openings.
4. SEGMENTS: Which type of user is asking (power user, SMB, enterprise, specific vertical)? Demand isn't uniform.
5. OPPORTUNITY SCORE: For {your_company}, rank each gap on demand × strategic fit × effort.
6. WEDGES: The 3-5 unmet needs that would make the strongest competitive wedge, with the angle.

Rules: Distinguish a loud minority from broad demand — only call something "high demand" if the signal is repeated across sources. Quote real requests. Don't fabricate request volumes.

Competitor: {competitor}
Market: {market}
Sources (optional): {paste_or_links}
Our perspective: {your_company}
```

## Output format
- **Top requests** — ranked, with demand signal and quotes.
- **Unmet needs** — implied gaps from complaints/workarounds.
- **Status map** — what the competitor has said about each.
- **Segment view** — who's asking for what.
- **Opportunity scores** — demand × fit × effort for each gap.
- **Recommended wedges** — the 3-5 strongest openings and the angle.

## Optional inputs
- Links to the competitor's public request board (highest signal).
- Review-site exports for volume.
- Your roadmap, to assess fit and avoid duplicating planned work.

## Notes
A competitor's public request board is a free, ranked list of their product's weaknesses — and the "acknowledged but not shipped" items are the richest openings. Guard against the loud-minority trap: validate that demand repeats across multiple sources before betting on it. Combine with [reddit monitoring](../social/reddit-monitoring.md) and [youtube monitoring](../social/youtube-monitoring.md) to widen the demand picture.
