# Documentation Standard

This standard defines the shared practices for writing, structuring, and maintaining documentation within Vector Labs Studio. It answers a single question: **How should documentation be written and maintained within Vector Labs Studio?** It builds upon the core principles established in the handbook to ensure our documentation remains durable, clear, and easy to maintain.

---

## 1. Single Responsibility

To prevent cognitive overhead and information sprawl, every document must be organized around a single responsibility:

*   **One Core Question**: Each document should answer exactly one fundamental question. Everything included in the document must directly support answering that question.
*   **Preventing Scope Bleed**: Avoid creating documents that accumulate unrelated guidance or diverse topics. 
*   **Decoupled Growth**: When a topic expands to address new questions or distinct responsibilities, those concerns should be factored out into a new document rather than stretching the existing one.

---

## 2. Information Architecture and Structure

Documentation is structured to maximize discoverability and ease of navigation while avoiding unnecessary complexity.

*   **Explicit Boundaries**: Each document must clearly define its scope—stating what it covers and, where necessary, explicitly detailing what it does not cover (scope boundaries).
*   **Flat over Deep**: We organize documentation with a preference for logical, flat structures over deep nesting. Avoid introducing artificial hierarchies or nested directories that make discovery difficult.
*   **Consistent Anatomy**: While document structures do not need to be identical, they should maintain consistency in naming, structural logic, and terminology. This ensures readers can navigate diverse documents with minimal cognitive friction.

---

## 3. Writing Style and Terminology

Clear writing is the foundation of clear alignment. Our writing style is designed to be accessible, precise, and durable:

*   **Principle-Driven and Timeless**: Focus on concepts, frameworks, and patterns that endure, rather than short-term configurations.
*   **Terminology Consistency**: Use key terms consistently across all documents. Avoid introducing synonyms for defined concepts, which creates ambiguity.
*   **Concise Expression**: Prefer clarity and brevity over long explanations. Every paragraph, list, or diagram should serve to make the document's answer easier to understand.

---

## 4. Referential Integrity and Duplication

Duplicate information is a primary driver of documentation rot. We protect the integrity of our knowledge base by adhering to these guidelines:

*   **Cross-References over Copying**: Prefer hyperlinking to the authoritative source of a concept rather than duplicating its explanation. Assume other documents exist and rely on them.
*   **Single Source of Truth**: Every principle, pattern, or standard should have a single home. If a concept is needed in multiple contexts, refer to its primary document rather than rewriting it.

---

## 5. Maintainability and Evolution

Documentation is a living representation of our shared understanding, not a static record.

*   **Ease of Modification**: Focus on small, modular documents that are simple to update, extend, or reorganize.
*   **Guidance Retirement**: When context changes and guidance loses its validity, the affected documents must be updated, replaced, or retired rather than allowed to linger as outdated records.
*   **Reorganization**: As domains grow, proactively restructure and clean up documentation pathways to prevent legacy organization from obscuring current knowledge.

---

## 6. Review Guidelines

Review is a collaborative activity aimed at building confidence in our shared knowledge. When reviewing documentation changes, reviewers should evaluate:

*   **Architecture and Scope**: Does the change respect the document's single responsibility? Does it introduce unnecessary duplication or cross-layer conflicts?
*   **Clarity and Simplicity**: Is the proposed wording clear, concise, and accessible? Does it avoid unnecessary complexity?
*   **Consistency**: Is the terminology consistent with the rest of the repository?
*   **Durable Value**: Does the contribution capture enduring guidance, avoiding temporary or project-specific details?

Reviewing documentation should focus as much on the quality of the information architecture and scope discipline as it does on editorial correctness.
