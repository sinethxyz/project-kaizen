# Project Kaizen

> A reasoning system for understanding enterprises deeply, debugging organisational gaps, and deciding what technology actually matters.

This repository is not a finished business plan, manifesto, or set of instructions. It is a reasoning logic for Mattia and Riccardo to attack, test, simplify, and evolve.

## The invariant

> **The enterprise is the invariant. AI is a variable.**

The enterprise itself evolves, but it remains the enduring object we are trying to understand, improve, and help persist.

AI changes. Models change. Vendors change. Cloud architectures change. Software categories change. The next technological wave will change too.

The enterprise remains the centre of gravity.

## Persist mission

From Sineth's point of view, Persist's mission should be:

> **Understand enterprises deeply enough to know what any new technology actually means for them and how to debug or close the gaps inside the enterprise.**

That means two things.

First, understand what changed and what it means for this specific enterprise.

Second, find the gap between how the enterprise works today and how it needs to work, then decide what should be fixed, redesigned, connected, removed, automated, or left alone.

```text
UNDERSTAND THE ENTERPRISE
↓
UNDERSTAND THE CHANGE
↓
IDENTIFY THE GAP
↓
DIAGNOSE
↓
ROUTE TO THE RIGHT CAPABILITY
↓
DEPLOY THE MINIMUM SUFFICIENT INTERVENTION
↓
MEASURE
↓
LEARN
↺
```

The objective is not more technology. The objective is a better enterprise.

## Five lines

> **Technologies change.**  
> **Markets change.**  
> **Systems change.**  
> **Companies either adapt or die.**  
> **Persist.**

## Core principles

> **Business first. Systems second. Technology third. AI somewhere much later.**

Technology should be selected after diagnosis, not before it.

> **The problem should determine the capability. The capability should not determine the problem.**

> **Understand deeply. Change only what needs changing.**

> **AI proposes. Evidence constrains. Humans decide. Outcomes judge.**

> **The model is not the truth. The model is a machine for finding the truth.**

## Why enterprise focus changes hiring

A company's workforce quietly shapes the problems it sees.

```text
WE HIRE AI SPECIALISTS
↓
WE BECOME VERY GOOD AT AI
↓
WE LOOK FOR AI OPPORTUNITIES
↓
WE SELL AI PROJECTS
↓
WE HIRE MORE AI SPECIALISTS
↺
```

There is nothing inherently wrong with that model if a company has already chosen AI transformation as its problem space.

Tenex is a useful contrast. Its public model is explicitly focused on AI transformation, so hiring AI engineers, AI strategists, and forward deployed operators follows naturally from the category it has chosen.

Project Kaizen starts one level earlier:

> **What does this enterprise actually need?**

One company may need AI engineering. Another may need ERP expertise, cybersecurity, data architecture, process redesign, organisational change, or no substantial new technology at all.

Persist should still hire. But permanent hiring should concentrate on the capabilities that define Persist itself: enterprise understanding, diagnosis, orchestration, client trust, quality control, measurement, and learning.

Specialist depth can then be assembled around the problem through a trusted capability network.

The principle is not "do not hire."

It is:

> **Do not let your payroll define your diagnosis.**

A large fixed specialist workforce creates utilisation pressure. That is organisational gravity. Project Kaizen tries to design against it.

## The enterprise model

An enterprise is not only a technical system. It is also economic, human, political, historical, and behavioural.

A useful model includes:

```text
structure
systems
data
economics
processes
people
incentives
power
history
behaviour
market
technology
```

The formal company and the real company are often different.

## LLM and agents are separate layers

The LLM layer is the reasoning substrate. It represents the enterprise, tracks evidence and uncertainty, preserves context, and helps form hypotheses.

The agent layer creates adversarial pressure on that reasoning.

Project Kaizen keeps the agent architecture deliberately small with six core perspectives:

1. Systems
2. Economics and Customer
3. Human and Power
4. History and Founder
5. Technology
6. Red Team

They are perspectives, not autonomous authorities.

```text
ENTERPRISE EVIDENCE
↓
LLM ENTERPRISE MODEL
↓
SIX ADVERSARIAL PERSPECTIVES
↓
CONTRADICTIONS
↓
BETTER QUESTIONS
↓
NEW EVIDENCE
↓
UPDATED MODEL
↺
```

## What counts as better?

Technology adoption is not the outcome.

A useful intervention should improve one or more of:

- truth
- coherence
- decision quality
- execution
- adaptability

If none improve, ask why the intervention exists.

## Internal doctrine, not service sprawl

Project Kaizen does not mean Persist should operationally do everything.

Persist may spend years primarily selling AI modernisation. That is compatible with the model.

```text
WHAT WE SELL TODAY
≠
WHAT WE MUST ALWAYS BE
```

Operational specialisation is useful. Intellectual rigidity is not.

## Repository map

- [`core/`](./core/) — the thesis, principles, and boundaries
- [`enterprise/`](./enterprise/) — what an enterprise is and how to map it
- [`method/`](./method/) — diagnose, route, deploy, measure, learn
- [`llm/`](./llm/) — how the reasoning layer represents evidence, context, uncertainty, and learning
- [`agents/`](./agents/) — six adversarial reasoning roles and how they interact
- [`strategy/`](./strategy/) — positioning, moat, and evolution
- [`evidence/`](./evidence/) — competitors, history, cases, patterns, sources, and falsification
- [`templates/`](./templates/) — practical working artefacts

## How to use this repo

1. Read [`FOR-MATTIA-AND-RICCARDO.md`](./FOR-MATTIA-AND-RICCARDO.md).
2. Read [`ONE-PAGE-LOGIC.md`](./ONE-PAGE-LOGIC.md).
3. Read deeper only where useful.
4. Connect the repository to an AI tool.
5. Run [`PROMPT.md`](./PROMPT.md).
6. Use [`AI-REVIEW.md`](./AI-REVIEW.md) to attack the model.
7. Test whatever survives against real customers, operators, economics, and outcomes.

Do not preserve this repo because it is elegant.

**Attack it. Change it. Delete what fails. Keep what survives.**
