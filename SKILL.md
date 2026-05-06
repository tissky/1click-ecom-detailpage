---
name: crossborder-pdp-conversion-strategy
description: Build high-converting cross-border e-commerce hero image and PDP copy strategy by first diagnosing conversion driver type (visual-driven, pain-driven, or emotion-value-driven), then producing conversion-first English baseline and optional intent-preserving localization.
---

# Cross-Border PDP Conversion Strategy Skill

Use this skill when the user asks for product listing copy, hero image logic, PDP structure, or conversion optimization for cross-border e-commerce.

## Trigger Signals

- "Amazon listing", "Shopify PDP", "detail page", "hero image copy", "A+ content"
- "improve conversion", "improve CTR", "boost add-to-cart", "offer + CTA"
- "localize copy", "multilingual listing", "adapt copy for market"

## Core Principle

This skill does **not** start from fixed image templates. It starts from a **conversion diagnosis**:

1. **Visual-Driven** (sell with seeing)
2. **Pain-Driven** (sell with problem urgency + resolution)
3. **Emotion-Value-Driven** (sell with identity, aspiration, impulse)

Then it maps the selected driver to hero-image and PDP flow.

---

## Workflow

1. Collect minimum inputs
2. Diagnose 1 primary conversion driver (+ optional secondary)
3. Build conversion hypothesis and evidence plan
4. Produce English (US) baseline strategy and copy
5. Optionally apply localization layer (intent-preserving, not literal)
6. Run conversion QA and publish output

---

## Step 1) Minimum Inputs (Required)

Collect these before drafting:

- Product name + category + price band
- Audience segment and purchase context
- Top differentiators (material, function, design, speed, cost, guarantee)
- Proof assets (test data, certifications, user feedback, press, warranty terms)
- Channel constraints (Amazon, Shopify, TikTok Shop, etc.)
- Current weak points (low CTR, low CVR, weak trust, low AOV)

If critical fields are missing, mark assumptions explicitly.

## Step 2) Diagnose Conversion Driver Type

Choose one primary type:

### A. Visual-Driven (Sell the Image)

Use when:
- Purchase decision depends on visual appeal, style fit, finish, texture, before/after visibility, or giftability.

Output emphasis:
- Hero image story arc
- Visual hierarchy, texture cues, lifestyle context
- Fast scan copy with short benefit anchors

### B. Pain-Driven (Sell the Need)

Use when:
- Buyer feels acute friction, risk, time loss, or recurring annoyance.

Output emphasis:
- Problem intensity and consequence framing
- Relief mechanism and concrete benefits
- Trust and proof to remove skepticism
- Strong offer and urgent CTA

### C. Emotion-Value-Driven (Sell the Feeling)

Use when:
- Product is tied to identity, confidence, belonging, status, care, joy, novelty, or impulse.

Output emphasis:
- Emotional hook and identity narrative
- Symbolic payoff + practical reassurance
- Social proof and low-friction action

---

## Step 3) Driver-Specific Page Logic

## Visual-Driven Flow

### Hero Images
1. Thumb-stop visual claim (style/value in 1 second)
2. Key feature close-up (texture/detail proof)
3. Use scenario fit (where/when/how it looks right)
4. Comparison frame (ordinary vs upgraded look)
5. Conversion frame (offer + shipping/guarantee + CTA)

### PDP Flow
- Above-the-fold visual promise
- Feature zoom modules
- Scenario modules
- Quality/proof module
- Offer + CTA block

## Pain-Driven Flow (Priority Sequence)

### Mandatory Conversion Sequence
1. **Pain mining / fear trigger**: Make the problem concrete and costly
2. **Benefit / solution**: Show clear mechanism and relief outcome
3. **Trust**: Authority, evidence, and user experience reassurance
4. **Irresistible offer + CTA**: Make inaction expensive and action easy

### Hero Images
1. Problem snapshot (what hurts now)
2. Solution mechanism (what this product changes)
3. Benefit proof (measurable or observable outcomes)
4. Trust frame (credentials, testimonials, policies)
5. Offer + urgency CTA (bundle, guarantee, deadline)

### PDP Flow
- Problem severity opener
- Why current alternatives fail
- How this solves it (mechanism)
- Benefit stack (functional + practical)
- Trust stack (authority + user experience)
- Offer architecture (price logic, bundle, guarantee, risk reversal)
- CTA close

**Rule:** Every block must serve conversion. Remove decorative sections.

## Emotion-Value-Driven Flow

### Hero Images
1. Emotional scene hook
2. Identity/value statement
3. Product as enabler
4. Belonging/status/social cue
5. Offer + CTA with emotional reinforcement

### PDP Flow
- Emotional promise
- Identity narrative + use moments
- Practical confidence proof
- Community/social validation
- Offer + CTA

---

## Step 4) English Baseline Output (Always First)

Produce:

1. Conversion diagnosis summary
2. Hero image sequence (5 frames)
3. PDP module map
4. Copy draft snippets (headline/subhead/CTA/proof lines)
5. Offer and CTA strategy
6. Assumptions and test plan

Keep copy concise and scan-friendly for image embedding.

---

## Step 5) Localization Layer (Optional, Lightweight)

Localization is a **layer**, not the strategy core.

Process:
1. Lock conversion intent in English baseline
2. Adapt by market while preserving the same persuasion job
3. Validate length, cultural sensitivity, unit/scene relevance

Rules:
- Do not literal-translate high-performing lines
- Preserve conversion intent (hook, belief shift, action cue)
- Respect platform length constraints for images and mobile PDP
- Adapt units (oz/ml, in/cm, temperature, currency format)
- Replace culturally weak or risky references

If localization weakens conversion intent, flag and revise.

---

## Step 6) Conversion QA Checklist

Before final output, verify:

- Driver diagnosis is explicit and justified
- Flow matches selected driver
- Pain-driven sequence includes all 4 required stages
- Trust claims are evidence-backed
- Offer + CTA are clear and specific
- Copy length fits hero/PDP placement
- Localization (if any) preserves intent, not wording

---

## Output Format

Return in this structure:

1. **Conversion Driver Diagnosis**
2. **Hero Image Plan (5 Frames)**
3. **PDP Structure**
4. **Core Copy Lines (English Baseline)**
5. **Offer + CTA Architecture**
6. **Localization Notes (if requested)**
7. **Assumptions + Test Priorities**

Be practical: outputs should be executable by marketer + designer + media buyer.
