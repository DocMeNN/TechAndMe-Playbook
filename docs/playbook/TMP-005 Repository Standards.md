# TechAndMe Playbook

# TMP-005

# Repository Standards

---

## Document Information

| Property | Value |
|----------|-------|
| Document ID | TMP-005 |
| Title | Repository Standards |
| Version | 2.0 |
| Status | Adopted |
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

1. Purpose
2. Repository Philosophy
3. Core Repository Principles
4. Standard Repository Files
5. Standard Repository Structure
6. Repository Naming Standards
7. Branching Strategy
8. Commit Message Standards
9. Repository Maintenance
10. Repository Lifecycle
11. Open Source Standards
12. Security and Sensitive Information
13. Repository Quality Checklist
14. Related Documents
15. Revision History
16. Closing Reflection

---

# 1. Purpose

## 1.1 Purpose

This document establishes the official repository standards for all TechAndMe engineering projects.

It defines a consistent repository structure and management approach to improve navigation, discoverability, collaboration, maintainability, onboarding, and long-term sustainability.

### RS-001

All TechAndMe repositories shall comply with this standard.

### RS-002

Repository organisation shall prioritise clarity, maintainability, and long-term engineering quality.

---

# 2. Repository Philosophy

Repositories are more than locations for source code.

They are the permanent home of software, documentation, engineering decisions, and project history.

Every repository should communicate the architecture, maturity, and purpose of the project.

### RS-003

Repository organisation shall communicate the structure of the project rather than merely storing files.

---

# 3. Core Repository Principles

## 3.1 One Repository, One Product

Each repository should represent one software product, engineering resource, or reusable component.

### RS-004

Repositories shall not combine unrelated projects.

---

## 3.2 Documentation First

Documentation is part of the product.

### RS-005

Every repository shall contain sufficient documentation before implementation is considered complete.

---

## 3.3 Predictable Structure

Repository structures should be familiar across TechAndMe projects.

### RS-006

Repositories shall follow a predictable directory structure.

---

## 3.4 Clean Root Directory

The repository root should contain only essential files.

### RS-007

Implementation files should normally reside within the source directory.

---

## 3.5 Version Controlled Knowledge

Engineering knowledge belongs to the repository.

### RS-008

Project knowledge should be version controlled wherever practical.

---

# 4. Standard Repository Files

Typical repository files include:

- README.md
- LICENSE
- .gitignore
- CHANGELOG.md
- CONTRIBUTING.md
- docs/
- src/
- tests/
- assets/

### RS-009

Repositories shall include the files and directories appropriate to the project while maintaining a consistent structure.

---

# 5. Standard Repository Structure

A typical TechAndMe repository should resemble:

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

Not every repository requires every directory.

### RS-010

Repositories shall include only directories that provide engineering value.

---

## 5.1 Repository Root

The repository root should contain only files required to understand, configure, or build the project.

Typical root files include:

- README.md
- LICENSE
- .gitignore
- CHANGELOG.md
- CONTRIBUTING.md
- Project configuration files

### RS-011

The repository root shall remain clean and uncluttered.

---

## 5.2 Documentation Directory

The `docs` directory contains project documentation.

Typical contents include:

- Architecture
- Business documents
- Specifications
- Checkpoints
- Playbooks
- API documentation
- Roadmaps

### RS-012

Documentation shall be organised into logical subdirectories.

---

## 5.3 Source Directory

The `src` directory contains software implementation.

### RS-013

Source code organisation shall reflect the software architecture.

---

## 5.4 Tests Directory

The `tests` directory contains automated tests.

### RS-014

Where practical, the test structure should mirror the source structure.

---

## 5.5 Assets Directory

The `assets` directory stores non-source resources.

Examples include:

- Images
- Icons
- Logos
- Diagrams
- Sample data
- Demonstration files

### RS-015

Generated build outputs should not normally be stored in the assets directory.

---

# 6. Repository Naming Standards

Repository names should be:

- Clear
- Concise
- Descriptive
- Stable

Examples:

- attendance_dashboard
- TechAndMe-Playbook
- QMS-TAT-Monitor

### RS-016

Repository names shall clearly communicate the primary purpose of the project.

### RS-017

Repository names should remain stable throughout the life of the project.

---

# 7. Branching Strategy

Most TechAndMe repositories should adopt a simple branching strategy.

Typical branches include:

- `main`
- Feature branches
- Temporary experimental branches

### RS-018

The `main` branch shall represent the stable version of the repository.

### RS-019

Feature branches should be reviewed before merging.

### RS-020

Repository history should remain clean, meaningful, and understandable.

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

### RS-021

Every commit message shall clearly describe the primary engineering change.

### RS-022

Commit messages should be concise, meaningful, and written in the imperative mood.

### RS-023

Engineering standards and governance documents should be committed individually whenever practical.

---

# 9. Repository Maintenance

Repositories should be maintained continuously.

Routine maintenance includes:

- Updating documentation
- Reviewing dependencies
- Removing obsolete files
- Maintaining a clean directory structure
- Archiving outdated documents where appropriate

### RS-024

Repository maintenance shall be performed throughout the project lifecycle.

### RS-025

Repository quality shall be considered part of overall engineering quality.

---

# 10. Repository Lifecycle

Every TechAndMe repository progresses through a defined lifecycle.

## 10.1 Lifecycle Stages

| Stage | Description |
|---------|-------------|
| Planning | Vision, architecture, and documentation are being developed. |
| Development | Active implementation is in progress. |
| Review | Features and documentation are undergoing technical review. |
| Release | A stable version has been published. |
| Maintenance | Improvements continue after release. |
| Archived | Development has concluded. |

### RS-026

Every repository shall clearly communicate its current lifecycle stage.

---

# 11. Open Source Standards

Where appropriate, TechAndMe repositories should be prepared for public collaboration.

Open-source repositories should include:

- README
- LICENSE
- CONTRIBUTING
- CHANGELOG
- Meaningful documentation
- Consistent commit history

### RS-027

Public repositories shall reflect professional engineering standards.

---

# 12. Security and Sensitive Information

Repositories shall never contain confidential or sensitive information.

Examples include:

- Passwords
- API keys
- Authentication tokens
- Personal data
- Private certificates
- Production secrets

Sensitive information should be managed using secure configuration mechanisms and excluded from version control.

### RS-028

Sensitive information shall never be committed to version control.

### RS-029

Repository configuration shall prevent accidental publication of confidential information.

---

# 13. Repository Quality Checklist

Before publication, verify that:

- Repository purpose is clearly defined.
- README accurately describes the project.
- Documentation is organised and current.
- Source code follows the architecture.
- Tests are included where applicable.
- Licensing information is present.
- Sensitive information has been excluded.
- Commit history is meaningful.
- Directory structure remains organised.
- Engineering standards have been followed.

### RS-030

Repositories should satisfy the quality checklist before public release.

---

# 14. Related Documents

This document should be read alongside:

- TMP-001 Engineering Charter
- TMP-003 Engineering Principles
- TMP-004 Documentation Standards
- TMP-006 Architecture Review Process
- TMP-007 Checkpoint Framework
- TMP-008 Engineering Reference System

### RS-031

Repository standards shall comply with the Engineering Reference System defined in **TMP-008**.

---

# 15. Revision History

| Version | Date | Description | Author |
|----------|------|-------------|--------|
| 1.0 | July 2026 | Initial adopted edition | TechAndMe |
| 2.0 | July 2026 | Adopted Engineering Reference System, section numbering, rule identifiers, and cross-reference standards. | TechAndMe |

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