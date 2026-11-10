# Brand DNA: Capture Identity, Voice, and Positioning

> One file that captures who you are: identity, audience, positioning, values and voice. Every other design skill reads it first, so nothing drifts between projects.

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) ![Claude Code](https://img.shields.io/badge/Claude_Code-skill-blueviolet.svg) [![Available on Agensi](https://img.shields.io/badge/Agensi-%249-ff5a5f.svg)](https://agensi.io/skills/brand-dna-capture-identity-voice-and-positioning)

## What it does

Capture and store core brand DNA: identity, audience, positioning, values, and voice. The foundation skill that the logo, deck, and content skills all read from.

Establishes the brand context foundation. This file is read by every other brand/design skill before doing any work.

## The failure it prevents

Working this by hand means rediscovering the same edge cases every time. They are written down here instead, with the fix for each one.

## When to use it

- capture who the brand is before designing anything
- give every design skill the same source of truth
- record positioning, voice and audience once

## What's inside

```
plugins/
└── brand-dna/
    ├── .claude-plugin/plugin.json
    └── skills/brand-dna/
        ├── SKILL.md
```

## Install

Add this repo as a Claude Code marketplace, then install the skill:

```bash
claude plugin marketplace add Verstige/brand-dna
claude plugin install brand-dna@brand-dna
```

Or copy the skill straight into your skills directory:

```bash
git clone https://github.com/Verstige/brand-dna.git
cp -R brand-dna/plugins/brand-dna/skills/brand-dna ~/.claude/skills/
```

## Usage

The skill activates on the work it describes. Ask for the outcome, and it
supplies the method:

```
> "capture who the brand is before designing anything"
```

## License

MIT. See [LICENSE](LICENSE).

---

**Also available as a paid skill on Agensi** — $9. Install it with one command, no clone required:

[agensi.io/skills/brand-dna-capture-identity-voice-and-positioning](https://agensi.io/skills/brand-dna-capture-identity-voice-and-positioning)

Part of the [Verstige](https://github.com/Verstige) skills portfolio. More at [github.com/Verstige](https://github.com/Verstige).
