# HA MCP Tools

Custom component for [ha-mcp](https://github.com/homeassistant-ai/ha-mcp) server.

Provides services that are not available through standard Home Assistant APIs, enabling AI assistants to perform advanced operations like file management.

## Installation

This component is designed to be installed via HACS as a custom repository.

## Services

### `ha_mcp_tools.list_files`

List files in a directory within the Home Assistant config directory.

| Field | Required | Description |
|-------|----------|-------------|
| `path` | Yes | Relative path from config directory (e.g., "www/", "themes/") |
| `pattern` | No | Optional glob pattern to filter files (e.g., "*.css") |

**Allowed directories:** `www`, `themes`, `custom_templates`

## License

MIT License - See [ha-mcp](https://github.com/homeassistant-ai/ha-mcp) for details.
