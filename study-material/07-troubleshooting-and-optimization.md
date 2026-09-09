# 7. Troubleshooting and Optimization

## Diagnose before changing

When quality drops, capture the exact conditions: prompt, inputs, Project instructions, knowledge sources, model, capability, output, and expected result. Compare the failing case with the last successful case.

## Common causes

| Symptom | First investigation |
| --- | --- |
| Wrong facts | Source quality, missing context, or unsupported inference |
| Stale answers | Outdated Project knowledge |
| Generic output | Missing audience, criteria, or examples |
| Wrong format | Unspecified schema or conflicting instructions |
| Missing items | No completeness rule or input too long/diluted |
| Inconsistent runs | Task permits variation or constraints are too loose |
| Higher cost or latency | Overpowered model, excessive context, or unnecessary steps |
| Works for one person only | Hidden context supplied by the successful user |

The first variable to investigate is often the change that coincided with the regression.

## Fix in controlled steps

1. Reproduce the problem if possible.
2. Classify the failure.
3. Change one likely cause.
4. Test on representative cases, including edge cases.
5. Record the result and keep the successful configuration.
6. Add a regression example for future changes.

Do not switch to a larger model as a reflex. A model upgrade cannot repair stale knowledge, privacy problems, ambiguous requirements, or a broken workflow.

## Optimization

Optimization means improving quality, speed, cost, or maintainability while preserving the required outcome. Useful levers include:

- Smaller model for routine subtasks.
- Focused context instead of irrelevant documents.
- Reusable Project instructions for repeated work.
- Decomposition for complex tasks.
- Validation checks at the point of risk.
- A clear fallback when information is missing.

## Measure the task, not just the model

Track task-level measures such as factual accuracy, completeness, format compliance, review time, latency, cost, failure rate, and user adoption. General benchmarks are signals, not proof that a model fits your specific workflow.

## Self-check

1. What should you collect when a user reports an unreproducible wrong answer?
2. What is the first suspect after many documents are added to a Project?
3. How should you handle acceptable variation between identical runs?
4. When is a larger model a justified optimization choice?

**Answers:** 1. Exact prompt, inputs, configuration, model, sources, and output. 2. Dilution or contradiction from the new knowledge. 3. Tighten requirements so variation does not affect the needed result, then test representative cases. 4. When evaluation shows the task genuinely needs its extra capability and the cost or latency is justified.
