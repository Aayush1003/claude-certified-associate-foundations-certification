# 5. Configuration and Knowledge Management

## Projects: durable context

Use a Project when a task repeats and benefits from shared instructions or reference material. Put stable conventions in the Project and temporary details in the individual prompt.

**Project instructions** can contain tone, audience, workflow rules, required sections, definitions, exclusions, and review expectations.

**Project knowledge** can contain maintained handbooks, approved examples, templates, policies, and reference documents.

Avoid putting today's client, deadline, or one-off request into durable instructions.

## Curate before uploading

More knowledge is not automatically better. Add only material relevant to the task, remove duplicates, identify authoritative versions, and keep sensitive content within approved policy boundaries.

A maintained source set should have:

- An owner.
- A review or replacement process.
- Clear version status.
- A way to remove obsolete documents.
- Spot checks after important changes.

## Connectors and access

Connectors can extend Claude's reach to services such as approved drives or mail systems. Treat access as a governance decision: grant only what the workflow needs, confirm who can use it, and understand what data may be retrieved.

Connecting Claude to operational systems or building custom integrations is technical work and may require escalation.

## Configuration quality checks

Ask:

1. Are instructions short enough to maintain and specific enough to follow?
2. Are sources current, relevant, and non-conflicting?
3. Does the Project define what to do when information is missing?
4. Can a user tell which source or rule supported an answer?
5. Is access appropriate for every intended user?

## Common failure patterns

- **Stale source:** replace the old version and verify representative answers.
- **Conflicting sources:** identify the authority and remove or label superseded material.
- **Prompt drift:** centralize the shared standard in Project instructions.
- **Knowledge overload:** reduce to relevant sources and test retrieval again.
- **User-specific context missing:** make required inputs explicit in the workflow.

## Self-check

1. Where should a shared client-communication tone live?
2. What must happen when a handbook is replaced?
3. Why is “tell Claude to ignore the old file” weaker than removing it?
4. What should you check before enabling a connector?

**Answers:** 1. Project instructions. 2. Replace the outdated source, then spot-check outputs. 3. The obsolete content still exists and can influence retrieval. 4. Required scope, users, data access, policy, and ownership.
