[![Add to Cursor](https://fastmcp.me/badges/cursor_dark.svg)](https://fastmcp.me/MCP/Details/1610/mac-apps-launcher)
[![Add to VS Code](https://fastmcp.me/badges/vscode_dark.svg)](https://fastmcp.me/MCP/Details/1610/mac-apps-launcher)
[![Add to Claude](https://fastmcp.me/badges/claude_dark.svg)](https://fastmcp.me/MCP/Details/1610/mac-apps-launcher)
[![Add to ChatGPT](https://fastmcp.me/badges/chatgpt_dark.svg)](https://fastmcp.me/MCP/Details/1610/mac-apps-launcher)
[![Add to Codex](https://fastmcp.me/badges/codex_dark.svg)](https://fastmcp.me/MCP/Details/1610/mac-apps-launcher)
[![Add to Gemini](https://fastmcp.me/badges/gemini_dark.svg)](https://fastmcp.me/MCP/Details/1610/mac-apps-launcher)

# Mac Apps Launcher MCP Server

A Model Context Protocol (MCP) server for launching and managing macOS applications.

## Features

- List all applications installed in the `/Applications` folder
- Launch applications by name
- Open files with specific applications

## Installation
Add the following to your Claude Config JSON file
```
{
  "mcpServers": {
    "simulator": {
      "command": "npx",
      "args": [
        "y",
        "@joshuarileydev/mac-apps-launcher-mcp-server"
      ]
    }
  }
}
```