# TechAndMe Playbook

# TMP-005

# Repository Standards

---

## Document Information

| Property | Value |
|----------|-------|
| Document ID | TMP-005 |
| Title | Repository Standards |
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
3. Repository Philosophy
4. Core Repository Principles
5. Standard Repository Files
6. Related Documents
7. Revision History
8. Closing Reflection

---

# Preamble

A repository is more than a location for source code.

It is the permanent home of a software project, its documentation, its engineering decisions, and its history.

A well-organised repository enables engineers to understand a project quickly, contribute confidently, and maintain software efficiently over time.

This document establishes the repository standards that shall be followed across all TechAndMe projects.

---

# 1. Purpose

The purpose of this document is to define a consistent repository structure and management approach for every TechAndMe project.

Standardisation improves:

- Navigation
- Discoverability
- Collaboration
- Maintainability
- Onboarding
- Long-term sustainability

Every repository should feel familiar to an engineer who has worked on any previous TechAndMe project.

---

# 2. Repository Philosophy

Repositories should be organised around clarity rather than convenience.

Every file should have a logical home.

Every folder should serve a clear purpose.

The repository itself should communicate the architecture and maturity of the project.

Repository organisation should minimise confusion and maximise maintainability.

---

# 3. Core Repository Principles

Every TechAndMe repository shall follow these principles.

## Principle 1 — One Repository, One Product

Each repository should represent a single software product, engineering resource, or reusable component.

Repositories should avoid combining unrelated projects.

---

## Principle 2 — Documentation First

Every repository shall contain sufficient documentation for an engineer to understand the project before reading the source code.

Documentation is part of the product.

---

## Principle 3 — Predictable Structure

Repositories should follow a consistent directory structure.

Engineers should be able to locate documentation, source code, assets, tests, and configuration files without guesswork.

---

## Principle 4 — Clean Root Directory

The repository root should contain only essential files.

Avoid placing implementation files directly in the root unless they are required by the technology.

A clean root improves readability and project navigation.

---

## Principle 5 — Version Controlled Knowledge

Everything required to understand, build, and maintain the project should be version controlled wherever practical.

Knowledge should remain with the repository rather than individual contributors.

---

# 4. Standard Repository Files

Every repository should include, where applicable:

- README.md
- LICENSE
- .gitignore
- CHANGELOG.md
- CONTRIBUTING.md
- docs/
- src/
- tests/
- assets/

Additional files may be included when required by the project, but these should remain the core repository foundation.

# 5. Standard Repository Structure

Every TechAndMe repository should adopt a logical and predictable structure.

Although individual projects may introduce additional folders, the overall organisation should remain consistent.

A typical repository should resemble the following:

```text
Repository/
│
├── README.md
├── LICENSE
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
│
├── docs/
├── src/
├── tests/
├── assets/
├── scripts/
└── examples/
```

Not every repository requires every folder.

Repositories should include only folders that provide value to the project.

---

## Repository Root

The root directory should contain only files required to understand, configure, or build the project.

Typical root files include:

- README.md
- LICENSE
- .gitignore
- CHANGELOG.md
- CONTRIBUTING.md
- Project configuration files

Implementation files should normally reside within the source directory.

---

## Documentation Directory

The `docs` directory contains all project documentation.

Typical contents include:

- Architecture
- Business documents
- Specifications
- Checkpoints
- Playbooks
- API documentation
- Roadmaps

Documentation should be organised into logical subdirectories rather than large collections of unrelated files.

---

## Source Directory

The `src` directory contains the implementation of the software.

Source code should reflect the system architecture rather than technical convenience.

Directory structures should encourage modularity and separation of responsibilities.

---

## Tests Directory

The `tests` directory contains automated tests.

Where practical, the test structure should closely mirror the structure of the source code.

This improves navigation and simplifies maintenance.

---

## Assets Directory

The `assets` directory stores non-source resources.

Examples include:

- Images
- Icons
- Logos
- Diagrams
- Sample data
- Demonstration files

Generated build outputs should not normally be stored here.

---

# 6. Repository Naming Standards

Repository names should be:

- Clear
- Concise
- Descriptive
- Stable

Repository names should communicate the primary purpose of the project.

Examples:

- attendance_dashboard
- TechAndMe-Playbook
- QMS-TAT-Monitor

