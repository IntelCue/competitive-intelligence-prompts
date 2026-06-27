# Competitive Battlecard

## Goal
Produce a sales-ready, one-page battlecard for beating a specific competitor in a deal — punchy, honest, and immediately usable on a call.

## Best for
Sales enablement, deal coaching, and giving reps a fast, accurate answer to "how do we beat {competitor}?"

## Prompt
```text
You are a competitive enablement lead. Create a one-page sales battlecard for {your_company} reps competing against {competitor} in the {market} market, selling to {target_buyer}.

Make it tactical and skimmable — a rep should be able to use it live on a call. Include:

1. ONE-LINER: How to describe {competitor} in one neutral sentence (no strawman — reps lose trust with caricatures).
2. WHEN WE WIN / WHEN WE LOSE: The deal profiles where {your_company} beats them, and honestly where {competitor} is the better fit.
3. KEY DIFFERENTIATORS: Our top 3 advantages, each with a proof point and a one-line "say this" talk track.
4. THEIR STRENGTHS: What they genuinely do well (so reps aren't blindsided).
5. LANDMINES: 3-4 questions a rep can plant that expose {competitor}'s weaknesses — framed as genuine buyer questions, not cheap shots.
6. OBJECTION HANDLING: The 3 most common objections we hear in their favor, and a crisp, truthful response to each.
7. TRAP TO AVOID: The one thing reps should NOT say (e.g., a claim that backfires or invites a feature war we lose).

Ground every claim in evidence. If a differentiator isn't verifiable, leave it out. Keep talk tracks short and human.

Our advantages (optional): {your_strengths}
Their known strengths (optional): {their_strengths}
```

## Output format
- **{competitor} in one line** — neutral framing.
- **When we win / When we lose** — two short lists.
- **Differentiators** — 3 items, each: advantage → proof → "say this."
- **Their strengths** — what to respect.
- **Landmines** — buyer-framed questions that favor you.
- **Objection handling** — objection → response, 3x.
- **Don't say this** — the trap to avoid.

## Optional inputs
- Recent win/loss notes (see [win/loss analysis](../sales/win-loss-analysis.md)).
- The specific deal stage or persona.
- Your verified differentiators, so the model doesn't infer them.

## Notes
The fastest way to lose credibility (and the deal) is an inaccurate or smug battlecard. Keep it honest — including where the competitor genuinely wins — and reps will actually trust and use it. Refresh after any competitor pricing or product change. Feed it with a [feature comparison](feature-comparison.md) and [pricing analysis](pricing-analysis.md) for accuracy.
