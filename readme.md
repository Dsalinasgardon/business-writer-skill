# business-writer

A Claude skill for drafting, reviewing, and improving professional business writing across all common formats.

## What it does

Once installed, this skill activates automatically whenever you ask Claude to write, improve, or review any piece of business communication — emails, proposals, executive summaries, business letters, and more.

It works in two modes:

- **Draft** — Claude writes from your brief, applying the right structure and framework for the document type.
- **Review** — Claude evaluates writing you share, flags specific issues, and offers a revised version.

## Document types covered

| Type | Examples |
|---|---|
| Email / stakeholder message | Client updates, follow-ups, internal requests |
| Business proposal | Project pitches, budget requests, internal proposals |
| Research proposal | Formal plans requesting funding or resources |
| Executive summary | One-page summaries of reports or proposals |
| Business letter | Formal letters to clients, partners, or stakeholders |

## Frameworks included

The skill draws on a reference library of proven business writing frameworks:

- **7 C's** — Complete, Concise, Considerate, Clear, Concrete, Courteous, Correct
- **8S Framework** — Simple, Specific, Surprising, Stirring, Seductive, Smart, Social, Story-Driven
- **AIDA + Proof** — Attention, Interest, Desire, Action, supported by evidence
- **BLUF** — Bottom Line Up Front for fast, decision-first communication
- **Aristotle's Three Appeals** — Ethos, Logos, Pathos for high-stakes persuasion
- **Hot Buttons** — Audience alignment by stakeholder type
- **Paramedic Check** — Sentence-level editing for conciseness
- **Seven-Step Email Proofreading Checklist**

## File structure

```
business-writer/
├── SKILL.md                        # Main skill logic and instructions
└── references/
    ├── frameworks.md               # All writing frameworks and checklists
    └── document-types.md          # Structure guides for each document type
```

## Installation

Copy the `business-writer/` folder into your Claude skills directory:

```
/mnt/skills/user/business-writer/
```

Claude will detect and use the skill automatically based on the request.

## Usage examples

These phrases will trigger the skill automatically:

- *"Draft an email to our CTO requesting budget approval."*
- *"Review this proposal and tell me what's weak."*
- *"Help me write an executive summary for this report."*
- *"Is this email too wordy?"*
- *"Rewrite this in a more professional tone."*

## Source material

Frameworks are drawn from established business writing research and practice, including:

- Scott Powell on clarity of purpose
- The 8S cognitive framework for persuasive writing
- Jeff Bradford (Forbes) on writing as a leadership skill
- Julie Maddock on audience-focused writing
- Aristotle's rhetorical appeals
- AIDA persuasion model
- Grammarly's seven-step proofreading method
- BLUF communication standard

## License

MIT
