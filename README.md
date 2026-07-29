# Brand Grill

A jargon-free brand discovery skill for solo founders who know what they want their company to feel like but struggle to express it in conventional brand language.

Brand Grill runs an adaptive guided interview using situations, trade-offs, metaphors, and emotional reactions. It then offers either a concise findings summary or a comprehensive, designer-ready brand foundation.

## What makes it different

- No requests to “write your mission statement.”
- No archetype, demographic, or brand-value worksheets.
- Roughly two concrete questions per round.
- Mostly vivid choices, always with room for a custom answer.
- Follow-ups adapt to the founder rather than following a rigid form.
- Contradictions become useful decision rules.
- Existing names and visual assets are preserved unless critique is invited.
- Direct founder choices remain distinct from strategic interpretation.
- No premature logo, palette, slogan, or naming advice.

The intended reaction is:

> This puts words around things I felt but could not explain.

## Interview flow

1. Eight-round core discovery
2. Short coverage checkpoint
3. Optional deeper exploration of:
   - voice and language;
   - messaging;
   - tagline territory;
   - customer journey;
   - creative direction
4. Focused clarification of material gaps
5. Concise summary or comprehensive foundation

## Install

### Local review

From a parent directory:

```bash
npx skills add ./brand-grill
```

List the skill without installing:

```bash
npx skills add ./brand-grill --list
```

### From GitHub after public release

```bash
npx skills add ekansh005/brand-grill --skill brand-grill
```

Add `-g` for a global installation or select a supported agent interactively.

## Example requests

The skill is designed to activate automatically for relevant brand-discovery requests. It can also be named directly:

```text
Use brand-grill to help me understand the brand behind my new accounting product.
```

```text
I know what I want my company to feel like, but brand questionnaires make me freeze. Grill me.
```

```text
Help me turn my founder story and instincts into a brief I can hand to a designer.
```

```text
We already have a company name and logo. Preserve them, but help me clarify everything the wider brand should communicate.
```

## Package

```text
brand-grill/
├── SKILL.md
├── references/
│   ├── core-interview.md
│   ├── deep-dives.md
│   ├── fictional-example.md
│   └── output-templates.md
├── README.md
└── LICENSE
```

The skill is Markdown-only. It contains no scripts, executable code, external services, or telemetry.

## Privacy

Brand discovery can involve commercially sensitive information. The skill itself does not transmit or store data, but the agent or platform running it may have separate data-handling policies.

- Review the privacy terms of the agent you use.
- Avoid sharing confidential client names, credentials, unreleased financial information, or protected personal data.
- Redact private material before including it in a public example.
- Keep final strategy documents private unless you deliberately choose to publish them.

All examples included in this repository are fictional. No private Visyst brand findings are included.

## Status

This repository is prepared for local review and validation. It is not yet a public skills.sh release.

After review, publishing consists of pushing the repository publicly and installing it through the Skills CLI. There is no separate registry publish command; skills.sh discovery can occur through install telemetry.

## Authorship

Created by Ekansh ([@ekansh005](https://github.com/ekansh005)) and Visyst Labs Oy.

## License

[MIT](LICENSE)
