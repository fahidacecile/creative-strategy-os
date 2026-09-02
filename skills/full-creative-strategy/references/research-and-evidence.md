# Research and evidence protocol

Use this reference during the research phase of Full Creative Strategy.

## Source hierarchy

### Brand truth

Use official brand and product pages for factual brand-controlled information: product details, offer, pricing, guarantees, positioning, brand voice, visual system, claims, and legal language. Label all of it `brand-owned`.

### Customer truth

Prioritize independent sources such as G2, Capterra, Trustpilot, Amazon, retail reviews, Reddit, specialist forums, YouTube comments, and TikTok comments. Brand-site testimonials may inform brand messaging, but they do not count as independent customer proof.

### Competitive and advertising truth

Use direct competitor sites, public ad libraries, landing pages, creator partnerships, review platforms, and credible category sources. A visible ad proves only that the creative was observed. It does not prove spend, performance, strategic priority, or profitability.

## Research order

1. Confirm brand, product, market, price, offer, and channel scope.
2. Map the category and identify five direct competitors by product use case, customer, and buying alternative. Keep adjacent comparators separate.
3. Research independent customer language before generating personas.
4. Inspect visible advertising for the brand and competitors.
5. Synthesize patterns, contradictions, missing evidence, and open questions.

## Dynamic customer-language sample

Target 300-500 usable verbatims for a full strategy when the category has enough accessible evidence. Determine the stopping point dynamically:

- Continue until each priority segment and major polarity has coverage.
- Continue while new pain, desire, objection, trigger, identity, or proof themes are still appearing.
- Stop after two consecutive collection blocks add no material theme and do not change the ranking of the leading themes.
- Stop at 500 unless the user expands scope.
- If fewer than 300 independent verbatims are accessible, use the available evidence, state the shortfall, lower confidence, and never pad the dataset with brand-owned or invented content.

Deduplicate reposts, copied reviews, syndicated text, and near-identical comments. Keep exact customer wording in short excerpts and respect source quotation limits.

## What to capture

For every usable customer item, capture:

| Field | Meaning |
| --- | --- |
| `evidence_id` | Stable local identifier |
| `source_type` | Review platform, forum, social comment, video comment, press, brand page, ad library |
| `source_url` | Direct URL |
| `observed_at` | Date of collection |
| `market` | Geography or `unknown` |
| `product` | Product or plan mentioned |
| `rating_or_polarity` | Rating where available; otherwise positive, mixed, negative, or neutral |
| `verbatim` | Short exact excerpt |
| `theme` | Pain, desire, objection, trigger, identity, use case, proof, competitor, outcome |
| `persona_signal` | Who appears to be speaking; `unknown` if unsupported |
| `strength` | Strong, medium, or weak |
| `confidence` | 1-5 with rationale |
| `notes` | Context, contradiction, duplication, or legal concern |

Never infer demographics from a name or photograph alone. Prefer self-described identity, context, use case, or explicit product need.

## Advertising sample

For the target brand, inspect active ads and ads stopped within the last 90 days when the platform makes them accessible. Analyze up to 100 ads. If more exist, create a balanced sample across age, status, format, angle, persona, and landing page.

Capture:

- Ad or library identifier and URL
- Observation date and visible status
- First-seen date when available
- Persona represented or addressed
- Awareness state and funnel job
- Strategic angle and hook archetype
- Macro and micro format
- Proof type and claim
- Creator or partnership signal
- CTA and destination
- Similarity to other sampled creatives as a qualitative observation

For JavaScript-rendered libraries, use an interactive browser when available. If the library is blocked, explicitly mark ad evidence unavailable and continue only with sources that were actually inspected.

## Research synthesis

Produce these sections before ideation:

1. Customer reality: contexts, micro-moments, language, emotions, and identity signals
2. Brand reality: offer, assets, constraints, objectives, and current claims
3. Category reality: conventions, dominant claims, proof, formats, and saturation
4. Market psychography: jobs, drivers, beliefs, anxieties, and trade-offs
5. Buyer sentiment: pains, desires, triggers, objections, and outcomes
6. Market sophistication: what customers already know and what proof they require
7. Objection map: cluster, root cause, supporting evidence, and response path
8. Proof stack: available proof, missing proof, and claim boundaries
9. Creative opportunity: underused personas, awareness states, angles, formats, and creator representations
10. Contradictions and limitations

## Traceability rules

- Give every evidence item an ID.
- Cite evidence IDs beside each material insight.
- Label inferences as inferences.
- Use `not observed` instead of `does not exist`.
- Use `estimated from the visible sample` for calculated advertising distributions.
- Do not turn frequency or duration into a performance claim.
- Record what would change the conclusion.
