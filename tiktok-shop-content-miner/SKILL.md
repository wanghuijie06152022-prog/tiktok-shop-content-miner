---
name: tiktok-shop-content-miner
description: Mine GMV-ranked TikTok Shop content case libraries, extract evidence-backed creative templates, and turn them into photo-carousel briefs, concepts, storyboards, image directions, copy, and publishing plans. Use for TikTok Shop content research, case teardown, Black Friday or gifting campaigns, and product-specific creative production. Do not use for generic social copy that does not need case evidence.
---

# TikTok Shop Content Miner

Use the case library as evidence, not decoration. First build a compact learning pack from relevant GMV-performing cases; only then create new content.

## Live case sources

These two source views are maintained continuously. At the start of each case-mining request, open the live view and read its current records rather than relying on a previously copied snapshot:

1. **日用家纺行业专属榜单** — prioritize for home textiles, home goods and kitchen cases, including first-screen copy hooks, lifestyle/atmosphere, feature demonstration and before/after proof:
   `https://bytedance.sg.larkoffice.com/base/HItOb9EmmarvbjsdvbTlPkQHgHb?table=tblHzigDo2GfiEgK&view=vewUg1CAvT`
2. **全品类优质图文榜单（持续更新）** — use for adjacent categories, new cases and transferable creative mechanisms:
   `https://bytedance.sg.larkoffice.com/base/YrsUb0baMa6OpRsSdXxl01wLgWh?table=tbl5onwbm2IeHpPV&view=vewUCAwef1`

The links point to live views, so later updates by the maintainer are available on the next invocation without republishing the skill. The skill does not perform background synchronization or cache the source records. Access still depends on the current user's account permissions. If access is blocked, ask for an authorized Excel/CSV export or pasted filtered view and do not claim to have analyzed inaccessible rows.

If no cases are available, explain that evidence-backed mining cannot yet be completed. Product briefing may proceed from verified product facts at the user's request; do not claim the AI has learned inaccessible examples.

For daily home-textile requests, search the industry-specific library first, then use the general library to add fresh or cross-category mechanisms. For other industries, start with the general library. When combining results, keep the source and GMV evidence attached to every case and do not merge duplicate records as independent evidence.

Treat both libraries as read-only unless the user explicitly asks to edit them.

## Route the request

1. For research, diagnosis, pattern extraction, or benchmarks, read [references/case-mining.md](references/case-mining.md).
2. To create or revise a carousel, campaign, or product content plan, first mine cases, then read [references/creation-workflow.md](references/creation-workflow.md).
3. When reusable prompts are useful, read [references/prompt-library.md](references/prompt-library.md) and adapt them to the product.

## Required sequence

### 1. Define the retrieval question

Translate the request into filters: market/campaign, category/product, price band, content type, GMV range or threshold, audience/occasion, and requested output. Content types include first-screen copy hook, lifestyle/atmosphere, feature demonstration, and before/after proof.

If no GMV threshold is given, start with the strongest available GMV tier and include a small contrast set from the next tier. State the assumption.

### 2. Build an evidence pack before ideation

Retrieve the most relevant cases and capture the fields needed to explain performance. Prefer 8–20 highly relevant cases over a large mixed dump. Include outliers only when they teach a distinct mechanism.

Separate observed facts from interpretation. Never infer GMV, discounts, product claims, or causality that the source does not support.

### 3. Distill mechanisms, not surface styling

Normalize each case into `HOOK → BODY → CTA`. Extract audience trigger, problem framing, proof order, product reveal timing, trust device, purchase reason, and urgency.

Do not copy brand assets, creator identity, exact long-form wording, or unsupported claims. Do not treat correlation with GMV as proof of causation.

### 4. Create only after learning is explicit

Before generating concepts, summarize what wins, which evidence supports it, which structures are reusable, what should not be copied, and what product facts still need confirmation.

Then execute the creation workflow. Keep each recommendation traceable to a case pattern or verified product fact.

## Output standard

A strong response normally contains:

1. Retrieval scope and assumptions.
2. Selected benchmark cases with GMV evidence.
3. Pattern matrix across HOOK, BODY, proof, CTA, and production style.
4. Three to six reusable templates with applicability boundaries.
5. Recommended direction and reasons.
6. The requested artifact: brief, concepts, storyboard, image prompts, copy, hashtags, BGM direction, or diagnosis.
7. Unknowns and claims requiring confirmation.

For diagnosis, map problems to the funnel: stop/hold → swipe/engagement → product click → conversion. A beautiful image is not evidence of a strong selling mechanism.
