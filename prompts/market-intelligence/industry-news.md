# Industry News Briefing

## Goal
Turn a pile of recent industry news into a prioritized, signal-rich briefing — what happened, why it matters, and what (if anything) to do about it.

## Best for
Staying current without drowning, weekly team updates, and feeding a leadership digest.

## Prompt
```text
You are an industry analyst writing a briefing for a busy operator in the {market} market.

From the news and sources below (or from your browsing of the {timeframe}), produce a prioritized briefing.

For each item that matters:
1. HEADLINE: A plain-English summary in one line.
2. WHAT HAPPENED: 2-3 sentences of substance, with the source.
3. WHY IT MATTERS: The strategic implication — for the market, for competitors, or for us.
4. SIGNAL STRENGTH: High / Medium / Low — how much this should change anyone's plans.
5. ACTION: A concrete next step, or "monitor only."

Rules:
- Lead with the highest-signal items. Ruthlessly cut PR fluff, minor funding noise, and vanity announcements unless they signal a real shift.
- Group related items into themes where it helps.
- Distinguish confirmed facts from rumor/speculation.
- End with a "Quiet but important" section for under-covered items that deserve attention.

Market: {market}
Timeframe: {timeframe}
Our focus areas (optional): {your_priorities}
Sources/news to analyze (optional): {paste_sources}
```

## Output format
- **Top stories** — the 3-5 highest-signal items, full treatment.
- **Themes** — clustered developments with a one-line read each.
- **Quiet but important** — under-the-radar items worth noting.
- **Noise filtered out** — a one-line note on what you ignored and why (keeps it honest).
- **This week's takeaway** — the single most important thing to remember.

## Optional inputs
- Pasted articles, newsletters, or links to ground the briefing.
- Your priority areas, so the "why it matters" is tailored.
- A named competitor set to weight coverage toward.

## Notes
The discipline here is *subtraction* — a good briefing leaves most news out. The "noise filtered out" line keeps the model honest about what it skipped. Doing this every day across many sources is tedious by hand; tools like [IntelCue](https://www.intelcue.ai) continuously ingest news, newsletters, and feeds and assemble the briefing for you. For a publication-style version, see the [weekly market brief](../agents/weekly-market-brief.md) agent.
