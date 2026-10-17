# Changelog

Significant project changes are recorded here. Planned features do not count as released features.

## [Unreleased] — Public project showcase

- Introduced ByteCoop's public identity, project documentation and architectural graphics.
- Clarified the difference between the tested local prototype and code actually published in this repository.
- Documented security-sensitive boundaries and the planned 0.4 improvement work.

## Alpha 0.3 — Local prototype · 2026-10-17

- Introduced a conversation-centered React interface and projects.
- Added persistent multi-conversation organization.
- Integrated local OpenAI and DeepSeek real API workflows.
- Preserved Cortex's project memory and decision history alongside Mesh event records.
- Provided Windows installation and migration scripts for the local source package.

**Observed validation:** Windows installation output reported **65 passing backend tests** and **11 passing UI tests**; a separate real three-call workflow cost a reported **$0.001649**.

**Known defect:** first model returned a plan without the substantive answer; the next model generated what it called the first model's response. This is part of 0.4's priorities.

## Alpha 0.2 — Local prototype

Provider integration, guarded approvals, key handling and cost limits.

## Alpha 0.1 — Local prototype

Persistent project memory, permissions and coordinated task foundations.
