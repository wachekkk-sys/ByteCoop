# Roadmap

> **ByteCoop is an experimental alpha.** Milestones describe intentions, not delivery dates or promises.

## Now / next

| Version | Milestone | Status |
|---|---|---|
| **0.1** | Cortex/Mesh memory, policies and event logging foundation | Implemented in local prototype |
| **0.2** | Real provider adapters, human approvals and budgets | Implemented in local prototype |
| **0.3** | Chat interface, persistent conversations, handoff between models | Tested locally |
| **0.4** | Improve substantive first-agent responses and relevant context retrieval | Planned |
| **0.5** | Optional developer workspace with sandboxed execution model | Proposed |
| **0.6** | Controlled dependency installation, previews and reviewable code changes | Proposed |

## 0.4 — Make collaboration genuinely collaborative

- Ensure the first agent completes its assigned analysis, not only a plan.
- Preserve actual provider authorship when handing results to another agent.
- Filter irrelevant project memories out of task prompts without weakening server-enforced policies.
- Test project memory reuse across separate conversations.
- Make failures actionable while preserving secret redaction and safe billing states.

**Exit condition:** A reproducible OpenAI → DeepSeek → OpenAI workflow where model B critiques model A's *real* output and model A synthesizes both.

## 0.5 — Developer capabilities, without developer complexity

ByteCoop is intended for **everyone**, not solely programmers. An optional developer mode could reveal a file explorer, source editor and terminal. Non-developers should see only task progress and the finished preview.

Direct host-shell access and unattended software installation are **out of scope** without strong isolation and explicit controls.

## 0.6 — Safe project workflows

Explore isolated project environments, explicit package-install permissions, preview environments, diff review and rollback.

## Quality gates for every release

1. Reproducible tests and clear installation notes.
2. Human approval boundaries preserved for paid requests and sensitive actions.
3. No cross-project/private-memory leaks.
4. No secrets or local user data in released source or logs.
5. Source and license review before a public code release.

This roadmap may change as we learn from real developer and non-developer pilots.
