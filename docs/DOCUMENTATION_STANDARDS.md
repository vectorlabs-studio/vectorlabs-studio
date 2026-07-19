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
This document defines the philosophy of documentation within Vector Labs Studio. We treat documentation as part of the Studio's durable, versioned memory rather than temporary communication or process. This document establishes the principles for why we document, what knowledge belongs in our shared documentation, and what must be excluded to keep our knowledge system clear, sustainable, and relevant as decisions and context evolve.

---

## 1. The Value of Documentation
Documentation exists to eliminate the cognitive waste of rediscovering information or repeating resolved decisions. It is a core mechanism that preserves important context and makes knowledge understandable across the Studio, alongside working systems, measurements, and reusable assets.
* **Durability**: We build documentation to serve as the Studio's versioned memory, designed to remain understandable and usable over time. As knowledge and decisions change, documents may evolve, be superseded, or lose relevance.
* **Dual Audience**: Documentation should remain understandable and usable by both human contributors and AI agents, without optimizing exclusively for either audience. It must be clear and structured to help both human and AI readers parse context and extract key lessons.

---

## 2. What We Preserve: Decisions, Context, and Constraints
Documentation represents the current accepted state of knowledge rather than raw discussion history or transient logs. While meeting records, chat logs, and status updates serve as temporary source material or evidence, they should not be treated as durable Studio knowledge without synthesis. Documentation should preserve the resulting knowledge rather than reproducing the entire conversation.
To remain useful, documentation should preserve:
* **Context and Rationale**: The background, reasoning, and evidence that support our current state of knowledge.
* **Assumptions and Uncertainty**: Explicitly documented assumptions, remaining uncertainty, and validity conditions.
* **Decisions and Alternatives**: The accepted standards, decision status, and significant trade-offs or rejected alternatives.

---

## 3. What We Omit
To prevent information rot and maintain clarity, documentation must exclude:
* **Transient Content**: We exclude temporary status, raw meeting minutes, chat records, and work-tracking logs from durable documentation, preserving only the synthesized outcomes.
* **Chronological History**: Documentation should preserve the knowledge required to understand the current state, rather than reproduce a chronological history of every implementation change.
* **Operational Details**: We do not mix high-level knowledge with rules about text formats, directory structures, document templates, or parsing tools.

---

## 4. Proportionality and Evolution
* **Proportional Rigor**: The depth, structure, and maintenance effort of documentation must be proportional to the risk, impact, longevity, and reuse value of the knowledge being preserved. We avoid creating unnecessary documentation for routine or low-impact work.
* **Active Guidance Evolution**: Documentation should be updated when its underlying knowledge, standards, or decisions change; when its validity changes; when it conflicts with another authoritative document; or when its current expression no longer communicates the knowledge accurately. Outdated knowledge should be updated, superseded, or removed from active guidance rather than silently coexisting with current guidance.

---

## Scope Boundaries
This document intentionally does not define:

- Markdown, templating, or text formatting styles
- File naming conventions or directory organizations
- README structures or document templates
- Tooling, automated documentation generators, or parsers
- Chat, issue tracking, or task management systems

Where needed, implementation-specific guidance may be defined separately without changing these principles.
