# Platform Standards Foundation

This document defines the foundation for all platform-specific standards within Vector Labs Studio. It answers a single question: **How should platform-specific standards be defined within Vector Labs Studio?** It establishes how general engineering principles and design expectations are translated into actionable guidance for specific technical environments.

---

## Hierarchy of Guidance

To preserve coherence and make the source of guidance clear, we organize our standards within a progressive hierarchy:

1.  **The Handbook**: Provides enduring principles, defining why the Studio exists and how we think.
2.  **Standards Foundation**: Defines how all standards are created, scoped, and maintained.
3.  **Cross-Domain Standards**: Product and Design Standards define upstream requirements and experience expectations.
4.  **Engineering Standard**: Provides technology-independent engineering guidance and quality expectations.
5.  **Platform Standards**: Translate general engineering and design guidance into a specific technical environment.
6.  **Project Decisions**: Establish local design and implementation choices within the boundaries defined by upstream standards.

Platform standards should inherit from broader standards. They should not redefine or contradict them without making the conflict explicit and resolving it at the appropriate level.

---

## Role and Scope of a Platform Standard

A platform standard defines recurring decisions that materially depend on the characteristics of a technical platform or ecosystem:

*   **Platform-Dependent Concerns**: Guidance belongs in a platform standard when it addresses concerns such as platform lifecycles, execution environments, state and concurrency models, native navigation conventions, integration boundaries, persistence capabilities, packaging, platform security, testing capabilities, observability, resource constraints, and distribution models.
*   **Justification for Existence**: A platform standard should exist only when the guidance cannot remain useful and precise at the general Engineering Standard level. Sibling platform standards should not create competing definitions, and cross-platform concerns should have explicit ownership.
*   **Scope Discipline**: Platform standards should remain focused on recurring platform decisions. They should not become complete platform tutorials, onboarding manuals, framework documentation, project setup guides, dependency catalogs, repository blueprints, or collections of transient implementation details.

---

## General Versus Platform-Specific Guidance

We maintain a clear distinction between general engineering guidance and platform-specific applications:

*   **General Guidance**: Principles that remain valid across technologies (such as clear responsibilities, low coupling, confidence-driven verification, security design, and explicit trade-off reasoning) belong in the Engineering Standard. We avoid duplicating these principles in platform documents.
*   **Platform-Specific Guidance**: Platform standards should inherit applicable guidance by default. Instead of restating broader principles, a platform standard should provide contextual references, narrow abstract guidance, identify platform constraints, establish defaults, and define justified exceptions.

---

## Platform Boundaries

Each platform standard should clearly define the technical environment it governs:

*   **Defining Boundaries**: Platform boundaries should be based on meaningful differences in engineering decisions, such as runtimes, operating systems, deployment environments, application layers, ecosystems, distribution models, or ownership of technical capabilities.
*   **Decoupled Boundaries**: Avoid defining a platform boundary solely by repository folder structure, programming language, or current organizational boundaries.
*   **Dynamic Taxonomy**: The platform taxonomy is not permanent. New platform domains may be introduced when a distinct body of recurring guidance emerges, and existing domains may be merged or retired as technical boundaries evolve.

---

## Defaults and Judgment

Platform standards should establish opinionated defaults to support consistency, maintainability, and operational confidence:

*   **Supporting Judgment**: Defaults should reduce unnecessary decision-making for common cases without eliminating contextual judgment. They should be clearly motivated and revisited when platform capabilities change.
*   **Proportional Exceptions**: A standard establishes a common path, not a constraint on judgment. Thoughtful deviations are allowed when platform constraints differ, defaults create disproportionate costs, product requirements demand an alternative, or existing compatibility obligations limit options.
*   **Visibility of Exceptions**: Small, local choices should not require unnecessary ceremony. Material deviations should make their rationale, consequences, and expected lifetime visible to help future contributors.

---

## Platform Evolution and Compatibility

Platform standards must account for technical change and the realities of existing codebases:

*   **Durable Intent**: Distinguish between enduring engineering intent, current platform constraints, current preferred approaches, and deprecated practices. We avoid embedding short-lived version numbers in foundational standards.
*   **Compatibility and Legacy**: Platform standards should account for both new and existing systems, considering version compatibility, migration costs, and dependent systems. The standard should support incremental improvement without forcing unsafe or unnecessarily disruptive rewrites of legacy code.
*   **Review Triggers**: Standards should be reviewed when platform capabilities evolve, recurring exceptions indicate a gap in the defaults, or an established approach becomes obsolete.

---

## Relationships with Upstream Standards

Platform standards connect design and engineering intent to specific implementations:

*   **Expressing Design Intent**: Platform standards may explain how the Design Standard is expressed in a specific environment, defining interaction conventions, native accessibility implementation expectations, and platform-specific feedback behaviors. They must not redefine usability principles, information hierarchy, or visual design philosophy.
*   **Actionable Engineering**: Platform standards contextualize engineering principles (such as architecture, security, state, and concurrency) within the platform's constraints. They must not redefine general engineering quality. Where multiple platforms share a rule, it should live at the broadest useful level.

---

## Evidence and Review Expectations

Platform guidance should reflect accumulated experience rather than personal preference:

*   **Evidence-Led Guidance**: Standards should be informed by observed failure modes, platform behaviors, maintenance outcomes, established conventions, and deliberate technical judgment. Where evidence is limited, guidance should remain flexible and easy to revise.
*   **Proportional Review**: Review of a platform standard should evaluate alignment with broader standards, accuracy within the platform context, boundary clarity, compatibility implications, and migration impacts. Review should challenge both excessive generality and unnecessary implementation details.
