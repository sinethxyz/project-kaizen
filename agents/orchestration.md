# Orchestration

The six roles need a shared process.

The orchestrator is a workflow function, not a seventh reasoning role.

## Flow

```text
1. INGEST EVIDENCE
↓
2. UPDATE ENTERPRISE MODEL
↓
3. FORM HYPOTHESES
↓
4. RUN SIX PERSPECTIVES
↓
5. EXTRACT AGREEMENTS / DISAGREEMENTS
↓
6. IDENTIFY MISSING EVIDENCE
↓
7. GENERATE QUESTIONS OR REQUEST DATA
↓
8. HUMAN REVIEW
↓
9. UPDATE MODEL
↓
10. REPEAT UNTIL DECISION QUALITY IS SUFFICIENT
```

## Output

The orchestrator should return:

- strongest current hypothesis
- evidence for and against
- confidence
- unresolved contradictions
- alternative explanations
- evidence required next
- recommended next action
- what would falsify the recommendation

## Decision boundary

> **AI proposes. Evidence constrains. Humans decide. Outcomes judge.**

The system should be comfortable stopping with:

> **Insufficient evidence. Do not decide yet.**

That is a valid output.
