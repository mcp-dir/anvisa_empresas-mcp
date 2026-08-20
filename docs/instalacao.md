# Instalação detalhada

ANVISA: Funcionamento de Empresa Nacional é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_anvisa_empresas`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_anvisa_empresas` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_anvisa_empresas` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_anvisa_empresas` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.anvisa_empresas` (ou `servers.anvisa_empresas` no VS Code) do config do cliente e reinicie.
