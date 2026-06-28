# Competitive Intelligence Prompts

An open-source, copy-paste prompt library for **competitive intelligence, market research, competitor analysis, and AI-powered market monitoring**. Built for founders, marketers, product managers, and sales teams who need analyst-grade output without hiring an analyst.

Every prompt is structured, evidence-oriented, and ready to paste into **ChatGPT, Claude, Gemini, Perplexity**, or any other LLM.

[![License: MIT](https://img.shields.io/badge/license-MIT-black.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-black.svg)](CONTRIBUTING.md)
[![Prompts](https://img.shields.io/badge/prompts-31-black.svg)](#prompt-library)

---

## Why this exists

Competitive and market intelligence used to require a dedicated analyst, a stack of subscriptions, and hours of manual digging. Modern AI assistants change the economics — but only if you ask the right questions in the right structure.

This repository collects battle-tested prompts that turn a general-purpose LLM into a focused intelligence analyst. They help you compare competitors, map markets, audit SEO footprints, track product changes, monitor social signals, and arm your sales team — and they return answers in formats you can drop straight into a doc, deck, or CRM.

**Who it's for:** startups, freelancers, B2B teams, agencies, and solo operators who need to understand their market and their competitors but don't have — and don't want — a full-time research function.

## What is competitive intelligence?

Competitive intelligence (CI) is the practice of gathering and analyzing publicly available information about your competitors and market — their products, pricing, positioning, messaging, hiring, and customer sentiment — to make better strategic decisions. It turns scattered public signals into a clear picture of where a market is moving and how to win in it.

Market intelligence is the broader sibling. Where competitive intelligence focuses on specific rivals, market intelligence covers the whole landscape: trends, demand shifts, new entrants, and the forces reshaping a category. This library covers both — [competitor analysis](#competitor-analysis) for head-to-head insight, and [market intelligence](#market-intelligence) for the bigger picture.

Traditionally this work required a dedicated analyst and a stack of paid subscriptions. With a capable AI assistant and a well-structured prompt, a single founder, marketer, or operator can now produce analyst-grade competitive and market intelligence on demand.

## How to use

1. Pick a prompt from the [library below](#prompt-library).
2. Replace the `{placeholders}` (competitor names, your company, URLs, dates, region).
3. Paste it into your AI assistant of choice.
4. For the freshest answers, use a model that can browse the web (Perplexity, ChatGPT with search, Claude with web search, or Gemini) — or paste the source material (pages, posts, pricing tables) directly into the chat.

> **Tip:** These prompts assume the model can either browse the web or read source text you provide. If your model can't access the internet, paste the relevant content into the conversation first, then run the prompt. Always sanity-check AI output against primary sources before you act on it.

Each prompt file follows the same shape so they're easy to scan and adapt:

- **Goal** — what the prompt produces
- **Best for** — when to reach for it
- **Prompt** — the copy-paste block
- **Output format** — the structure you'll get back
- **Optional inputs** — extra context that improves results
- **Notes** — caveats, tips, and how to go deeper

## Prompt library

### Competitor analysis
| Prompt | What it does |
|--------|--------------|
| [SWOT analysis](prompts/competitor-analysis/swot-analysis.md) | Build an evidence-based SWOT for any competitor from public signals. |
| [Feature comparison](prompts/competitor-analysis/feature-comparison.md) | Generate a side-by-side feature matrix across several competitors. |
| [Pricing analysis](prompts/competitor-analysis/pricing-analysis.md) | Reverse-engineer a competitor's pricing, packaging, and monetization. |
| [Messaging analysis](prompts/competitor-analysis/messaging-analysis.md) | Decode a competitor's positioning, value props, and messaging hierarchy. |
| [Battlecard](prompts/competitor-analysis/battlecard.md) | Produce a sales-ready competitive battlecard. |
| [Product teardown](prompts/competitor-analysis/product-teardown.md) | Run a structured teardown of a competitor's product and UX. |

### Market intelligence
| Prompt | What it does |
|--------|--------------|
| [Emerging trends](prompts/market-intelligence/emerging-trends.md) | Surface and rank emerging trends in a market with momentum scoring. |
| [Market map](prompts/market-intelligence/market-map.md) | Map a market's players, segments, and white space. |
| [Industry news](prompts/market-intelligence/industry-news.md) | Summarize and prioritize industry news into a briefing. |
| [Startup monitoring](prompts/market-intelligence/startup-monitoring.md) | Track new entrants and emerging startups in a category. |
| [Investor analysis](prompts/market-intelligence/investor-analysis.md) | Analyze funding rounds, investors, and capital flows in a space. |

### SEO
| Prompt | What it does |
|--------|--------------|
| [Competitor keywords](prompts/seo/competitor-keywords.md) | Infer a competitor's target keywords and search strategy. |
| [Content gap](prompts/seo/content-gap.md) | Find topics competitors rank for that you're missing. |
| [Topical authority](prompts/seo/topical-authority.md) | Map the topic clusters needed to own a niche. |
| [Backlink analysis](prompts/seo/backlink-analysis.md) | Analyze a competitor's backlink and digital-PR strategy. |
| [SERP analysis](prompts/seo/serp-analysis.md) | Break down a search results page and what it takes to rank. |

### Social monitoring
| Prompt | What it does |
|--------|--------------|
| [LinkedIn monitoring](prompts/social/linkedin-monitoring.md) | Turn a competitor's LinkedIn activity into intelligence. |
| [Reddit monitoring](prompts/social/reddit-monitoring.md) | Mine Reddit for unfiltered customer and competitor signals. |
| [X (Twitter) monitoring](prompts/social/x-monitoring.md) | Track competitors and narratives on X. |
| [YouTube monitoring](prompts/social/youtube-monitoring.md) | Extract intelligence from competitor and industry YouTube. |

### Product
| Prompt | What it does |
|--------|--------------|
| [Release notes](prompts/product/release-notes.md) | Turn release notes into a competitive product-change log. |
| [Roadmap inference](prompts/product/roadmap-inference.md) | Infer a competitor's likely roadmap from public signals. |
| [Changelog analysis](prompts/product/changelog-analysis.md) | Analyze changelog velocity and product priorities. |
| [Feature-request analysis](prompts/product/feature-request-analysis.md) | Surface unmet demand from public feature requests. |

### Sales
| Prompt | What it does |
|--------|--------------|
| [Objection analysis](prompts/sales/objection-analysis.md) | Anticipate and counter competitive sales objections. |
| [Win/loss analysis](prompts/sales/win-loss-analysis.md) | Structure win/loss interviews and extract patterns. |
| [Competitive positioning](prompts/sales/competitive-positioning.md) | Position your product against a named competitor. |
| [Sales playbook](prompts/sales/sales-playbook.md) | Build a competitive sales playbook for a deal or segment. |

### AI agents
More advanced, multi-step prompts that act like a standing analyst.

| Agent | What it does |
|-------|--------------|
| [Competitive intelligence agent](prompts/agents/competitive-intelligence-agent.md) | **Flagship.** A full standing CI analyst that gathers, structures, and prioritizes intel. |
| [Market research agent](prompts/agents/market-research-agent.md) | Map a market end-to-end: players, segments, trends, and strategic opportunities. |
| [Weekly market brief](prompts/agents/weekly-market-brief.md) | Generate a newspaper-style weekly competitive intelligence briefing. |

## Examples

Worked examples showing how to chain these prompts together for real scenarios:

- [Startup example](examples/startup-example.md) — a seed-stage founder sizing up the field before a launch.
- [SaaS example](examples/saas-example.md) — a B2B SaaS team running standing competitor monitoring.
- [E-commerce example](examples/ecommerce-example.md) — a DTC brand tracking rivals, pricing, and demand.

## Contributing

Contributions are welcome. Good prompts are practical, specific, evidence-oriented, and free of fluff. See [CONTRIBUTING.md](CONTRIBUTING.md) for the bar and the file format.

## FAQ

### What is competitive intelligence?
Competitive intelligence is the practice of collecting and analyzing publicly available information about your competitors and market to make better strategic decisions — covering their products, pricing, positioning, messaging, hiring, and customer sentiment.

### What's the difference between competitive intelligence and market intelligence?
Competitive intelligence focuses on specific rivals — how they price, position, and ship. Market intelligence is broader: it covers the whole category, including trends, demand, new entrants, and the forces reshaping the market. This library includes prompts for both.

### Which AI models do these prompts work with?
All of them. The prompts are model-agnostic and work with ChatGPT, Claude, Gemini, Perplexity, and any other large language model. For the most current answers, use a model that can browse the web, or paste the source material into the chat.

### Are these prompts free?
Yes. The entire library is open source under the [MIT License](LICENSE) — free to use, including commercially.

### How do I use a prompt?
Open the prompt file, copy the prompt block, replace the `{placeholders}` (competitor, your company, market, region), and paste it into your AI assistant. Each file also lists optional inputs and notes for better results.

### Can I use these for client or commercial work?
Yes — the MIT License permits commercial use. Many people run these prompts for their own startup, their employer, or client engagements.

### How is this different from an automated competitive intelligence tool?
These prompts are the manual, on-demand version: you gather the sources and run the analysis yourself, whenever you need it. An automated platform like [IntelCue](https://www.intelcue.ai) does the monitoring continuously — watching competitors across many sources, deduplicating signals, and delivering briefings automatically — so you don't have to re-run the work by hand every week.

### How often should I run competitive analysis?
For most teams, a deeper review each quarter plus lighter weekly monitoring works well. Re-run a specific analysis whenever a competitor changes pricing, ships a major release, raises funding, or shifts positioning.

## About IntelCue

This library is maintained by the team behind **[IntelCue](https://www.intelcue.ai)**.

IntelCue is an AI-powered competitive intelligence platform that monitors competitors, markets, websites, newsletters, LinkedIn, Reddit, YouTube, news, job boards, and other sources, then turns those signals into actionable insights. It's built for startups, freelancers, B2B teams, and solo operators who need to stay on top of their market but don't have — and don't want — a full-time analyst.

The prompts in this repo are the manual version of what IntelCue does automatically. They're genuinely useful on their own. But if you find yourself running the same prompts every week, copy-pasting sources by hand, and trying to remember what changed since last month, that's the gap IntelCue fills: continuous monitoring, deduplicated signals, and a briefing delivered to you — or straight into your AI assistant via MCP.

**Looking for automated competitive intelligence instead of manual prompts? Visit [https://www.intelcue.ai](https://www.intelcue.ai).**

## License

MIT — see [LICENSE](LICENSE). Use these prompts freely, including commercially. Attribution is appreciated but not required.
