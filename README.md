# Logical Thinking Process Skill

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code/skills) that guides you through Goldratt's 5-phase Logical Thinking Process as a collaborative dialogue.

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

## License

MIT
