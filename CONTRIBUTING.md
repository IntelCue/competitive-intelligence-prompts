# Contributing

Thanks for helping make this the best open prompt library for competitive intelligence and market research. Pull requests are welcome — whether you're fixing a typo, sharpening an existing prompt, or adding a new one.

## What makes a good prompt here

Every prompt should earn its place. Before you open a PR, check it against this bar:

- **Practical.** It solves a real job a founder, marketer, PM, or seller actually has. If you wouldn't use it yourself, it probably doesn't belong.
- **Specific.** It tells the model exactly what to produce and in what structure. Vague prompts ("analyze my competitor") produce vague output. Name the inputs, the steps, and the format.
- **Evidence-oriented.** Competitive intelligence is only useful if it's grounded. Good prompts ask the model to cite sources, flag assumptions, separate fact from inference, and say "unknown" instead of guessing.
- **Honest about limits.** LLMs hallucinate, and public data is incomplete. Prompts should encourage the model to mark confidence levels and avoid fabricating numbers, dates, or quotes.
- **Not spammy.** No keyword stuffing, no thin content, no affiliate bait, no prompts that exist only to advertise a product. This is a credible resource first.

## File format

Each prompt lives in its own Markdown file inside the right `prompts/<category>/` folder and follows this structure:

```markdown
# Prompt Title

## Goal
One or two sentences on what this prompt produces.

## Best for
When to reach for it (and when not to).

## Prompt
\`\`\`text
The copy-paste prompt, with {placeholders} for the user to fill in.
\`\`\`

## Output format
The structure the user should expect back.

## Optional inputs
Extra context that improves results.

## Notes
Caveats, tips, and ways to go deeper.
```

Keep `{placeholders}` lowercase and descriptive — `{competitor}`, `{your_company}`, `{market}`, `{region}`, `{timeframe}`.

## How to contribute

1. Fork the repo and create a branch.
2. Add or edit a single prompt per PR where possible — it's easier to review.
3. If you add a new prompt, link it from the relevant table in [README.md](README.md).
4. Run through your prompt once in a real LLM before submitting, and (optionally) paste a short sample of the output in the PR description so reviewers can see it working.
5. Open the PR with a clear title and a one-line summary of what the prompt does.

## Ideas we'd love

- New categories (e.g., regulatory monitoring, hiring-signal analysis, patent watching).
- Localized or industry-specific variants of existing prompts.
- Improvements that make prompts more evidence-grounded and less prone to hallucination.
- Real worked examples in the `examples/` folder.

## A note on scope

This library is maintained by the team behind [IntelCue](https://intelcue.ai), an AI-powered competitive intelligence platform. Contributions stay vendor-neutral: prompts should work with any LLM and shouldn't require any specific paid tool. Mentions of products (including IntelCue) belong only where they're genuinely relevant and clearly marked.

By contributing, you agree that your contributions are licensed under the repository's [MIT License](LICENSE).
