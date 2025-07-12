# mcp-sticky-notes-demo
A simple demo that allows LLMs to save and read sticky notes in the browser.


# 📒 MCP Sticky Notes Demo

A simple MCP-B demo that allows LLMs to save and read sticky notes in the browser.

## How it works

- Defines two tools (`saveNote`, `readNote`) via `window.mcp`.
- Any MCP-compatible client (e.g., Claude Desktop, Glama.ai, LobeHub) can auto-detect and invoke these actions.

## 🧑‍💻 Setup

### Local Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/shadabsayani/mcp-sticky-notes-demo.git
   cd mcp-sticky-notes-demo
