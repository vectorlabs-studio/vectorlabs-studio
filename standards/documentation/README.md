# Documentation Standard

This standard defines the shared practices for writing, structuring, and maintaining documentation within Vector Labs Studio. It answers a single question: **How should documentation be written and maintained within Vector Labs Studio?** It builds upon the core principles established in the handbook to support clear, coherent, and maintainable documentation.

---

## Proportional Documentation

Documentation should be written and managed according to its purpose, intended audience, expected lifetime, impact, risk, and reuse value. Rigor, structure, review depth, and maintenance expectations should be proportional to the document's importance and longevity.

*   **Durable Shared Guidance**: Documents intended for long-term organizational value should focus on enduring principles and clear trade-offs, avoiding transient operational details or project-specific context.
*   **Scoped and Temporary Documentation**: Project-specific or short-lived documents may include contextual, transient, or implementation details when necessary for their immediate responsibility.

---

## Single Responsibility

To manage complexity and support discoverability, each document should focus on one clear primary responsibility:

*   **Primary Responsibility**: A document should address a single primary question or topic. Supporting questions and relevant context may be included when they directly serve that responsibility.
*   **Preventing Scope Bleed**: Unrelated concerns should be separated into different files rather than combined into a single document.
*   **Balanced Organization**: While scope boundaries should be maintained, we avoid excessive fragmentation that splits closely related concepts into many artificially small documents.

---

## Document Stewardship

Documents with durable shared value should have identifiable stewardship to ensure their ongoing quality and relevance:

*   **Stewardship Responsibilities**: Stewards help maintain accuracy, respond when the underlying knowledge changes, resolve contradictions, and ensure that outdated guidance is updated, superseded, or retired.
*   **Adaptive Ownership**: We do not require static metadata blocks (such as version numbers, last updated dates, or specific owners) inside every file. Stewardship is fluid and may move as responsibilities and domains evolve.

---

## Authoritative Sources and Cross-References

To prevent duplicate information and conflicting guidance, each core concept should have a single authoritative home:

*   **Contextual Summaries**: When another document requires context from an authoritative source for reader comprehension, it may include a concise summary of the concept. This prevents readers from having to follow a link merely to understand the local document's basic context.
*   **Referential Integrity**: Any contextual summary should link to the authoritative source, avoid duplicating substantial guidance, and remain consistent with the primary definition. It must not create a competing or conflicting definition.

---

## Information Architecture

We organize documentation to support discoverability and clear navigation:

*   **Shallow Structures**: Use the shallowest structure that preserves clear domain boundaries, ownership, and discoverability. We avoid deep nesting that obscures content.
*   **Meaningful Hierarchy**: Directory and document hierarchies should exist only when they communicate meaningful relationships and structures.
*   **Explicit Scope**: Each document should clearly define its domain boundaries, helping readers understand where the guidance applies.

---

## Writing Style and Terminology

Our writing practices are designed to help contributors communicate clearly and maintain terminology consistency:

*   **Clarity and Precision**: Write with clarity and precision, aligning the depth of detail with the document's intended lifetime and audience.
*   **Contextual Completeness**: Provide sufficient background to make the guidance understandable within its scope without requiring external search.
*   **Terminology Consistency**: Use established terms consistently. Avoid introducing synonyms for defined concepts, helping to prevent ambiguity.

---

## Review Guidelines

Review is a collaborative activity that helps build confidence in our shared knowledge. When reviewing documentation, contributors should evaluate:

*   **Responsibility and Scope**: Does the document have a clear primary responsibility? Is the level of detail appropriate for the document's purpose and expected lifetime?
*   **Clarity and Precision**: Is the guidance clear, and are assumptions, scope, and validity conditions clearly articulated where relevant?
*   **Information Architecture**: Is the document located in the appropriate domain, and does it maintain referential integrity with authoritative sources?
*   **Stewardship**: For durable shared guidance, is the future maintenance or stewardship responsibility sufficiently clear?
