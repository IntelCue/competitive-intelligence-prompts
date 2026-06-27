# Roadmap Inference

## Goal
Infer a competitor's likely roadmap — what they'll build next — from public signals, before they announce it.

## Best for
Product strategy, staying ahead of competitive moves, and pressure-testing your own roadmap against where rivals are heading.

## Prompt
```text
You are a competitive product strategist. Infer the likely near-term roadmap of {competitor} (next ~2-4 quarters) from public signals.

Gather and weigh evidence from:
- Recent releases and shipping velocity (what they've been building toward)
- Job postings (the roles they're hiring reveal where they're investing)
- Public roadmap, beta programs, feature flags, or "coming soon" mentions
- Docs/API changes that hint at unreleased capabilities
- Executive statements, blog posts, conference talks, and investor messaging
- Customer requests they've publicly acknowledged
- Funding (capital enables ambition)

Then produce:
1. LIKELY BETS: The 4-7 things they're most likely to ship next, each with the supporting signals and a confidence level (High/Medium/Low).
2. STRATEGIC DIRECTION: The bigger arc — where the product is heading and the thesis behind it.
3. TELLS: The specific signals to watch that would confirm or deny each prediction.
4. IMPLICATIONS: What this means for {your_company} — where we should pre-empt, differentiate, or not bother.

Rules: This is inference — label confidence honestly and show the evidence chain for each prediction. Hiring + docs + velocity together are stronger than any single signal. Don't state guesses as facts.

Competitor: {competitor}
Known signals (optional): {paste_signals}
Our perspective: {your_company}
```

## Output format
- **Likely bets** — predicted features with evidence and confidence.
- **Strategic direction** — the overarching arc.
- **Confirming tells** — signals to monitor for each prediction.
- **Implications for {your_company}** — pre-empt / differentiate / ignore.
- **Confidence summary** — overall how readable their roadmap is.

## Optional inputs
- Their current job postings (one of the strongest signals).
- Their public roadmap or beta announcements.
- Your own roadmap, to find collisions and gaps.

## Notes
Job postings are the most underrated roadmap signal — a company hiring three ML engineers and a "Head of Payments" is telling you what's coming. The discipline is in the confidence labels and evidence chains; without them this becomes fan fiction. Build the input from a running [release notes](release-notes.md) log and [changelog analysis](changelog-analysis.md).
