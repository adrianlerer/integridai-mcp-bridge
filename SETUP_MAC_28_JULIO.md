# SETUP INTEGRIDAI + N8N-MCP EN MAC (28/7)

## 1. Instalar n8n-mcp bridge
npm install -g @czlonkowski/n8n-mcp

## 2. Configurar Claude Desktop
# Editar: ~/Library/Application Support/Claude/claude_desktop_config.json
{
  "mcpServers": {
    "n8n-mcp": {
      "command": "npx",
      "args": ["@czlonkowski/n8n-mcp"],
      "env": {
        "N8N_HOST": "tu-n8n-hostinger-url",
        "N8N_API_KEY": "tu-api-key"
      }
    }
  }
}

## 3. Conectar con FLAISIMULATOR (localhost:8000)
# Workflows automáticos universidad

## 4. Test university demos
