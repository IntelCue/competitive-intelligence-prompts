# Product Teardown

## Goal
Run a structured teardown of a competitor's product — its core flows, UX, onboarding, depth, and the strategy revealed by what they chose to build (and not build).

## Best for
Product and design teams, founders evaluating a category, and anyone who needs to understand a rival's product beyond the marketing site.

## Prompt
```text
You are a product strategist conducting a teardown of {competitor}'s product in the {market} category.

Work from their product pages, docs, demo videos, screenshots, app store listings, reviews, and (if available) a hands-on trial. Then assess:

1. CORE JOB: What is the product fundamentally for? What's the primary use case it nails?
2. KEY FLOWS: Walk through the 3-4 most important user flows (e.g., setup, the core action, getting value, inviting a team). Note friction and delight in each.
3. ONBOARDING: How fast is time-to-value? Self-serve or sales-led? What's the activation moment?
4. DEPTH vs. BREADTH: Are they deep in a narrow use case or broad and shallow? Where's the product's center of gravity?
5. UX & DESIGN: Overall quality, opinionatedness, and who it's clearly designed for.
6. AI / AUTOMATION: How (if at all) do they use AI? Is it core or bolted on?
7. STRATEGY REVEALED: What does the build prioritization tell you about their strategy and roadmap?
8. GAPS: What's conspicuously missing, clunky, or underbaked?

For each section, separate what you OBSERVED from what you're INFERRING. Note where a hands-on trial would be needed to confirm.

Competitor: {competitor}
Product/docs URL: {product_url}
```

## Output format
- **Product snapshot** — core job and primary use case.
- **Flow-by-flow notes** — friction/delight per key flow.
- **Onboarding & time-to-value** — activation path and speed.
- **Depth vs. breadth** — center of gravity.
- **UX assessment** — quality and intended user.
- **AI usage** — core vs. cosmetic.
- **Strategy read** — what the build reveals.
- **Gaps & openings** — where a challenger can win.

## Optional inputs
- A trial account or recorded demo for first-hand observation.
- Review excerpts (G2/Capterra/App Store) for real-user friction points.
- The specific flow you care most about (e.g., onboarding only).

## Notes
A teardown from marketing pages alone is shallow — get into the docs, demo videos, and ideally a trial. Reviews are gold for finding the friction users actually hit. Pair with [roadmap inference](../product/roadmap-inference.md) to turn "what they built" into "what they'll build next."
