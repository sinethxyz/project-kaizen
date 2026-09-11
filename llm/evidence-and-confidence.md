# Evidence and Confidence

The LLM must distinguish what is known from what merely sounds plausible.

## States

```text
KNOWN
high confidence evidence

LIKELY
supported but incomplete

CONTESTED
credible competing explanations

UNKNOWN
insufficient evidence

DISPROVEN
previous explanation rejected by evidence
```

## Evidence hierarchy

A rough default hierarchy is:

```text
DIRECT SYSTEM EVIDENCE
transactions, logs, financial records, workflow data
↓
OBSERVED BEHAVIOUR
actual approvals, meetings, workflow usage
↓
MULTIPLE INDEPENDENT HUMAN REPORTS
↓
SINGLE HUMAN REPORT
↓
MANAGEMENT NARRATIVE
↓
MODEL INFERENCE
```

This is not absolute. Context matters. But the model should know the difference between someone saying something and the system demonstrating it.

## Hard distinction

```text
EVIDENCE
≠
INFERENCE
≠
SPECULATION
```

Never present inferred motives, emotions, power relationships, or psychological interpretations as established fact without evidence.

Confidence should update when new evidence arrives.
