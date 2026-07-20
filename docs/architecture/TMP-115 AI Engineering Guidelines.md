# TechAndMe Playbook

# TMP-115

# AI Engineering Guidelines

---

## Document Information

| Property | Value |
|----------|-------|
| Document ID | TMP-115 |
| Title | AI Engineering Guidelines |
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
4. AI Engineering Principles
5. AI Architecture Guidelines
6. Prompt Engineering
7. Model Selection
8. AI Safety and Governance
9. Performance and Evaluation
10. Continuous Improvement
11. Related Documents
12. Revision History
13. Closing Reflection

---

# Preamble

Artificial Intelligence is becoming an integral component of modern software systems.

However, successful AI solutions depend on disciplined engineering rather than simply integrating large language models or machine learning services.

The AI Engineering Guidelines establish a common engineering approach for designing, integrating, evaluating, and maintaining AI capabilities across TechAndMe projects.

These guidelines ensure that AI remains reliable, explainable, maintainable, and aligned with business objectives.

---

# 1. Purpose

The purpose of this document is to establish engineering standards for the responsible design and implementation of Artificial Intelligence within TechAndMe projects.

It provides practical guidance that complements existing engineering principles and architectural standards.

---

# 2. Scope

This document applies to:

- Large Language Models (LLMs)
- AI Assistants
- Machine Learning systems
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering
- AI APIs
- Local AI models
- AI-enabled applications

Model-specific implementation details should be documented within individual projects.

---

# 3. AI Engineering Principles

AI engineering follows the same professional standards as every other architectural discipline.

Core principles include:

- Business before AI
- Human-centred design
- Explainable behaviour
- Responsible automation
- Privacy by design
- Security by design
- Modular architecture
- Continuous evaluation
- Continuous improvement

AI should solve meaningful problems rather than introduce unnecessary complexity.

---

# 4. AI Architecture Guidelines

AI should remain an architectural component rather than becoming the application architecture itself.

Recommended practices include:

- Separate AI services from business logic.
- Use provider abstraction.
- Support multiple AI providers where practical.
- Isolate prompts from application code.
- Protect domain models from provider-specific dependencies.
- Maintain clear application boundaries.

This approach enables flexibility as AI technologies continue to evolve.

---

# 5. Prompt Engineering

Prompts should be treated as engineering assets.

Recommended practices include:

- Version prompts.
- Document prompt objectives.
- Separate system, developer, and user instructions.
- Minimise ambiguity.
- Test prompts using representative scenarios.
- Review prompts alongside application changes.

Prompt libraries should be maintained as part of project documentation.

---

# 6. Model Selection

Model selection should be based on project requirements rather than popularity.

Evaluation criteria may include:

- Accuracy
- Cost
- Response quality
- Latency
- Context window
- Privacy requirements
- Local deployment capability
- Licensing

Projects should periodically reassess model suitability as technologies evolve.

---

# 7. AI Safety and Governance

AI systems should operate within clearly defined boundaries.

Engineering considerations include:

- Human oversight
- Content validation
- Sensitive data protection
- Output review
- Responsible disclosure
- Ethical use
- Auditability

AI should assist engineering decisions rather than replace engineering judgement.

---

# 8. Performance and Evaluation

AI capabilities should be evaluated using measurable criteria.

Typical evaluation metrics include:

- Response quality
- Accuracy
- Hallucination rate
- Consistency
- Latency
- Cost efficiency
- User satisfaction

Evaluation should become a continuous engineering activity rather than a one-time exercise.

---

# 9. Continuous Improvement

AI engineering evolves rapidly.

Projects should regularly review:

- Prompt effectiveness
- Model performance
- New providers
- Security considerations
- Regulatory developments
- User feedback

Continuous improvement ensures AI capabilities remain valuable and maintainable over time.

---

# 10. Related Documents

- TMP-003 Engineering Principles
- TMP-004 Documentation Standards
- TMP-006 Architecture Review Process
- TMP-106 AI Architecture
- TMP-111 Security Architecture
- TMP-112 Integration Architecture
- TMP-114 Testing Architecture

---

# 11. Revision History

| Version | Date | Description | Author |
|----------|------|-------------|--------|
| 1.0 | July 2026 | Initial draft | TechAndMe |

---

# 12. Closing Reflection

Artificial Intelligence is most effective when combined with disciplined engineering.

Within TechAndMe, AI is viewed as an architectural capability that extends human expertise rather than replacing it.

By applying sound engineering principles, responsible governance, and continuous evaluation, AI can become a reliable, maintainable, and trusted component of modern software systems.

---

**TechAndMe Playbook**

**Building Better Software.**

**Building Better Engineers.**

© TechAndMe