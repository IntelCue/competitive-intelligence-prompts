# LinkedIn Monitoring

## Goal
Turn a competitor's (or an executive's) LinkedIn activity into intelligence: what they're announcing, how they're positioning, what's resonating, and what it signals about their strategy.

## Best for
Tracking competitor go-to-market moves, executive narratives, hiring signals, and content that's working in your category.

## Prompt
```text
You are a social intelligence analyst. Analyze the recent LinkedIn activity of {target} (a {company_or_person}) over the {timeframe}.

From the posts, articles, and activity I provide (or that you can access), extract:

1. THEMES: The 3-5 recurring themes in their posting. What narrative are they building?
2. ANNOUNCEMENTS: Any product launches, hires, partnerships, funding, events, or milestones — with dates.
3. POSITIONING SIGNALS: How they talk about their category, their customers, and (implicitly or explicitly) their competitors.
4. WHAT'S RESONATING: Which posts got outsized engagement and why — the format, hook, and topic. What does this teach about the audience?
5. HIRING & EXPANSION SIGNALS: Any clues about new roles, teams, markets, or initiatives (from posts or "we're hiring" activity).
6. TONE: Confident, defensive, experimental, pivoting? What's the subtext?

Then summarize: the single most important signal from this activity for {your_company}.

Rules: Quote real posts where possible. Separate what's stated from what you infer. Don't fabricate engagement numbers — describe relative reach only if you can observe it.

Target: {target}
Timeframe: {timeframe}
Posts/activity (optional): {paste_content}
Our perspective: {your_company}
```

## Output format
- **Narrative themes** — what they're consistently pushing.
- **Announcements log** — dated list of concrete moves.
- **Positioning signals** — how they frame the market and rivals.
- **What's resonating** — top-performing posts and the lesson.
- **Hiring/expansion signals** — clues about where they're growing.
- **Top signal** — the one thing that matters most for you.

## Optional inputs
- Pasted posts or a profile activity export (most reliable input).
- A list of executives to track, not just the company page.
- Your own positioning, to sharpen the "so what."

## Notes
LinkedIn is one of the most honest competitive signals available — companies announce moves there before anywhere else, and execs reveal strategy in "thought leadership." Respect LinkedIn's terms of service and privacy: work from public posts, and don't scrape in ways that violate the platform's rules. Continuously watching multiple profiles by hand is impractical; [IntelCue](https://www.intelcue.ai) monitors LinkedIn (and other sources) for you and surfaces the signals. Combine with [messaging analysis](../competitor-analysis/messaging-analysis.md) for a full positioning picture.
