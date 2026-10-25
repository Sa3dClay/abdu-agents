# abdu-agents

A Claude Code plugin marketplace.

| Plugin | What it does |
|---|---|
| `pipeline` | Idea-to-build agent pipeline: Lens → Atlas → Anvil → Assay, orchestrated in GitHub Actions by Foreman |

## Install

```
/plugin marketplace add Sa3dClay/abdu-agents
/plugin install pipeline@abdu-agents
```

In GitHub Actions (`anthropics/claude-code-action`):

```yaml
plugin_marketplaces: "https://github.com/Sa3dClay/abdu-agents.git"
plugins: "pipeline@abdu-agents"
```
