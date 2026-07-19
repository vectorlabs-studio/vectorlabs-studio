# Vector Labs Studio Documentation Standards

## Version
0.1.0

## Status
Draft

## Owner
Founder

## Last Updated
2026-07-19

## Purpose
This document defines the philosophy of documentation within Vector Labs Studio. We treat documentation as a long-lived organizational asset rather than temporary communication or process. This document establishes the principles for why we document, what knowledge belongs in our permanent documentation, and what must be excluded to keep our knowledge system clear and sustainable.

---

## 1. The Value of Documentation
Documentation exists to eliminate the cognitive waste of rediscovering information or repeating resolved decisions. It is the primary mechanism for scaling the Studio's capabilities beyond individual memory.
* **Durability**: We build documentation to outlive the individuals who wrote it. It is designed to remain understandable and useful over years, serving as the permanent repository of the Studio's operating context.
* **Dual Audience**: We write documentation to serve human contributors and AI agents equally. It must be clear, structured, and logical, enabling both human readers and automated systems to parse context, extract lessons, and act on instructions with minimal ambiguity.

---

## 2. What We Preserve: Decisions, Context, and Constraints
We do not document transient conversations or raw discussion history. Instead, documentation captures the final, structured outcomes of those interactions.
To remain useful, documentation must preserve:
* **Context**: The problem, opportunities, and background surrounding a decision.
* **Rationale**: The reasoning, assumptions, and evidence that led to a choice.
* **Constraints**: The boundaries, trade-offs, and conditions under which a decision is valid.
* **Decisions**: The accepted standards, operating rules, or technical directions.

---

## 3. What We Omit
To prevent information rot and maintain clarity, documentation must exclude:
* **Transient Content**: We omit temporary status, meeting minutes, chat records, issue tracking logs, and local configurations.
* **Implementation History**: We do not duplicate context that is captured automatically in version control.
* **Operational Details**: We do not mix high-level knowledge with rules about text formats, directory structures, document templates, or parsing tools.

---

## 4. Proportionality and Evolution
* **Proportional Rigor**: The depth, structure, and maintenance effort of documentation must be proportional to the risk, impact, and longevity of the knowledge being preserved. Routine tasks and low-impact experiments do not require permanent documentation.
* **Event-Driven Evolution**: Documentation should only evolve when our underlying knowledge, standards, or decisions change. We do not modify documentation for superficial reasons; updates must reflect a change in the Studio's operating reality or validated experience.

---

## Scope Boundaries
This document intentionally does not define:

- Markdown, templating, or text formatting styles
- File naming conventions or directory organizations
- README structures or document templates
- Tooling, automated documentation generators, or parsers
- Chat, issue tracking, or task management systems

These technical rules and formats are documented separately and build upon these core documentation principles.
