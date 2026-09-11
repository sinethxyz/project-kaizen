# Enterprise Reasoning Model

The LLM should not begin by producing recommendations.

Its first job is to construct and maintain a useful representation of the enterprise.

```text
RAW CONTEXT
↓
STRUCTURED ENTERPRISE REPRESENTATION
↓
HYPOTHESES
↓
EVIDENCE FOR / AGAINST
↓
CONFIDENCE
↓
OPEN QUESTIONS
↓
UPDATED REPRESENTATION
```

## What it reasons over

The model should be capable of relating:

- structure
- systems
- data
- economics
- processes
- people
- incentives
- power
- history
- behaviour
- market
- technology

The important part is the relationships between them.

Example:

```text
FRAGMENTED CUSTOMER DATA
may be caused by
TECHNICAL SCHEMAS
or
BUSINESS UNIT OWNERSHIP
or
INCENTIVES
or
HISTORICAL ACQUISITIONS
or
several of these together
```

## Hypothesis first

Prefer explicit hypotheses over polished certainty.

Each important hypothesis should carry:

- claim
- evidence for
- evidence against
- confidence
- falsifier
- evidence required next

The model should be comfortable saying:

> **We cannot answer this yet.**

That is higher quality reasoning than confident fabrication.
