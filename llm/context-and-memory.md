# Context and Memory

Enterprise reasoning is temporal. The model needs enough context to understand how today's state emerged and how previous interventions changed it.

## Per enterprise context

Useful memory includes:

- business model and objectives
- organisational structure
- systems and data model
- important entities and workflows
- decision rights
- known constraints
- key historical events
- assumptions and hypotheses
- unresolved questions
- interventions
- measured outcomes
- previous mistakes in the model

## Time matters

Do not overwrite history with the latest state.

A useful representation should preserve changes over time:

```text
STATE A
↓
EVENT / INTERVENTION
↓
STATE B
↓
OUTCOME
↓
LEARNING
```

## Isolation

Enterprise memory should be tenant isolated by default.

Cross enterprise pattern learning must not create cross client disclosure.

A reasoning system can learn that a pattern exists without revealing the confidential details of the client from which the pattern was learned.
