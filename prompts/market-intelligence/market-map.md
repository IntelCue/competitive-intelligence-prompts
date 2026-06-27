# Market Map

## Goal
Map a market's structure: the players, how they segment, where they cluster, and — most importantly — where the white space is.

## Best for
Entering a new market, fundraising narratives, positioning, and finding underserved segments before competitors do.

## Prompt
```text
You are a market researcher mapping the {market} market in {region}.

Produce a structured market map:

1. SEGMENTATION AXES: Choose the 2 most meaningful axes for this market (e.g., SMB↔Enterprise, Point-solution↔Platform, Self-serve↔Sales-led, Horizontal↔Vertical). Justify the choice.
2. PLAYER INVENTORY: List the notable players you can identify (incumbents, challengers, startups, adjacent entrants). For each: one-line description, apparent segment, and rough stage/size if known.
3. CLUSTERS: Place players into clusters based on the axes. Describe each cluster and who's crowded into it.
4. WHITE SPACE: Identify positions on the map that are underserved or empty. For each, explain why it's open and whether it's open because it's an opportunity or because it's a trap (no demand).
5. CATEGORY DYNAMICS: Is the market consolidating or fragmenting? Are incumbents bundling? Are new entrants unbundling?
6. ENTRY POINTS: If a new or growing company wanted in, the 2-3 most attractive wedges.

Mark each player fact [verified] or [approximate]. Flag where the list is likely incomplete.

Market: {market}
Region: {region}
Our company (optional): {your_company}
```

## Output format
- **Axes & rationale** — the two segmentation dimensions and why.
- **Player inventory** — table: player, description, segment, stage/size.
- **Cluster map** — described textually (and as a 2x2 if useful).
- **White space** — open positions, each labeled opportunity or trap.
- **Category dynamics** — consolidation/fragmentation read.
- **Recommended wedges** — best entry points and why.

## Optional inputs
- Your company, to assess where you fit and where to move.
- A known list of competitors to seed the inventory.
- Analyst reports or a category G2 grid pasted in for grounding.

## Notes
The player inventory is never complete from public data alone — explicitly ask the model to flag gaps and treat the map as a living document. The most valuable output is usually the white-space analysis, but be ruthless about distinguishing a real gap from a dead zone with no demand. Combine with [startup monitoring](startup-monitoring.md) to keep the new-entrant list fresh.
