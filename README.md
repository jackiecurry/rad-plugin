# RAD Design System — Claude Code Plugin

**RAD (Responsible · Accountable · Disclosed)** is a design system for agentic AI user interfaces. This plugin brings RAD component knowledge directly into Claude Code.

**By Jackie Curry** · [jackiecurry.github.io/rad.html](https://jackiecurry.github.io/rad.html)

---

## Commands

| Command | What it does |
|---------|-------------|
| `/rad:suggest` | Describe what you're building — get the right RAD components recommended |
| `/rad:audit` | Review the current file for RAD compliance issues |
| `/rad:new [component]` | Scaffold a RAD component with markup, tokens, and a11y |
| `/rad:explain [component]` | Explain a component's purpose, contracts, and when to use it |

---

## Examples

```
/rad:suggest I'm building an agent that sends emails on the user's behalf
/rad:audit
/rad:new HC01
/rad:explain Algorithmic Nudge Disclosure
```

---

## Installation

Install from the Claude Code plugin marketplace, or manually:

1. Copy this directory into your project or `~/.claude/plugins/`
2. Commands are available immediately as `/rad:suggest`, `/rad:audit`, etc.

---

## What is RAD?

RAD provides standardized components, behavioral contracts, and interaction patterns for the specific trust failures that occur when AI systems act on behalf of humans:

- **R — Responsible.** Every AI action is attributable.
- **A — Accountable.** Human oversight is preserved. Consequential decisions require explicit human approval.
- **D — Disclosed.** AI involvement is never hidden.

34 components across 7 groups: Transparency & Disclosure, Human Control & Oversight, Accountability & Audit, Foundation, Capability Discovery, Agent Activity, and Context Management.

Full docs: [jackiecurry.github.io/rad-components.html](https://jackiecurry.github.io/rad-components.html)

---

© 2025 Jackie Curry. See [license](https://jackiecurry.github.io/license-personal.html).
