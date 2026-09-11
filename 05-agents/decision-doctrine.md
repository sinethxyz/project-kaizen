# Decision Doctrine

AI agents are reasoning instruments, not authorities.

Persist should use agents to generate hypotheses, expose contradictions, search for evidence, simulate alternatives, and challenge decisions. They should not silently become the decision-maker.

The governing rule is:

> **AI proposes. Evidence constrains. Humans decide. Outcomes judge.**

## Why

A multi-agent system can still be wrong in a coordinated way. More agents do not automatically create truth. They can share the same missing context, repeat the same assumptions, or produce persuasive explanations unsupported by enterprise reality.

Therefore:

```text
AGENT OUTPUT
↓
EVIDENCE CHECK
↓
UNCERTAINTY / DISAGREEMENT
↓
HUMAN JUDGMENT
↓
CONTROLLED ACTION
↓
OUTCOME
↓
MODEL UPDATE
```

## Rules

1. Agents must distinguish evidence, inference, and speculation.
2. Important recommendations should expose disagreement rather than hide it.
3. Confidence should never substitute for evidence.
4. High-impact or difficult-to-reverse interventions require stronger evidence and explicit human accountability.
5. When evidence is insufficient, the correct answer may be: **we do not know yet**.
6. Outcomes feed back into the model and can falsify both human and agent reasoning.

The purpose of adversarial intelligence is not to automate conviction.

It is to make decisions harder to fool.
