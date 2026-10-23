<p align="center">
  <img src="https://raw.githubusercontent.com/tavric-labs/.github/main/profile/brand/tavric-labs-avatar.jpg" width="144" height="144" alt="Tavric Labs" />
</p>

<h1 align="center">Tavric Labs</h1>
<p align="center"><strong>Tools and infrastructure for LLMs and agent systems.</strong></p>

We build the infrastructure around agents: running their services, connecting their tools, controlling access, and carrying useful work context between sessions and devices.

## Products

- [MCP Runtime](https://github.com/tavric-labs/mcp-runtime) — a self-hosted Kubernetes runtime and control plane for MCP servers. Deploy and route services, govern tool access, and audit requests inside your own cluster. [Website](https://mcpruntime.org/) · [Docs](https://docs.mcpruntime.org/)
- [Cully](https://github.com/tavric-labs/cully) — a workspace around coding agents, with session guidance, durable project memory, team handoffs, and native Self-mode mobile clients. [Website](https://cully.net/) · [Docs](https://docs.cully.net/)
- [mcp-mobile](https://github.com/tavric-labs/mcp-mobile) — native Kotlin and Swift MCP client SDKs for mobile apps, wrapping the official MCP SDKs. [Docs](https://mcp-mobile.tavric-labs.net/) · [Releases](https://github.com/tavric-labs/mcp-mobile/releases)

## The toolbox

**Build**
- [PyMCP Kit](https://github.com/tavric-labs/py-mcp) — an opinionated implementation of the MCP spec for FastAPI. [Docs](https://py-mcp.tavric-labs.net/)

**Access**
- [MCP Auth](https://github.com/tavric-labs/mcp-auth) — a provider-neutral OAuth 2.1 authorization broker with Python, Go, and TypeScript resource-server SDKs. [Docs](https://mcp-auth.tavric-labs.net/docs/)
- [1Password MCP Plugin](https://github.com/tavric-labs/onepassword-mcp-plugin) — a credential gateway connecting mcp-auth, 1Password, and upstream tools. Preview.

**Test and inspect**
- [MCP Server Fuzzer](https://github.com/tavric-labs/mcp-server-fuzzer) — black-box security assessment for live MCP servers.
- [mcp-smoke](https://github.com/tavric-labs/mcp-smoke) — smoke-test MCP servers with plain-English requests. [Docs](https://mcp-smoke.tavric-labs.net/)
- [mcpsnoop](https://github.com/tavric-labs/mcpsnoop) — a transparent proxy that shows real MCP traffic in your terminal.
- [mcpfz-probe](https://github.com/tavric-labs/mcpfz-probe) — a runtime observation sidecar for MCP server fuzzing.

## Documentation

Every project documents itself next to its code, and all the docs sites share one design: the [`docs-theme`](https://github.com/tavric-labs/docs-theme) package. Browse them all at [tavric-labs.net](https://tavric-labs.net/#docs).

MCP Runtime remains the product name. Tavric Labs is the organization bringing these projects together.
