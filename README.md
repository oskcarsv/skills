# skills

[![skills.sh](https://skills.sh/b/oskcarsv/skills)](https://skills.sh/oskcarsv/skills)

Skills públicas de Oscar Morales para Claude Code, Codex, Cursor y cualquier agente que siga el estándar [Agent Skills](https://agentskills.io).

## Instalar

Claude Code:

    claude plugin marketplace add oskcarsv/skills
    claude plugin install <plugin>@oskcarsv

Cualquier agente con la CLI `skills`:

    npx skills add oskcarsv/skills

## Estructura

    plugins/<plugin>/skills/<skill>/SKILL.md

Cada skill es una carpeta con `SKILL.md` y, opcionalmente, `references/`, `scripts/` y `assets/`.

## Licencia

MIT.
