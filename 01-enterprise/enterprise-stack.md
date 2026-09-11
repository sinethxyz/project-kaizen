# Enterprise Stack

A diagnostic heuristic for locating where a problem may actually live.

```text
L11  Adaptive / autonomous systems
L10  AI / generative intelligence
L9   Prediction / optimisation
L8   Automation
L7   Decision systems
L6   Process design
L5   Analytics
L4   Observability
L3   Organisation / ownership
L2   Data foundations
L1   Connectivity
```

The stack is not natural law. Layers overlap and some enterprises will skip or combine them.

Its purpose is to prevent premature diagnosis.

> **A visible problem at a high layer may be caused by a lower layer.**

Example:

```text
"We need an AI support agent"
↓
Support is slow
↓
Staff search five systems
↓
Customer records conflict
↓
No canonical customer identity
```

The request appears at L10. The root problem may be L2.
