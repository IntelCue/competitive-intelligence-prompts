# Startup & New-Entrant Monitoring

## Goal
Track the new and emerging startups entering a category — who they are, what they're betting on, and whether they're a threat, an acquisition target, or noise.

## Best for
Founders and product leaders watching for disruptors, corp-dev teams, and investors mapping a space.

## Prompt
```text
You are a venture analyst tracking new entrants in the {market} market.

Identify emerging startups and recent entrants (founded or pivoted within roughly the last {timeframe}). For each:

1. NAME & ONE-LINER: What they do, in their own words plus your translation.
2. WEDGE: The specific angle or underserved segment they're attacking. What's their insight?
3. STAGE & BACKING: Founding year, funding stage/amount, and notable investors if known.
4. TRACTION SIGNALS: Evidence of momentum — hiring, launches, waitlists, community, press, review velocity.
5. DIFFERENTIATION: How they're positioning against incumbents.
6. THREAT LEVEL (1-5): To an established player like {your_company}, with reasoning.
7. CATEGORY: Direct competitor / adjacent / complementary / could-go-either-way.

Rank by threat level × momentum. Be clear about confidence — many startups look bigger than they are. Mark each data point [verified] or [unverified]. Flag any that look like vaporware.

Market: {market}
Timeframe: {timeframe}
Incumbent perspective (optional): {your_company}
```

## Output format
- **Watch list** — ranked table: startup, wedge, stage, threat level.
- **Per-startup notes** — wedge, traction, differentiation, threat reasoning.
- **Rising fast** — the 1-3 to watch most closely and why.
- **Probably noise** — entrants that look thin, with the tell.
- **Pattern** — what these new entrants collectively reveal about where the market is heading.

## Optional inputs
- A seed list of startup names you already know.
- The incumbent's perspective, to calibrate threat level.
- Links to launch posts, funding announcements, or directories to ground the search.

## Notes
Public data flatters startups — a slick site and a press release aren't traction. Force the model to separate real momentum signals (hiring velocity, review growth, repeat funding) from launch theater. This list goes stale within weeks; continuous monitoring (e.g., via [IntelCue](https://www.intelcue.ai)) keeps it current. Pair with [investor analysis](investor-analysis.md) to see who's funding the wave and [emerging trends](emerging-trends.md) to see which trend each entrant is riding.
