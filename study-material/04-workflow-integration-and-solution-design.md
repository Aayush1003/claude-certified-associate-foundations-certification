# 4. Workflow Integration and Solution Design

## Start with the business outcome

Do not begin with “Where can we put Claude?” Begin with the process:

1. Define the outcome and success measure.
2. Map the current steps, inputs, handoffs, delays, and decisions.
3. Separate bounded work from accountable judgment.
4. Identify where Claude can draft, classify, extract, summarize, compare, or propose.
5. Design review, exception handling, and ownership.
6. Test with representative examples.
7. Measure quality, time, cost, adoption, and risk.

## Good candidates for delegation

Claude is usually a strong fit for bounded, repeatable, checkable work such as drafting, reformatting, extracting fields, grouping themes, summarizing, and generating options.

Keep humans responsible for decisions involving accountability, relationships, irreversible actions, exceptions, or consequences that the workflow cannot reliably assess.

## Redesign versus automation

Automation copies a step. Redesign asks whether the step, handoff, approval, or output should exist in its current form. A useful design can propose two options: one that improves the current structure and one that changes the structure, with tradeoffs.

## Human-in-the-loop design

Keep an approval step when an action is external, difficult to reverse, legally or financially consequential, or likely to affect a person materially. The review should be meaningful: the reviewer needs the source, output, warnings, and authority to change the result.

## Adoption and integration

A workflow can produce excellent output and still fail if it arrives outside the user's working process, uses an inconvenient format, lacks ownership, or does not explain limits. Fit the output into the place where the decision or next action already happens.

Custom connections to internal databases, CRMs, or operational systems require approved technical design and escalation to the appropriate Developer or Architect.

## Stakeholder explanation template

Explain:

- What Claude does.
- What it does not do.
- What inputs it needs.
- What humans review or decide.
- How success and failure will be measured.
- What happens when the workflow cannot answer safely.

## Self-check

1. Which is safer to delegate: drafting variance commentary from agreed figures or approving journal entries?
2. Why can a technically good workflow have poor adoption?
3. When should a human approval step remain?
4. What is the first response to “Can Claude replace this whole process?”

**Answers:** 1. Drafting commentary. 2. It may not fit the existing work, output format, ownership, or review process. 3. When the action has external, irreversible, or high-consequence effects. 4. Map the process and define the division of labor, limits, and review points.
