# Example: DTC E-commerce Brand Tracking Rivals, Pricing, and Demand

A worked example of using these prompts in an e-commerce / direct-to-consumer context, where the competitive signals are pricing, product drops, ads, search demand, and customer sentiment.

## The scenario

**Tidewell** is a DTC brand selling sustainable home-cleaning refills by subscription. The category is heating up — two well-funded rivals and a flood of smaller entrants. **Priya**, who runs growth, needs to keep pace on pricing, spot new competitors early, and find content that actually ranks. No research team; one capable AI assistant.

Here's how she uses this library.

## Step 1 — Map the competitive set and entrants

Priya starts with the [market map](../prompts/market-intelligence/market-map.md) prompt to place the players on two axes (subscription ↔ one-time, eco-premium ↔ value), then runs [startup monitoring](../prompts/market-intelligence/startup-monitoring.md) to catch new entrants. The monitoring prompt surfaces two newcomers she hadn't seen — one undercutting on price, one going premium with refillable glass. She tags both to watch.

## Step 2 — Decode competitor pricing and packaging

Pricing is the daily battleground, so she runs the [pricing analysis](../prompts/competitor-analysis/pricing-analysis.md) prompt on her two main rivals.

The analysis reveals one rival's "subscribe and save" gate: the discount only kicks in at a 3-product bundle, nudging cart size. The other anchors with a pricey "starter kit" to make the refills feel cheap. Priya realizes Tidewell's single-product entry point looks expensive by comparison — a packaging problem she can fix.

## Step 3 — Mine real customer sentiment

She runs the [Reddit monitoring](../prompts/social/reddit-monitoring.md) prompt across r/ZeroWaste and sustainability threads, plus the [YouTube monitoring](../prompts/social/youtube-monitoring.md) prompt on the "honest review" videos that drive a lot of DTC consideration.

Two signals jump out: shoppers love her rival's scent options but complain the bottles leak in transit, and reviewers repeatedly praise *refill clarity* — knowing exactly when and what will ship. The leak complaint is a wedge; the "refill clarity" praise tells her what to emphasize.

## Step 4 — Win the search and content game

DTC lives and dies on discovery, so Priya runs the [content gap](../prompts/seo/content-gap.md) and [SERP analysis](../prompts/seo/serp-analysis.md) prompts.

The content gap shows competitors ranking for "how to reduce plastic in the kitchen" and "are cleaning refills worth it" — high-intent comparison queries Tidewell ignores. The SERP analysis for "best eco cleaning subscription" reveals the page that ranks is a listicle, so a product page won't win — she needs an honest comparison piece (where she can use her leak-resistance advantage). She maps it all into a cluster with the [topical authority](../prompts/seo/topical-authority.md) prompt.

## Step 5 — Track ad and messaging moves

Finally, she runs the [messaging analysis](../prompts/competitor-analysis/messaging-analysis.md) prompt on competitor homepages and landing pages to see how they frame value. Everyone leads with "sustainable"; nobody owns "never run out, never leak." That becomes Tidewell's angle.

## The result

In a focused week, Priya gathered: two new competitors to watch, a packaging fix for her entry price, a product wedge (leak-resistance), the exact high-intent content to publish, and a differentiated message — all from public signals and a handful of prompts.

## The part that never stops

E-commerce competition is relentless: prices change weekly, rivals run new product drops and ad campaigns constantly, and a new entrant can appear overnight. Re-running these prompts by hand every week isn't realistic for a one-person growth team. The always-on layer — *watch competitor pricing pages, new product launches, ad activity, and review sentiment, and tell me the moment something shifts* — is what Priya offloads to a continuous monitoring platform like [IntelCue](https://www.intelcue.ai). She lets it do the watching, and uses the prompts here for the deep analysis whenever a signal is worth a closer look.
