# Soul Change

You have access to the Soul Change MCP server, which lets you browse and apply AI personas from ClawSouls.

## Available Tools

- **search_souls**: Search for AI personas by keyword, category, or tag
- **get_soul**: Get detailed information about a specific persona  
- **apply_persona**: Apply a persona to change your behavior
- **preview_soul**: Preview a persona's files before applying
- **install_soul**: Install a persona package to local directory
- **list_categories**: List all available persona categories

## Usage

When the user asks to change personality, browse personas, or apply a soul:

1. Use `search_souls` or `list_categories` to help them find a persona
2. Use `preview_soul` to show what the persona includes
3. Use `apply_persona` to apply it

## Examples

- "Show me all coding personas" → `search_souls` with query "coding"
- "Apply the brad persona" → `get_soul` then `apply_persona`
- "What categories are available?" → `list_categories`
