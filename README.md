# Foundational AI Plugins

This repo contains Foundational's plugins for AI models and agentic workflows.

## Cursor

The repo is a Cursor plugin marketplace. `.cursor-plugin/marketplace.json` at the root lists each plugin by its `source` folder, so the plugins live under `plugins/`.

```
.cursor-plugin/marketplace.json      lists the plugins
plugins/foundational/
  .cursor-plugin/plugin.json         plugin manifest
  mcp.json                           the Foundational MCP server (remote, OAuth)
  assets/logo.png                    listing logo
  README.md
```

| Plugin | What it does |
|---|---|
| [foundational](plugins/foundational/README.md) | Connects Cursor to your organization's Foundational lineage graph through the Foundational MCP server. |

### Rules the manifests follow

- A plugin's `name` in `marketplace.json` equals its `name` in its `plugin.json`.
- Manifest paths are relative, with no `..`.
- The manifests accept only the fields in Cursor's schemas.

### Try a change locally

In Cursor, add this repo's folder as a local marketplace and install the plugin. Cursor reads the folder as a git repository, so commit a change before Cursor can see it, then reinstall the plugin.
