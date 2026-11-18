# Smolnikov Research Skill - `pomerado-mcp`

> **Category:** Browser & Web-to-MCP (On-Demand) · **License:** MIT · **Author:** [Smolnikov Research Center](https://github.com/SmolnikovResearch)

**EN:** Turn websites without APIs into on-demand MCP tools.

**RU:** Превращение HAR-трейсов и веб-потоков без API в типизированные MCP-инструменты по требованию.

---

## On-Demand Activation & Lazy Loading (`on-demand.json`)

This skill stays **disabled by default** (`auto_load_on_startup: false`) and loads dependencies/checkpoints strictly when you enable and run it:

| Component | Requirement |
|---|---|
| System binaries | `pomerado` |
| Python packages | `none (stdlib)` |
| Model checkpoints | `none` |

## Installation in CapyAgent

```bash
capyagent skills install SmolnikovResearch/pomerado-mcp/skills/pomerado-mcp
```

Or copy this directory into `~/.capyagent/skills/` (or `~/.agents/skills/`).

## Check Status & Bootstrap Dependencies

```bash
python3 scripts/optional_skill_bootstrap.py pomerado-mcp --status
python3 scripts/optional_skill_bootstrap.py pomerado-mcp --install
```

See [`SKILL.md`](SKILL.md) for agent instructions and workflow examples.

## Related

- Full multi-skill catalog: [SmolnikovResearch/skills](https://github.com/SmolnikovResearch/skills)
- License: [MIT](LICENSE)
