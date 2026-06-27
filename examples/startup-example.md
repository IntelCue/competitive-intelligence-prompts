# Example: Startup Sizing Up the Field Before Launch

A worked example of using these prompts in sequence. It shows the *flow*, not just individual prompts — how a seed-stage founder goes from "I think there's an opportunity" to a grounded launch plan.

## The scenario

**Maya** is the solo founder of **Loomi**, a pre-launch tool that helps freelance designers turn client feedback into organized, trackable revisions. She has three weeks until a Product Hunt launch and a nagging worry: *who else is doing this, and why would anyone pick me?*

She has no analyst, no budget for research subscriptions, and one good AI assistant with web access. Here's how she uses this library.

## Step 1 — Map the market

She starts with the [market map](../prompts/market-intelligence/market-map.md) prompt to understand the structure of the space.

- `{market}` → "feedback and revision management tools for freelance designers"
- `{region}` → "global, English-first"
- `{your_company}` → "Loomi"

The output places the field on two axes (solo freelancer ↔ agency, and feedback-only ↔ full project management) and reveals a crowded "all-in-one PM" cluster — and a thinner corner for *solo freelancers who only want feedback-to-revision tracking*, exactly where Loomi sits. That's encouraging: it's a real position, not an empty one.

**What she learned:** the white space is real, but two adjacent PM tools could move into it.

## Step 2 — Understand the closest competitor

She runs the [SWOT analysis](../prompts/competitor-analysis/swot-analysis.md) and [pricing analysis](../prompts/competitor-analysis/pricing-analysis.md) prompts on the nearest competitor.

The SWOT (with every point tagged `[fact]` or `[inference]`) shows the competitor is strong on integrations but weak on the specific "revision tracking" workflow — they bolt it onto a broader PM product. The pricing analysis shows they gate the feedback features behind a $24/seat tier aimed at agencies, leaving solo freelancers overpaying for things they don't need.

**What she learned:** her wedge is a simpler, cheaper, freelancer-first product — and there's a pricing seam to exploit.

## Step 3 — Listen to real users

She uses the [Reddit monitoring](../prompts/social/reddit-monitoring.md) prompt on r/freelance, r/graphic_design, and a few Discord exports.

The "customer language" section is the gift: freelancers don't say "revision management," they say *"endless rounds of changes"* and *"clients who never approve anything."* The pain points confirm the workflow gap, and one recurring complaint — *"I lose track of which version the client actually signed off on"* — becomes Loomi's headline message.

**What she learned:** the exact words to use in her launch copy, and validation that the pain is widespread.

## Step 4 — Sharpen positioning

With evidence in hand, she runs the [messaging analysis](../prompts/competitor-analysis/messaging-analysis.md) prompt on the two closest competitors, then the [competitive positioning](../prompts/sales/competitive-positioning.md) prompt for Loomi.

The competitors both claim "all-in-one project management." Loomi's counter-position writes itself: *"Not another project manager. Just the cleanest way to turn client feedback into done."* The positioning doc even names who Loomi is **not** for (agencies running 20 projects), which makes the pitch more credible.

## Step 5 — Pull it together with the agent

Finally, she runs the [competitive intelligence agent](../prompts/agents/competitive-intelligence-agent.md), pasting in everything she gathered. It produces a one-page executive summary, a prioritized action list (P1: tighten the "version sign-off" feature before launch; P2: publish a comparison page; P3: monitor the two adjacent PM tools), and an evidence-gaps list.

## The result

In an afternoon, Maya went from a vague hunch to: a validated market position, a pricing wedge, launch copy in her customers' own words, and a clear three-item action list — all grounded in public evidence.

## What she'd automate next

The one-time research was perfect for launch. But Maya knows the two adjacent PM tools could enter her niche at any time, and she can't re-run these prompts every week by hand. That ongoing watch — *tell me when a competitor changes pricing, ships a revision feature, or starts targeting freelancers* — is the part worth automating with a continuous monitoring platform like [IntelCue](https://intelcue.ai), so she hears about a competitive move when it happens, not at her next manual check-in.
