# Obsidian Memory for Hermes

Browse, search, and edit your Obsidian vault notes directly from the Hermes dashboard.

## Features

- **Multi-vault support** — auto-discovers all Obsidian vaults, switchable via dropdown
- **Graph visualization** — force-directed graph with curved edges, node dragging, zoom controls
- **Note viewer** — full markdown rendering (code blocks, tables, callouts, checkboxes, wikilinks)
- **Inline editing** — edit notes directly from the dashboard with save/cancel
- **Search & filter** — search by name, filter by folder or tag
- **Backlinks** — see which notes link to the current note, click to navigate

## Install

```bash
hermes plugins install kyssta-exe/hermes-obsidian-memory
```

## Configuration

Set your vault path (auto-discovers vaults with `.obsidian` directory):

```bash
# Optional: override primary vault path
export OBSIDIAN_VAULT_PATH=/path/to/your/vault
```

By default, the plugin scans for Obsidian vaults in:
- The primary vault path (env or `/home/ubuntu/ObsidianVault`)
- Sibling directories of the primary vault
- `~/Documents/Obsidian/`
- `~/obsidian-vaults/`
- `~/vaults/`

## Usage

After install, the **OBSIDIAN** tab appears in the dashboard sidebar.

- Click a note to view it
- Click **Edit** to modify note content
- Click `[[wikilinks]]` to navigate between notes
- Use the vault dropdown to switch between vaults
- Graph view: drag nodes, scroll to zoom, click to open note

## Requirements

- Hermes Agent with dashboard enabled
- Obsidian vault(s) on the host machine

## License

MIT
