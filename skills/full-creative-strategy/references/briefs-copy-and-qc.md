# Briefs, copy, and quality control

Use this reference after concepts pass the diversity gate.

## Brand Spec Card

Document official capitalization, logo use, typography, color palette, photography and motion direction, CTA conventions, three to five voice attributes, banned language, claim boundaries, and visual `do`/`never` rules.

## Copy Masterfile

For each concept, extract only the writing inputs:

- Persona and customer-language evidence
- Awareness state and funnel job
- Pain, desire, objection, and trigger
- Single strategic angle
- Target emotion
- Promise and proof path
- Brand voice and banned language
- Format and channel
- Valid performance reference, only if first-party data was provided

## Brief types

### New concept

Use for a net-new angle or creative territory. Include persona, awareness, funnel job, angle, emotion, message, proof, hook options, format, visual direction, CTA, production notes, hypothesis, and metric.

### Iteration

Use only when a real reference creative and performance signal exist. State what stays fixed, what changes, why, and how the result will be compared.

### Creator-ready UGC

Include creator profile, representation requirement, setting, prop/product requirements, delivery tone, shot guidance, hook options, talking points, objection handling, prohibited claims, CTA, and edit notes. Do not script fake personal experience.

## Copy rules

- One primary argument per ad.
- Match the hook to persona, awareness, and funnel job.
- Use short, natural sentences and concrete situations.
- Prefer exact customer language when legally and ethically reusable.
- Remove generic AI language and inflated claims.
- Never invent statistics, testimonials, awards, scarcity, guarantees, or results.
- Keep medical, financial, comparative, and performance claims within verified proof.
- Do not treat a round number as more credible merely because it is specific.

For video, a useful six-block flow is: hook, problem context, natural product arrival, demonstration, reassurance, and one CTA. Adapt the structure to the platform and concept; do not force every video into identical timing.

## Eight-part review

Review the complete brief and copy sequentially. Reviewers 1-7 each score 1-100 and must reach 90. Reviewer 8 returns PASS or FAIL and has veto power.

### 1. Strategic alignment

Check the brief against project objectives, evidence, awareness, funnel job, and intended learning. Fail unsupported strategy drift.

### 2. Persona fit

Check recognition, language match, desire versus feature, specificity, and whether the represented creator or scene fits the evidence-backed persona.

### 3. Awareness and sophistication

Check that the message assumes the right prior knowledge, explains neither too much nor too little, and uses a proof type appropriate to market sophistication.

### 4. Angle execution

Check angle clarity, headline alignment, full-brief consistency, and single-idea discipline.

### 5. Proof and claims

Check every material claim against the proof stack. Flag unsupported quantification, fake urgency, guarantee drift, prohibited claims, and evidence that does not support the exact wording.

### 6. Emotion and copy craft

Check whether the copy triggers rather than labels the intended emotion; then assess compression, specificity, originality, rhythm, clarity, selling power, and respect for the reader.

### 7. Format and production readiness

Check channel fit, hook visibility, text length, visual-copy coherence, creator instructions, shot or layout clarity, CTA logic, and whether production can execute without guessing.

### 8. Copy editor - veto

Check grammar, spelling, punctuation, number consistency, duplicate content, official brand/product capitalization, prohibited characters supplied by the brand, and required length limits. One unresolved mechanical error returns FAIL.

## Reviewer output

For reviewers 1-7 return:

```json
{
  "reviewer": 1,
  "name": "Strategic alignment",
  "score": 0,
  "verdict": "PASS or NEEDS_REVISION",
  "evidence": ["specific observation"],
  "strongest_element": "specific strength",
  "weakest_element": "specific weakness",
  "revision_instruction": "actionable instruction or null"
}
```

Reviewer 8 returns:

```json
{
  "reviewer": 8,
  "name": "Copy editor",
  "result": "PASS or FAIL",
  "veto_triggered": false,
  "errors": [
    {
      "element": "headline",
      "exact_text": "text containing the error",
      "issue": "specific issue",
      "correction": "corrected text"
    }
  ]
}
```

## Revision loop

1. Fix blocking claim, brand, persona, and mechanical failures first.
2. Fix structural problems second.
3. Improve weak hooks, angle clarity, emotion, and craft third.
4. Rerun all eight reviews because one revision may create a new inconsistency.
5. Stop only when reviewers 1-7 are at least 90 and reviewer 8 passes.

Never inflate a score to close the loop.
