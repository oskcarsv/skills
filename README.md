# skills

[![skills.sh](https://skills.sh/b/oskcarsv/skills)](https://skills.sh/oskcarsv/skills)

General skills by Oscar Morales for Claude Code, Codex, Cursor and any agent supported by the [`skills` CLI](https://www.skills.sh/docs/cli). Everything here is generic: no personal, company or client information. Skills that carry that kind of context live in a private repo.

## Install

    npx skills add oskcarsv/skills

Pick specific skills with `--skill <name>`, or `--all` for every skill in the repo. Update later with `npx skills update`.

## Structure

    skills/<skill-name>/SKILL.md

Each skill is a folder with a `SKILL.md` (`name` and `description` frontmatter, then the instructions) plus any supporting files. See the [skills.sh docs](https://www.skills.sh/docs).

## License

MIT.
