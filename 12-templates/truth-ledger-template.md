# Truth Ledger Template

| Claim | State | Confidence | Evidence | Contradictions | Owner | Next evidence |
|---|---|---:|---|---|---|---|
| Example claim | CONTESTED | 0.55 | Interviews + logs | Finance disagrees | Operator | Pull transaction data |

Allowed states:

- **KNOWN**
- **LIKELY**
- **CONTESTED**
- **UNKNOWN**
- **DISPROVEN**

Never upgrade a claim because it is repeated often. Upgrade it because evidence improves.
