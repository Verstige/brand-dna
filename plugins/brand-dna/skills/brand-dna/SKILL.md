---
name: brand-dna
description: "Capture and store core brand DNA: identity, audience, positioning, values, and voice. The foundation skill that the logo, deck, and content skills all read from."
version: 1.0.0
license: MIT
author: "the maintainers"
---
# Brand Context

Establishes the brand context foundation. This file is read by every other brand/design skill before doing any work.

## Before You Start

Check if `.agents/brand-context.md` already exists. If it does, read it and ask user what to update. If it doesn't exist, collect the information.

## Information to Collect

### 1. Brand Basics
- Brand name
- One-line description of what it does
- Industry / category
- Stage (pre-launch, early, growth, established)

### 2. Audience
- Primary target audience (who they are)
- Key problem the brand solves for them
- Audience language (words/phrases they use)

### 3. Positioning
- What makes this brand different from alternatives?
- Who are 2–3 main competitors?
- Where does this brand sit? (premium, value, niche, mass)

### 4. Brand Personality
- 3–5 words describing brand character
- Tone: formal or casual? Serious or playful?
- Any brands whose identity/voice this brand admires?

### 5. Values & Mission
- Core values (3–5)
- Mission statement (or working draft)

### 6. Goals
- Primary business goal for the next 12 months
- Key metrics (revenue, awareness, followers, signups)

## Output

Create `.agents/brand-context.md` with:

```markdown
# Brand Context

## Brand
- **Name**: [name]
- **Category**: [category]
- **Description**: [one-liner]
- **Stage**: [stage]

## Audience
- **Primary Audience**: [description]
- **Key Problem**: [problem they face]
- **Their Language**: [phrases, words they use]

## Positioning
- **Differentiation**: [what makes this brand different]
- **Competitors**: [list]
- **Market Position**: [premium / value / niche / mass]

## Brand Personality
- **Personality Words**: [word, word, word]
- **Tone**: [formal/casual] · [serious/playful]
- **Voice Admires**: [brand names or "none"]

## Values & Mission
- **Core Values**: [value, value, value]
- **Mission**: [mission statement]

## Goals
- **Primary Goal**: [goal]
- **Key Metrics**: [metrics]
```

Tell the user the file is saved and all other brand skills will use it automatically. They can update it anytime by running this skill again.

## Related Skills

- **brand-identity**: Visual identity brief using this context
- **brand-strategy**: Full brand strategy using this context
- **brand-voice**: Voice and tone using this context
- **brand-messaging**: Taglines and messaging using this context
- **logo-design**: Logo creation using this context
