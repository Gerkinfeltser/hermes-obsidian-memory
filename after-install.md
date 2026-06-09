## Obsidian Memory installed

The **OBSIDIAN** tab is now available in your Hermes dashboard.

### Quick Start

1. Open the dashboard (`hermes dashboard`)
2. Click the **OBSIDIAN** tab in the sidebar
3. Your vault notes will appear automatically

### Multi-Vault

The plugin auto-discovers vaults by looking for `.obsidian` directories. If you have multiple vaults, a dropdown will appear in the header to switch between them.

### Custom Vault Path

To point to a specific vault:

```bash
export OBSIDIAN_VAULT_PATH=/path/to/your/vault
```

Add this to `~/.hermes/.env` to persist it.
