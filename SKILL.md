---
name: logical-thinking-process
description: "Use when analyzing complex problems, finding root causes of systemic issues, resolving conflicts or dilemmas, challenging assumptions, planning changes with if-then logic, or when Theory of Constraints or Logical Thinking Process is mentioned"
---

# Logical Thinking Process

## Overview

Guide the user through the 5-phase Logical Thinking Process as a collaborative dialogue, using if-then cause-and-effect logic to move from problem identification to actionable transition plan.

Based on Eliyahu Goldratt's Theory of Constraints thinking processes, as systematized by H. William Dettmer in *The Logical Thinking Process: A Systems Approach to Complex Problem Solving* (2007).

<HARD-GATE>
Do NOT skip phases or rush ahead. Ask ONE question at a time. Get explicit user confirmation before advancing to the next phase. The user is the domain expert — you facilitate the logic.
</HARD-GATE>

## Starting the Dialogue

1. Understand the scope: what system or situation is the user trying to improve?
2. Ask the user to identify 3-5 Undesirable Effects (UDEs) — things that are wrong, frustrating, or underperforming
3. Prefer multiple choice when possible, open-ended when needed

## Phase 1: Current Reality Tree (CRT)

**Goal:** Find the root cause(s) behind the UDEs.

- Take each UDE and ask "why does this happen?" to build if-then causal chains
- Present chains incrementally: "IF [cause] THEN [effect] — does this match your experience?"
- Connect chains where causes overlap
- Converge on 1-2 root causes that drive most UDEs
- Confirm with user: "These root causes explain most of your problems. Agree?"

## Phase 2: Evaporating Cloud (EC)

**Goal:** Surface and break the core conflict preventing improvement.

- Frame the conflict as 5 boxes:
  - **A** — Common objective (what both sides want)
  - **B** — Need #1 (one requirement for A)
  - **C** — Need #2 (another requirement for A)
  - **D** — Want for B (action/condition that satisfies B but conflicts with D')
  - **D'** — Want for C (action/condition that satisfies C but conflicts with D)
- Present the cloud and confirm the user recognizes the conflict
- List assumptions behind each arrow (A-B, B-D, A-C, C-D', D-D')
- Challenge each assumption: "Is this always true? Under what conditions could it be false?"
- Identify the breakable assumption
- Propose an injection — an action or condition that breaks the assumption and dissolves the conflict

## Phase 3: Future Reality Tree (FRT)

**Goal:** Verify the injection solves the problem without creating new ones.

- Build if-then logic forward: "IF [injection] THEN [expected effect]..."
- Walk the chain until all original UDEs are resolved (turned into Desirable Effects)
- Check for Negative Branch Reservations (NBRs): "Could this injection cause any new problems?"
- If NBRs found, add trimming actions and re-verify
- Confirm with user the future state is acceptable

## Phase 4: Prerequisite Tree (PRT)

**Goal:** Identify what stands in the way of implementing the injection.

- Ask: "What obstacles prevent you from implementing this change?"
- For each obstacle, define an Intermediate Objective (IO) that overcomes it
- Sequence IOs by dependency — what must happen first?
- Present the sequence and confirm

## Phase 5: Transition Tree (TT)

**Goal:** Create specific, actionable steps.

- For each IO, define concrete actions with cause-effect justification:
  - "I need [action] BECAUSE [reason] which will produce [expected result]"
- Sequence actions in implementation order
- Present the full action plan and confirm

## Saving Output

After completing the process (or any meaningful subset), save results to:

```
docs/thinking/YYYY-MM-DD-<topic>.md
```

Include sections for each completed phase with the if-then logic, conflict cloud, and action plan.

## References

- [Thinking Processes (Theory of Constraints) — Wikipedia](https://en.wikipedia.org/wiki/Thinking_processes_(theory_of_constraints))
- [Theory of Constraints — Wikipedia](https://en.wikipedia.org/wiki/Theory_of_constraints)
- Dettmer, H. W. — *The Logical Thinking Process* (2007) — definitive guide to all five tools
- Goldratt, E. M. — *It's Not Luck* (1994) — demonstrates the Thinking Processes in practice
- Goldratt, E. M. — *The Goal* (1984) — the novel that introduced Theory of Constraints

## Key Principles

- **One question at a time** — never overwhelm with multiple questions
- **Multiple choice preferred** — easier to answer than open-ended
- **Validate before advancing** — explicit confirmation at each phase gate
- **If-then backbone** — every connection must be a testable causal statement
- **Challenge assumptions explicitly** — assumptions are where breakthroughs hide
- **Plain language** — avoid jargon; use simple cause-and-effect framing
- **User is domain expert** — you provide the logical structure, they provide the knowledge
