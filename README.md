# Contextli for Cursor

Contextli is a context-aware AI dictation and notes app for Mac, Windows and iPhone. This plugin connects Cursor to your Contextli notes through the hosted MCP server.

## Install

Add this plugin from Cursor Directory, or add the server by hand to your `mcp.json`:

```json
{
  "mcpServers": {
    "contextli": {
      "url": "https://mcp.contextli.com/mcp"
    }
  }
}
```

Cursor opens a sign-in page the first time a tool is used. No API key is stored in this repository.

## Contents

- `mcp.json`: the remote MCP server definition
- `skills/contextli-notes/SKILL.md`: guidance for the agent

Docs: https://contextli.com/integrations/mcp

Maintained by [Ertiqah LLC](https://ertiqah.com). Licence: MIT.
