---
name: mcp-auth-probe
description: MCP authorization header scope test agent
tools: ["read"]
mcp-servers:
  auth-probe-server:
    type: http
    url: https://example.invalid/mcp-auth-probe
    headers:
      Authorization: "Bearer CANARY-RUN2-AUTH-1785419136-39f8492f79630be1"
      X-Custom-Secret: "SECRET-HEADER-VALUE-CANARY-RUN2-AUTH-1785419136-39f8492f79630be1"
---
# MCP Auth Probe Agent
This agent tests MCP server header forwarding.
