# Changelog Velocity Analysis

## Goal
Analyze the velocity and pattern of a competitor's changelog over time — how fast they ship, where they focus, and what the rhythm reveals about their priorities and health.

## Best for
Spotting when a competitor accelerates, stalls, or pivots — often before it shows up anywhere else.

## Prompt
```text
You are a product analyst studying the shipping patterns of {competitor} from their changelog over {timeframe}.

Analyze beyond individual releases to the meta-pattern:

1. VELOCITY: Roughly how many meaningful releases per month/quarter? Is the pace accelerating, steady, or slowing? Note any gaps (a silent quarter is a signal).
2. CATEGORY MIX: How do releases split across new features / enhancements / integrations / fixes / platform / performance? What does the mix say about their stage and priorities?
3. FOCUS AREAS: Which parts of the product get the most attention? Which are neglected? Has the focus shifted over the period?
4. THEME ARCS: Multi-release initiatives — sequences that build toward a bigger capability (e.g., three releases that together add an "AI assistant").
5. SIGNALS OF HEALTH: Does the pattern suggest a team that's scaling and confident, or stretched and reactive (lots of fixes, little new)?
6. INFLECTIONS: Any clear before/after moments — a pivot, a slowdown, a sudden burst (often post-funding or post-leadership change).

Rules: Work from the dated changelog. Quantify where you can; estimate ranges where you can't (and say so). Don't fabricate release counts.

Competitor: {competitor}
Changelog URL: {changelog_url}
Timeframe: {timeframe}
```

## Output format
- **Velocity trend** — releases over time and the trajectory.
- **Category mix** — the split and what it implies.
- **Focus map** — where effort concentrates vs. what's neglected.
- **Theme arcs** — multi-release initiatives in progress.
- **Health read** — scaling-and-confident vs. stretched-and-reactive.
- **Inflection points** — notable shifts and likely causes.

## Optional inputs
- A longer time window for trend accuracy.
- Funding/leadership-change dates, to correlate with inflections.
- Your own shipping cadence, for a relative benchmark.

## Notes
Velocity changes are leading indicators — a competitor who suddenly goes quiet may be mid-rebuild, distracted, or in trouble, while a sudden burst often follows a raise or a new product lead. The theme-arc analysis is what turns a list of changes into a story about strategy. Pairs directly with [release notes](release-notes.md) (the entries) and [roadmap inference](roadmap-inference.md) (what's next).
