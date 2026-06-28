# Release Notes Analysis

## Goal
Turn a competitor's release notes and product updates into a clean, dated competitive change log — so you always know what they shipped, what it means, and how to respond.

## Best for
Product and PMM teams maintaining a running view of competitor product movement.

## Prompt
```text
You are a competitive product analyst. Analyze the release notes / product updates from {competitor} over the {timeframe}.

From their changelog, release notes, blog, or "what's new" page, produce a competitive change log. For each meaningful release:

1. DATE & VERSION: When it shipped (and version if given).
2. WHAT CHANGED: A plain-English description of the update.
3. CATEGORY: New feature / enhancement / integration / fix / pricing or packaging / platform.
4. WHY IT MATTERS: The strategic read — what customer need or competitive pressure this addresses.
5. THREAT LEVEL (1-5): How much it should concern {your_company}, with reasoning.
6. RESPONSE: Match / counter-position / ignore — and a one-line "why."

Then zoom out:
- VELOCITY: How fast are they shipping, and is it accelerating or slowing?
- FOCUS: Where is their effort concentrated? What does the pattern reveal about priorities?
- NOTABLE: The 1-3 releases that matter most.

Rules: Use real release entries with dates. Skip trivial fixes unless they signal something. Don't invent releases — if the changelog is sparse, say so.

Competitor: {competitor}
Changelog URL: {changelog_url}
Timeframe: {timeframe}
Our perspective: {your_company}
```

## Output format
- **Change log** — dated table: date, change, category, threat (1-5), response.
- **Shipping velocity** — pace and trend.
- **Effort concentration** — where their roadmap energy is going.
- **Releases that matter** — the 1-3 to act on.
- **Recommended responses** — what to match, counter, or ignore.

## Optional inputs
- The exact changelog/release-notes URL (or pasted text).
- Your own roadmap, to assess match/counter decisions.
- A prior change log, to measure velocity change over time.

## Notes
Changelogs are one of the highest-signal, lowest-noise competitive sources — they're the competitor telling you exactly what they built. Reviewing them every release by hand across several competitors is tedious; this is the kind of continuous tracking [IntelCue](https://www.intelcue.ai) automates. Feed the patterns into [roadmap inference](roadmap-inference.md) and [changelog analysis](changelog-analysis.md) for the bigger picture.
