# Multi-AI Orchestration | Leading an AI-Assisted Delivery Process

[English](../../README.md) | [日本語](../../README.ja.md)

## Approach

**The goal was not simply to generate code faster. It was to structure a delivery process in which different AI tools contribute to implementation, independent review, and improvement—while product decisions remain human-led.**

Ekiyomi used Claude Code and Codex in complementary roles, with GitHub serving as the change-management hub.

## Roles and responsibilities

| Role | Responsibility | Value added |
| --- | --- | --- |
| **Human product lead** | Product goals, priorities, UX direction, trade-offs, acceptance decisions | Keeps delivery aligned with user needs |
| **Claude Code** | Feature implementation, refinements, documentation, code changes | Translates requirements into working functionality |
| **Codex** | Independent review of implementation, usability, and technical quality | Surfaces issues from a distinct perspective |
| **GitHub** | Change tracking, pull requests, review findings, resolution history | Maintains traceability and coordination |

## A documented cross-AI review cycle

One review cycle surfaced **10 improvement areas** through Codex. Claude Code then supported implementation changes covering accessibility, child-appropriate interaction patterns, route information, readability, and iOS build preparation.

The core workflow was:

1. **Review:** obtain a separate evaluation of functionality and quality.
2. **Prioritize:** translate findings into actionable improvements.
3. **Implement:** use Claude Code to address the findings.
4. **Validate:** document what was checked and what required additional testing.
5. **Track:** preserve the connection between the review and resulting changes through GitHub.

[See the cross-AI review case study](./quality-management.md)

## Human judgment is the differentiator

AI can suggest changes, but the product lead must decide which ones support the intended experience. A useful example was the balance between text contrast and an illustrated, picture-book-like visual style.

This is a product decision, not just a coding decision. **Technical recommendations have to be evaluated against user experience, accessibility, and product positioning.**

## What I bring to AI-enabled teams

- **AI orchestration:** assign distinct roles to AI tools instead of duplicating work.
- **Delivery governance:** connect requirements, review findings, corrective actions, and changes.
- **Quality orientation:** assess usability and accessibility alongside technical functionality.
- **Business-to-technology translation:** turn user and product needs into concrete implementation direction.
- **Ownership:** make final prioritization and product decisions.

**Core principle: AI can expand execution capacity; leadership determines where that capacity creates value.**

[Back to portfolio](../../README.md)
