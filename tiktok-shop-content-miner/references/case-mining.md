# Case-library mining

## Goal

Turn GMV-ranked examples into a compact evidence pack that teaches the model which selling mechanisms apply to the current product.

## Retrieval procedure

1. Choose sources before filtering:
   - For 日用家纺 and close home/kitchen categories, begin with the industry-specific library and supplement from the general library.
   - For other industries or broad discovery, begin with the general library.
   - Use both when the user requests a comprehensive benchmark or when the primary source has too few close analogues.
2. Inspect the current table/view schema. Identify exact fields for GMV, category, product, content type, creator/link, date, market, media, and notes. Field names may change.
3. In the general library, use available dimensions such as 所属行业, 一级/二级/三级类目, 商品名称, 商品类型, 内容分型, 图文亮点, 创建日期, 是否AI, 视频链接, and media preview. Do not assume every view exposes every field.
4. Apply the user's constraints. Rank by the most relevant GMV metric; do not silently substitute views, likes, or engagement. If a selected general-library view contains no GMV field, state that limitation and use it for structural inspiration rather than calling it GMV-ranked evidence.
5. Select 5–10 close high-GMV analogues, 2–5 adjacent-category cases with transferable mechanisms, and optionally 2–3 lower-tier contrast cases for diagnosis.
6. Inspect the actual carousel/video when available. Titles and thumbnails alone are insufficient.
7. De-duplicate cases found in both sources by video link, product, or matching creative. Preserve source provenance.
8. Record missing or ambiguous fields instead of guessing.

## Case card

Capture product/category, GMV metric and value, price/promotion if present, audience/occasion, first-screen hook and visual device, product reveal position, BODY sequence, proof type, CTA/urgency, asset style, transferable mechanism, and applicability boundary.

## Pattern matrix

| Dimension | What to extract |
|---|---|
| Audience trigger | identity, pain, aspiration, relationship, occasion |
| Hook | curiosity, POV, dialogue, meme, warning, result, price |
| First-frame clarity | how quickly the product is understood |
| Story arc | problem/solution, reveal, list, transformation, gift story |
| Proof | what reduces doubt and when it appears |
| Product integration | reveal timing, visibility, action, accuracy |
| Purchase reason | functional, emotional, value, gifting, urgency |
| CTA | direct, scarcity, promotion, replacement, soft click |
| Production | real/AI mix, composition, text density, continuity |

## Synthesis rules

- Label direct facts `Observed` and strategic readings `Inference`.
- A repeated pattern is a candidate template, not a universal rule.
- Weight relevance before raw GMV; a close analogue can teach more than a distant viral winner.
- Separate attention mechanisms from conversion mechanisms.
- Note survivorship bias: a winners library lacks the denominator of failed attempts.

## Learning-pack output

Produce 5–10 findings, a named HOOK → BODY → CTA template library, a product/price/audience fit map, an avoid list, and open facts needed from the merchant. Feed this normalized synthesis into creation instead of dumping all raw cases.
