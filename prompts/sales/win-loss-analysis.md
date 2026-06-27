# Win/Loss Analysis

## Goal
Structure win/loss interviews and synthesize the results into patterns — why you really win and lose, against whom, and what to change.

## Best for
Sales and product leaders who want the truth about deal outcomes instead of the rep's after-the-fact narrative.

## Prompt
```text
You are a win/loss analyst. Help {your_company} run rigorous win/loss analysis for deals in the {market} market.

PART A — Interview guide:
Produce a neutral, non-leading interview guide (10-12 questions) to use with won and lost prospects. Cover: their buying process, the alternatives they evaluated, the decision criteria and how we/competitors scored, the moment they decided, the role of price, and what would have changed the outcome. Phrase questions so they don't lead the witness or let the buyer just flatter us.

PART B — Synthesis:
Given the interview notes / deal data I provide, synthesize:
1. WIN REASONS: The real, recurring reasons we win (not the reasons reps claim).
2. LOSS REASONS: The recurring reasons we lose, by category (product, price, process, perception, timing).
3. BY COMPETITOR: Against whom we win and lose, and the deciding factor each time.
4. DECISION CRITERIA: What buyers actually weight most — vs. what we assume.
5. INFLECTION MOMENTS: Where deals are won or lost in the cycle.
6. FIX LIST: The highest-leverage changes to product, pricing, messaging, or process — ranked by impact.

Rules: Separate evidence (what buyers said) from interpretation. Watch for self-serving narratives ("we lost on price" often hides a value-communication problem). Quote buyers where possible.

Market: {market}
Competitors: {competitors}
Interview notes / deal data (optional): {paste_data}
```

## Output format
- **Interview guide** — 10-12 neutral questions (Part A).
- **Win reasons** — recurring, evidence-based.
- **Loss reasons** — by category, with frequency.
- **Competitor breakdown** — win/loss and deciding factor per rival.
- **True decision criteria** — what buyers actually weight.
- **Inflection moments** — where deals turn.
- **Ranked fix list** — the changes that would move the win rate most.

## Optional inputs
- Anonymized interview transcripts or CRM closed-deal data.
- The competitor set to segment by.
- A specific segment or deal size to focus on.

## Notes
"We lost on price" is the most over-reported and least accurate loss reason — push the analysis to find the value-communication or fit problem hiding behind it. The interview guide's neutrality is essential; leading questions produce flattering, useless data. Feed findings into [objection analysis](objection-analysis.md), [competitive positioning](competitive-positioning.md), and the [battlecard](../competitor-analysis/battlecard.md).
