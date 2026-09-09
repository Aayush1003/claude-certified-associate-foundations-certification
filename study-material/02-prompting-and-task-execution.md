# 2. Prompting and Task Execution

## The core idea

Prompting is a communication discipline. A strong prompt makes the task, context, constraints, and success criteria visible.

## A practical prompt structure

Use this sequence:

1. **Role or perspective:** Who should Claude act as?
2. **Task:** What must it do?
3. **Context:** What information, definitions, or source material matters?
4. **Audience:** Who will use the result?
5. **Constraints:** Length, tone, exclusions, deadline, policy, and required checks.
6. **Output format:** Sections, fields, table columns, bullets, or artifact type.
7. **Quality bar:** What should be checked, flagged, cited, or left blank?

Example:

> Act as a project communications analyst. Using the attached weekly log, prepare an update for non-technical executives. Include status, three completed milestones, two risks with owners, and next week's priorities. Keep it under 200 words. Do not invent missing dates; mark gaps as `not provided`.

## Decompose complex work

Compound prompts often hide several different tasks. Break them into observable steps:

1. Extract facts.
2. Categorize or compare them.
3. Prioritize using stated criteria.
4. Draft the deliverable.
5. Review against the source and requirements.

Decomposition makes errors easier to find and lets you correct one stage without restarting the entire workflow.

## Match strategy to task type

- **Extraction:** define exactly what counts and require missing items to be flagged.
- **Summarization:** specify audience, length, emphasis, and whether caveats must be retained.
- **Analysis:** define the criteria, comparison set, assumptions, and decision output.
- **Research:** request sources, dates, and uncertainty; verify important claims.
- **Drafting:** provide audience, voice, structure, examples, and approval boundaries.
- **Brainstorming:** request breadth first, then filter ideas against explicit criteria.

## Iterate deliberately

When the output misses, name the failure before changing the prompt:

| Failure | Targeted adjustment |
| --- | --- |
| Wrong format | State exact structure, count, and example |
| Generic answer | Add decision criteria, audience, and relevant context |
| Missing items | Define completeness and require a gap report |
| Unsupported claims | Require source locations and verification flags |
| Wrong tone | Describe the audience and provide a short style example |
| Too much detail | Set scope, length, and priority order |

Changing one variable at a time makes the result diagnosable.

## Self-check

1. Why is “be detailed and thorough” weaker than an explicit output schema?
2. What should a prompt say when the source does not contain an answer?
3. What is the best next step after a formatting failure?
4. Why is repeating the same vague prompt a poor iteration strategy?

**Answers:** 1. It expresses preference without defining observable success. 2. Tell Claude to mark the gap rather than infer or invent. 3. State the required format, counts, and an example. 4. It does not change the cause of the failure.
