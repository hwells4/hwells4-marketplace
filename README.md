# hwells4-plugins

A Claude Code plugin marketplace.

## Installation

```bash
/plugin marketplace add hwells4/hwells4-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **create-hook** | Scaffold Claude Code hooks with templates, validation, and conflict analysis |

### Install a plugin

```bash
/plugin install create-hook
```

## Adding More Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json`:

```json
{
  "name": "new-plugin",
  "description": "What it does",
  "version": "1.0.0",
  "source": {
    "source": "github",
    "repo": "hwells4/new-plugin-repo"
  }
}
```
