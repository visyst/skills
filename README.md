# Visyst Skills

Agent skills from [Visyst](https://visyst.com).

[![skills.sh](https://skills.sh/b/visyst/skills)](https://skills.sh/visyst/skills)

## Skills

### brand-grill

A jargon-free brand discovery skill for solo founders who know what they want their company to feel like but struggle to express it in conventional brand language.

It runs an adaptive guided interview using situations, trade-offs, metaphors, and emotional reactions, then offers either a concise findings summary or a comprehensive, designer-ready brand foundation.

**Explicitly invoked** — name it in your request.

```bash
npx skills add visyst/skills --skill brand-grill
```

```text
Use brand-grill to help me understand the brand behind my new product.
```

Intended reaction:

> This puts words around things I felt but could not explain.

## Install

List skills in this repo:

```bash
npx skills add visyst/skills --list
```

Install one skill globally:

```bash
npx skills add visyst/skills --skill brand-grill -g
```

### Local review

From this repository root:

```bash
npx skills add . --skill brand-grill
```

## Package

```text
skills/
├── README.md
├── LICENSE
└── skills/
    └── brand-grill/
        ├── SKILL.md
        └── references/
            ├── core-interview.md
            ├── deep-dives.md
            ├── fictional-example.md
            └── output-templates.md
```

Skills are Markdown-only. No scripts, executable code, external services, or telemetry.

## Privacy

Brand discovery can involve commercially sensitive information. The skills themselves do not transmit or store data, but the agent or platform running them may have separate data-handling policies.

- Review the privacy terms of the agent you use.
- Avoid sharing confidential client names, credentials, unreleased financial information, or protected personal data.
- Redact private material before including it in a public example.

All examples in this repository are fictional. No private Visyst brand findings are included.

## Authorship

Created by [Visyst](https://visyst.com) ([@visyst](https://github.com/visyst)).

## License

[MIT](LICENSE) — Copyright (c) 2026 Visyst Labs Oy.