Avoid repository names that become obsolete after small changes in project scope.

---

# 7. Branching Strategy

Every repository should maintain a simple and understandable branching strategy.

For most TechAndMe projects:

- `main` represents the stable production branch.
- Feature branches may be used for significant development work.
- Experimental work should remain isolated until ready for review.

Branches should be merged only after sufficient review and testing.

Repository history should remain clean and meaningful.

---

# 8. Commit Message Standards

Commit messages form part of the engineering documentation.

Every commit should describe **what changed** rather than merely recording that something changed.

Preferred examples include:

- Initial commit: establish project foundation
- Adopt TMP-004 Documentation Standards
- Revise attendance analytics engine
- Add AI provider abstraction
- Refactor session detection service

Avoid vague commit messages such as:

- Update
- Changes
- Fix
- Miscellaneous

A meaningful commit history tells the story of a project's evolution.

---

# 9. Repository Maintenance

Repositories should be maintained continuously.

Routine maintenance includes:

- Updating documentation.
- Reviewing dependencies.
- Removing obsolete files.
- Maintaining a clean directory structure.
- Archiving outdated documents when appropriate.

Engineering quality includes repository quality.

A well-maintained repository reflects a well-maintained project.

---

# 10. Repository Lifecycle

Every TechAndMe repository progresses through a defined lifecycle.

Understanding the lifecycle helps engineers evaluate project maturity, plan future work, and manage expectations.

## Lifecycle Stages

| Stage | Description |
|---------|-------------|
| Planning | Vision, architecture, and documentation are being developed. |
| Development | Active implementation is in progress. |
| Review | Features and documentation are undergoing technical review. |
| Release | A stable version has been published for intended users. |
| Maintenance | Enhancements, bug fixes, and improvements continue after release. |
| Archived | Development has concluded. The repository is retained for historical reference. |

Repository status should be reflected through documentation, release tags, and version history.

---

# 11. Open Source Standards

Where appropriate, TechAndMe repositories should be prepared for public collaboration.

Open-source repositories should include:

- A clear README.
- An appropriate LICENSE.
- CONTRIBUTING guidelines.
- A maintained CHANGELOG.
- Meaningful documentation.
- Consistent commit history.

Public repositories represent both the software and the engineering practices behind it.

Professional presentation encourages community confidence and future collaboration.

---

# 12. Security and Sensitive Information

Repositories must never contain confidential or sensitive information.

Examples include:

- Passwords
- API keys
- Authentication tokens
- Personal data
- Private certificates
- Production secrets

Sensitive information should be managed through secure configuration mechanisms and excluded from version control using `.gitignore` where appropriate.

Security is a shared engineering responsibility.

---

# 13. Repository Quality Checklist

Before considering a repository ready for publication, verify that:

- Repository purpose is clearly defined.
- README accurately describes the project.
- Documentation is organised and current.
- Source code follows the project architecture.
- Tests are included where applicable.
- Licensing information is present.
- Sensitive information has been excluded.
- Commit history is meaningful.
- Directory structure remains organised.
- The repository reflects professional engineering standards.

This checklist provides a simple quality gate before publishing or sharing a repository.

---

# 14. Related Documents

This document should be read alongside:

- TMP-001 Engineering Charter
- TMP-003 Engineering Principles
- TMP-004 Documentation Standards
- TMP-006 Architecture Review Process
- TMP-007 Checkpoint Framework

Together, these documents establish the operational engineering standards used throughout TechAndMe.

---

# 15. Revision History

| Version | Date | Description | Author |
|----------|------|-------------|--------|
| 1.0 | July 2026 | Initial adopted edition | TechAndMe |

---

# 16. Closing Reflection

A repository is more than a collection of files.

It is the recorded history of engineering decisions, technical growth, and collaborative effort.

Well-organised repositories reduce friction, preserve knowledge, and enable projects to continue evolving long after their first release.

Within TechAndMe, every repository is expected to reflect the same values that guide our engineering practice: clarity, consistency, maintainability, and professionalism.

A well-structured repository is often the first demonstration of engineering quality—and the first invitation for others to trust, understand, and contribute to the work.

---

**TechAndMe Playbook**

**Building Better Software.**

**Building Better Engineers.**

© TechAndMe