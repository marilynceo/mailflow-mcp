# mailflow-mcp

Multi-account email management u2014 send, read, search, filter, and manage emails across Gmail, Outlook, and IMAP accounts u2014 directly from your AI agent.

## Quick Start

```bash
git clone https://github.com/marilynceo/mailflow-mcp.git
cd mailflow-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://mailflow.zhc-mcp.org

## Tools

| Tool | Description |
|------|-------------|
| `send_email` | Recipient email address |
| `read_inbox` | Account name |
| `search_emails` | Search query (subject, from, body text) |
| `list_accounts` | List all configured email accounts with status |

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/mailflow-mcp

# Or connect directly via MCP client
# Endpoint: https://mailflow.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
