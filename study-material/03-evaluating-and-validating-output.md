# 3. Evaluating and Validating Claude's Output

## The professional standard

Treat Claude's output as a draft or analysis to evaluate, not as evidence by itself. Fluent language, a confident tone, internal consistency, and self-reported confidence do not establish truth.

## Failure modes to recognize

- **Fabrication:** a detail, citation, number, name, or source is invented.
- **Omission:** an important fact or caveat present in the source is missing.
- **Misinterpretation:** the source is quoted but its meaning is changed.
- **Inconsistency:** two parts of the output conflict.
- **Bias:** framing, selection, or language unfairly favors a perspective.
- **Audience mismatch:** accurate content is unusable because tone, format, or detail is wrong.

## Risk-based validation workflow

1. Identify claims that would matter if wrong.
2. Return to the authoritative source of record.
3. Check the exact passage, number, date, and scope.
4. Check completeness, not only individual facts.
5. Compare the result with the requested format and audience.
6. Correct, remove, or clearly label unsupported material.
7. Obtain human review when the output is regulated, consequential, external-facing, or difficult to reverse.

A citation supplied by Claude is a lead to inspect, not proof. Asking Claude to check itself is useful for finding possible issues but is not independent validation.

## Completeness checks

For extraction and summarization, ask:

- Did every required section or item appear?
- Were exceptions and caveats preserved?
- Are labels and dates attached to the correct facts?
- Are unknowns clearly marked instead of filled with guesses?
- Does the output answer the requested question rather than a nearby one?

## Audience adaptation

After accuracy is established, adapt the output to the reader. An executive may need decisions, risks, and actions. An analyst may need evidence and assumptions. A customer may need clear language, appropriate tone, and approved claims.

Adaptation never means hiding uncertainty or removing a material limitation.

## Validation matrix

| Output use | Minimum discipline |
| --- | --- |
| Personal brainstorming | Sanity-check key assumptions |
| Internal working draft | Verify consequential facts and gaps |
| Customer or executive communication | Verify claims and obtain accountable human review |
| Legal, financial, medical, regulatory, or safety use | Use authoritative sources and qualified human review |

## Self-check

1. What does a plausible number without a source mean?
2. Why can a tidy four-item extraction still be incomplete?
3. What should happen to a claim that cannot be verified?
4. Who owns the decision to send an external communication?

**Answers:** 1. It remains unverified. 2. Formatting does not prove that other items were not omitted. 3. Remove it, mark it as unverified, or investigate before presenting it as fact. 4. The accountable human owner, not the model or prompt author alone.
