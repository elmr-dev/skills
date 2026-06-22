# Contributing

## Adding a skill

A skill is a directory with a `SKILL.md` in it. The directory name is the skill
name; keep it short and kebab-case.

The frontmatter is load-bearing. `name` matches the directory; `description` is
the trigger — an agent reads it to decide *whether to load the skill for a given
task*, so write it as a clear "use this when…", not a summary of what's inside.
If the description doesn't say when to reach for the skill, the skill won't get
reached for.

```markdown
---
name: your-skill
description: >-
  Use when … — the specific situations that should pull this skill in. Name the
  triggers, not the contents.
---

# Your skill

The canon goes here — rules, examples, the reasoning that travels with them.
```

One real skill beats a tree of empty scaffolding. Add a skill when there's an
actual second consumer for it — the same "apps earn it first" rule, applied to
how we work. Don't pre-create placeholder directories for skills you might write
later; add the directory when you have the skill to put in it.

Look at [`copy-voice`](./copy-voice/SKILL.md) for the shape to follow.

## Sending the change

Skills live in a repo, not in any one person's Claude memory, so the canon is
shared and the diff is the conversation. Open a PR; when the canon changes,
that's where it gets discussed.
