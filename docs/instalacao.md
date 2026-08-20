# Instalação detalhada

Prefeitura PB Mataraca: Certidão Negativa de Débitos é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_pref_pb_mataraca_cnd`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_pref_pb_mataraca_cnd` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_pref_pb_mataraca_cnd` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_pref_pb_mataraca_cnd` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.pref_pb_mataraca_cnd` (ou `servers.pref_pb_mataraca_cnd` no VS Code) do config do cliente e reinicie.
