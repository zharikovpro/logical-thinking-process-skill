# Logical Thinking Process Skill

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code/skills) that guides you through the 5-phase [Logical Thinking Process](https://en.wikipedia.org/wiki/Thinking_processes_(theory_of_constraints)) as a collaborative dialogue.

Based on [Eliyahu Goldratt](https://en.wikipedia.org/wiki/Eliyahu_M._Goldratt)'s [Theory of Constraints](https://en.wikipedia.org/wiki/Theory_of_constraints) thinking processes, as systematized by [H. William Dettmer](https://logicalthinkingprocess.podia.com/).

## What it does

Facilitates structured problem-solving using if-then cause-and-effect logic across five phases:

1. **Current Reality Tree** — find root causes behind undesirable effects
2. **Evaporating Cloud** — surface and break the core conflict
3. **Future Reality Tree** — verify the solution works without side effects
4. **Prerequisite Tree** — identify obstacles and intermediate objectives
5. **Transition Tree** — create specific, actionable steps

## Install

Add to your Claude Code settings (`.claude/settings.json`):

```json
{
  "skills": [
    "https://github.com/zharikovpro/logical-thinking-process-skill"
  ]
}
```

Or add to project settings (`.claude/settings.local.json`) for a specific project.

## Usage

The skill activates automatically when you:
- Analyze complex problems or systemic issues
- Look for root causes
- Resolve conflicts or dilemmas
- Challenge assumptions
- Plan changes with if-then logic
- Mention Theory of Constraints or Logical Thinking Process

You can also invoke it directly: `/logical-thinking-process`

## Background

The [Thinking Processes](https://en.wikipedia.org/wiki/Thinking_processes_(theory_of_constraints)) were developed by Eliyahu M. Goldratt as part of his [Theory of Constraints](https://en.wikipedia.org/wiki/Theory_of_constraints). H. William Dettmer refined and systematized these tools into what he called the Logical Thinking Process, adding the Goal Tree and clarifying the relationships between the tools.

### Recommended reading

- **Goldratt, E. M.** *[The Goal](https://www.amazon.com/dp/0884271951)* (1984) — the novel that introduced Theory of Constraints
- **Goldratt, E. M.** *[It's Not Luck](https://www.amazon.com/dp/0884271153)* (1994) — demonstrates the Thinking Processes applied to business strategy
- **Dettmer, H. W.** *[Goldratt's Theory of Constraints: A Systems Approach to Continuous Improvement](https://www.amazon.com/dp/0873893700)* (1997) — systematic introduction to TOC tools
- **Dettmer, H. W.** *[The Logical Thinking Process: A Systems Approach to Complex Problem Solving](https://www.amazon.com/dp/0873897234)* (2007) — the definitive guide to all five thinking process tools
- **Scheinkopf, L. J.** *[Thinking for a Change](https://www.amazon.com/dp/1574441035)* (1999) — concise guide to the classical TOC Thinking Processes

## License

MIT
