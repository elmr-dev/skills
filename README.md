# skills

A personal skills tap for agent skills, installable via [Homecrew](https://crew.logic.inc).

Each skill is a `SKILL.md` under a named directory. The frontmatter `description`
says *when* the skill applies; an agent matches against it to decide whether to
load the skill for a given task. The body is the canon — rules, examples, the
reasoning that travels with them.

These live in a repo, not in any one person's Claude memory, on purpose: a brain
is per-person and drifts; a repo is shared, versioned, and changes in the open via
PR. When the canon changes, the diff is the conversation.

## Install with Homecrew

[Homecrew](https://crew.logic.inc) treats this repo as a *tap* — a source of
skills you can install and keep current from the command line.

Add the tap:

```sh
crew tap add @elmr-dev/skills
```

Install a skill:

```sh
crew install elmr-dev/copy-voice
```

Keep installed skills current:

```sh
crew update
```

## Skills

- **copy-voice** — the elmr copy voice. Load before writing or reviewing any
  elmr-facing text (site, READMEs, Discord, deploy/CI messages, releases,
  release notes, social posts).

## Adding a skill

One real skill beats a tree of empty scaffolding. Add a skill when there's an
actual second consumer for it — the same "apps earn it first" rule, applied to how
we work. A new skill is a directory with a `SKILL.md`; the `description` frontmatter
is load-bearing, so write it as a clear *when to use this*.

## License

MIT — see [LICENSE](./LICENSE).
