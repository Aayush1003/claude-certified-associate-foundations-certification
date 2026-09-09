# 1. Claude Platform and Model Foundations

## What this module is about

Before writing a prompt, make four decisions: **entry point, capability, model, and context**. These choices set the quality, cost, speed, and safety ceiling of the session.

## Entry point

Choose the surface that matches the work:

| Need | Suitable starting point |
| --- | --- |
| Quick, self-contained question | Regular conversation |
| Repeated work with shared instructions and sources | Project |
| Current, sourced investigation | Research capability, when available and appropriate |
| Structured document, code, or interactive deliverable | Artifact capability, when available and appropriate |
| Connected internal systems or custom automation | Escalate to technical colleagues and approved integrations |

Do not choose a feature because it sounds more advanced. Choose it because it solves the actual constraint.

## Model selection

Use the smallest model that reliably meets the task requirement:

- **Haiku:** speed, cost, and high-volume routine work.
- **Sonnet:** balanced quality, speed, and cost for most everyday work.
- **Opus:** difficult reasoning, ambiguity, or high-value work where extra capability is justified.

A larger model does not fix missing context, weak instructions, stale sources, privacy violations, or absent human accountability.

## Context selection

Give Claude the information it needs, but keep the working context focused. Separate:

- **Durable context:** reusable project instructions, standards, reference documents, and definitions.
- **Task context:** today's input, audience, deadline, and requested output.
- **Decision context:** what Claude should compare, prioritize, or flag.

Too little context causes guessing. Too much irrelevant or conflicting context dilutes the important material.

## Four-question preflight

1. What work surface fits this task?
2. Which capability is actually needed?
3. What is the least expensive and fastest model that can meet the quality bar?
4. What sources and constraints must Claude have, and which should remain outside the prompt?

## Common exam traps

- Selecting the most capable model for every task.
- Treating a model's confidence or fluent language as proof.
- Uploading every available document instead of curating relevant sources.
- Using a prompt to compensate for a missing system control or integration.

## Self-check

1. Which model tier fits hundreds of formulaic replies where latency and cost dominate?
2. Why might adding more documents make an answer worse?
3. When does a one-off chat become a Project candidate?
4. What kind of request should be escalated to a Developer or Architect?

**Answers:** 1. The fastest, lowest-cost model that meets the quality requirement. 2. Relevant material can be diluted or contradicted. 3. When the task repeats and needs durable instructions or knowledge. 4. Custom integrations, internal system connections, or technical implementation beyond ordinary use.
