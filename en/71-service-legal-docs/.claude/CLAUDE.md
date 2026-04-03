# Service Legal Docs Jarbis

A service terms and legal document drafting agent team jarbis.

## Structure

```
.claude/
├── agents/
│   ├── tos-specialist.md
│   ├── privacy-specialist.md
│   ├── consumer-analyst.md
│   └── consistency-reviewer.md
├── skills/
│   ├── service-legal-docs/
│   │   └── skill.md              — Orchestrator
│   ├── unfair-terms-detector/
│   │   └── skill.md              — Unfair terms detector (unfairness criteria, regulatory examples, amendment suggestions)
│   └── cross-document-linker/
│       └── skill.md              — Cross-document linker (term consistency, cross-reference mapping, version management)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/service-legal-docs` skill, or make a natural language request.
