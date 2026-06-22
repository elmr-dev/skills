# skills

Agent skills for working on [elmr](https://github.com/elmr-dev) — shared so that
everyone's Claude works from the same canon instead of each from its own memory.

Each skill is a `SKILL.md` under a named directory. The frontmatter `description`
says *when* the skill applies; an agent matches against it to decide whether to
load the skill for a given task. The body is the canon — rules, examples, the
reasoning that travels with them.

These live in a repo, not in any one person's Claude memory, on purpose: a brain
is per-person and drifts; a repo is shared, versioned, and changes in the open via
PR. When the canon changes, the diff is the conversation.

## Skills

- **copy-voice** — the elmr copy voice. Load before writing or reviewing any
  elmr-facing text (site, READMEs, Discord, deploy messages, releases).

## Using a skill

Two paths, depending on how you work:

- **Claude Code** discovers `SKILL.md` files in the repo natively. Clone or
  reference this repo and the skills are available.
- **claude.ai / desktop** doesn't auto-sync from a repo. Point your Claude at it:
  add a line to your preferences along the lines of *"when writing elmr copy, read
  the copy-voice skill from elmr-dev/skills first."* Your Claude reads it via the
  GitHub or filesystem tools at the start of the task.

Either way the repo is the source of truth and loading is per-person. That's the
trade — slightly manual, but the canon lives somewhere everyone can pull, not in a
brain someone has to be granted access to.

## Adding a skill

One real skill beats a tree of empty scaffolding. Add a skill when there's an
actual second consumer for it — the same "apps earn it first" rule, applied to how
we work. A new skill is a directory with a `SKILL.md`; the `description` frontmatter
is load-bearing, so write it as a clear *when to use this*.

## License

MIT — see [LICENSE](./LICENSE).
