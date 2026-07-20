# TechAndMe Playbook

# TMP-116

# Engineering Decision Records (EDR) Standard

---

## Document Information

| Property | Value |
|----------|-------|
| Document ID | TMP-116 |
| Title | Engineering Decision Records (EDR) Standard |
| Version | 1.0 |
| Status | Draft |
| Classification | Public |
| Owner | TechAndMe |
| Author | TechAndMe |
| Reviewer | Chief Architect |
| Approver | Chief Architect |
| Effective Date | July 2026 |
| Last Updated | July 2026 |

---

> **Building Better Software.**
>
> **Building Better Engineers.**

---

# Table of Contents

1. Preamble
2. Purpose
3. Scope
4. What is an Engineering Decision Record?
5. Engineering Decision Principles
6. EDR Lifecycle
7. Standard EDR Structure
8. Decision Categories
9. Relationship with ADRs
10. Governance
11. Related Documents
12. Revision History
13. Closing Reflection

---

# Preamble

Engineering projects are shaped by thousands of decisions.

Some are minor implementation choices, while others influence architecture, engineering practices, tooling, documentation, repository organisation, or long-term project direction.

Without a structured record, these decisions are easily forgotten, making future maintenance and project evolution more difficult.

Engineering Decision Records (EDRs) provide a permanent and traceable history of significant engineering decisions made throughout the lifecycle of a TechAndMe project.

---

# 1. Purpose

The purpose of this document is to establish a standard for documenting engineering decisions across all TechAndMe projects.

The standard promotes transparency, knowledge preservation, traceability, and consistent decision-making.

---

# 2. Scope

This document applies to:

- Engineering practices
- Repository decisions
- Documentation standards
- Development workflow
- Technology selection
- Coding standards
- Build processes
- Testing strategies
- AI engineering decisions

Architectural decisions should instead be documented using the Architecture Decision Record (ADR) process.

---

# 3. What is an Engineering Decision Record?

An Engineering Decision Record (EDR) documents an important engineering decision together with its supporting context.

An EDR explains:

- What was decided.
- Why the decision was required.
- Alternatives that were considered.
- Why the selected option was chosen.
- Expected consequences.

The objective is to preserve engineering reasoning rather than simply recording outcomes.

---

# 4. Engineering Decision Principles

Every Engineering Decision Record should follow these principles.

- Record significant decisions.
- Capture decisions while they are fresh.
- Explain the reasoning.
- Consider alternatives.
- Remain objective.
- Support future engineers.
- Maintain traceability.

An EDR should answer the question:

> "Why was this decision made?"

---

# 5. EDR Lifecycle

Engineering Decision Records progress through a simple lifecycle.

| Status | Description |
|----------|-------------|
| Proposed | Decision under consideration. |
| Accepted | Decision approved and adopted. |
| Revised | Decision updated following review. |
| Superseded | Replaced by a newer decision. |
| Archived | Retained for historical reference. |

The status should always reflect the current state of the decision.

---

# 6. Standard EDR Structure

Every Engineering Decision Record should contain the following sections.

## Document Information

- EDR Identifier
- Title
- Status
- Date
- Author

---

## Context

Describe the situation that required the decision.

---

## Problem Statement

Explain the engineering problem that must be solved.

---

## Alternatives Considered

List the practical options that were evaluated.

---

## Decision

Describe the selected approach.

---

## Rationale

Explain why the selected option was preferred.

---

## Consequences

Describe the expected benefits, trade-offs, and risks.

---

## References

Include links to related documents, standards, checkpoints, or architecture documentation.

---

# 7. Decision Categories

Engineering Decision Records may cover topics including:

- Repository organisation
- Documentation standards
- Development workflow
- Engineering methodology
- Programming language selection
- Framework adoption
- Testing strategy
- AI provider selection
- Deployment approach
- Tooling decisions

Projects may introduce additional categories where appropriate.

---

# 8. Relationship with ADRs

Engineering Decision Records complement Architecture Decision Records (ADRs).

| EDR | ADR |
|-----|-----|
| Engineering practice | Software architecture |
| Repository decisions | Architectural decisions |
| Workflow | System structure |
| Tooling | Component relationships |
| Standards | Design decisions |

Projects should select the record type that best reflects the nature of the decision.

---

# 9. Governance

Engineering Decision Records should:

- Receive permanent identifiers.
- Remain under version control.
- Be reviewed when circumstances change.
- Never be deleted.
- Be superseded rather than overwritten.
- Remain accessible throughout the project lifecycle.

Engineering knowledge is cumulative and should be preserved.

---

# 10. Related Documents

- TMP-004 Documentation Standards
- TMP-006 Architecture Review Process
- TMP-007 Checkpoint Framework
- TMP-008 Engineering Reference System
- TMP-101 Architecture Patterns

---

# 11. Revision History

| Version | Date | Description | Author |
|----------|------|-------------|--------|
| 1.0 | July 2026 | Initial draft | TechAndMe |

---

# 12. Closing Reflection

Engineering excellence is built upon thoughtful decisions as much as quality implementation.

Recording engineering decisions allows projects to retain valuable knowledge, understand historical context, and make future improvements with confidence.

Within TechAndMe, every significant engineering decision is considered part of the project's intellectual foundation and deserves to be preserved.

---

**TechAndMe Playbook**

**Building Better Software.**

**Building Better Engineers.**

© TechAndMe