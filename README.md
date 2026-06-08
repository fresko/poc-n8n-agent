# PoC: n8n + MCP desde GitHub App

PoC para conectar **n8n** con un servidor **MCP** usando una **GitHub App** y crear los primeros flujos desde un agente.

## Flujo (pixel ASCII)
```text
┌───────────────┐      ┌───────────────┐      ┌───────────────┐
│  GitHub App   │ ───▶ │  MCP Server   │ ───▶ │      n8n      │
└───────────────┘      └───────────────┘      └───────┬───────┘
                                                       │
                                                       ▼
                                               ┌───────────────┐
                                               │ Agent Flows   │
                                               │ (create/run)  │
                                               └───────────────┘
```

## Alcance inicial
- Conexión de n8n al MCP.
- Autenticación vía GitHub App.
- Creación de flujos base desde un agente.

## Estado
En construcción.
