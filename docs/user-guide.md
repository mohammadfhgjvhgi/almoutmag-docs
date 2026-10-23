# User Guide

## Connect Claude Desktop

Edit claude_desktop_config.json:

    {
      "mcpServers": {
        "almoutmag": {
          "url": "https://TUNNEL-URL/mcp",
          "headers": { "Authorization": "Bearer TOKEN" }
        }
      }
    }

## Troubleshooting
- Tunnel: use --protocol http2
- Server: check tunnel_logs/server.err