# Awesome MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [Model Context Protocol (MCP)](https://modelcontextprotocol.io) servers, clients, frameworks, and resources.

The **Model Context Protocol** is an open standard that lets AI applications connect to external tools, data sources, and systems through a uniform interface — think of it as a "USB-C port for AI." This list collects the most useful projects in the ecosystem.

## Contents

- [Official Resources](#official-resources)
- [Frameworks & SDKs](#frameworks--sdks)
- [Clients](#clients)
- [Servers](#servers)
  - [Reference Servers](#reference-servers)
  - [Developer Tools](#developer-tools)
  - [Databases & Data Platforms](#databases--data-platforms)
  - [Cloud & Infrastructure](#cloud--infrastructure)
  - [Productivity & Communication](#productivity--communication)
  - [Search & Web](#search--web)
  - [Finance](#finance)
  - [Science & Research](#science--research)
- [Directories & Registries](#directories--registries)
- [Tutorials & Articles](#tutorials--articles)
- [Contributing](#contributing)

## Official Resources

- [Specification](https://spec.modelcontextprotocol.io) — The formal MCP specification.
- [Documentation](https://modelcontextprotocol.io) — Official docs, concepts, and quickstarts.
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Reference server implementations maintained by Anthropic.
- [Announcement Blog Post](https://www.anthropic.com/news/model-context-protocol) — The original introduction of MCP.

## Frameworks & SDKs

- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — Official SDK for building servers and clients in TypeScript.
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) — Official Python SDK, including the `FastMCP` high-level API.
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) — Official Kotlin SDK.
- [Java SDK](https://github.com/modelcontextprotocol/java-sdk) — Official Java SDK.
- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) — Official .NET SDK.
- [Go SDK](https://github.com/modelcontextprotocol/go-sdk) — Official Go SDK.
- [Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) — Official Swift SDK.
- [FastMCP](https://github.com/jlowin/fastmcp) — Ergonomic, Pythonic framework for building MCP servers and clients.

## Clients

- [Claude Desktop](https://claude.ai/download) — Anthropic's desktop app with first-class MCP support.
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — Anthropic's agentic CLI, MCP-capable.
- [Cursor](https://cursor.com) — AI code editor with MCP integration.
- [Zed](https://zed.dev) — High-performance editor supporting MCP context servers.
- [Cline](https://github.com/cline/cline) — Autonomous coding agent for VS Code with MCP support.
- [Continue](https://github.com/continuedev/continue) — Open-source IDE assistant supporting MCP.
- [LibreChat](https://github.com/danny-avila/LibreChat) — Open-source chat UI with MCP support.

## Servers

### Reference Servers

Maintained in [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers):

- **Filesystem** — Secure, configurable local file access.
- **Fetch** — Retrieve and convert web content for LLM use.
- **Git** — Read, search, and manipulate Git repositories.
- **Memory** — Knowledge-graph-based persistent memory.
- **Sequential Thinking** — Structured, step-by-step reasoning.
- **Time** — Time and timezone conversion utilities.

### Developer Tools

- [GitHub](https://github.com/github/github-mcp-server) — Official GitHub MCP server for repos, issues, and PRs.
- [GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) — GitLab project and issue management.
- [Sentry](https://github.com/getsentry/sentry-mcp) — Retrieve and analyze application errors.
- [Playwright](https://github.com/microsoft/playwright-mcp) — Browser automation and testing.
- [Chrome DevTools](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Debug and inspect web pages via Chrome.

### Databases & Data Platforms

- [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) — Read-only SQL queries and schema inspection.
- [SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) — Query and analyze SQLite databases.
- [Supabase](https://github.com/supabase-community/supabase-mcp) — Manage Supabase projects, tables, and migrations.
- [ClickHouse](https://github.com/ClickHouse/mcp-clickhouse) — Query ClickHouse analytics databases.
- [Redis](https://github.com/redis/mcp-redis) — Interact with Redis data structures.

### Cloud & Infrastructure

- [AWS](https://github.com/awslabs/mcp) — Official AWS MCP servers for cloud resources.
- [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Manage Workers, KV, R2, and D1.
- [Kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — Inspect and manage Kubernetes clusters.
- [Terraform](https://github.com/hashicorp/terraform-mcp-server) — Interact with Terraform and the registry.
- [Docker](https://github.com/ckreiling/mcp-server-docker) — Manage containers, images, and volumes.

### Productivity & Communication

- [Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) — Post messages and read channels.
- [Notion](https://github.com/makenotion/notion-mcp-server) — Official Notion server for pages and databases.
- [Linear](https://github.com/linear/linear-mcp-server) — Manage Linear issues and projects.
- [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) — Search and read Drive files.

### Search & Web

- [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) — Web and local search via the Brave API.
- [Exa](https://github.com/exa-labs/exa-mcp-server) — AI-native web search.
- [Tavily](https://github.com/tavily-ai/tavily-mcp) — Search and content extraction for agents.
- [Perplexity](https://github.com/ppl-ai/modelcontextprotocol) — Query the Perplexity Sonar API.

### Finance

- [Stripe](https://github.com/stripe/agent-toolkit) — Interact with the Stripe payments API.

### Science & Research

- [PubMed](https://github.com/ncukondo/pubmed-mcp) — Search biomedical literature.
- [ArXiv](https://github.com/blazickjp/arxiv-mcp-server) — Search and read arXiv preprints.

## Directories & Registries

- [MCP Registry](https://github.com/modelcontextprotocol/registry) — The official community server registry.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) — Large community-maintained server list.
- [Smithery](https://smithery.ai) — Registry and hosting for MCP servers.
- [Glama MCP](https://glama.ai/mcp/servers) — Searchable directory of MCP servers.

## Tutorials & Articles

- [Introduction to MCP](https://modelcontextprotocol.io/introduction) — Official getting-started guide.
- [Build Your First Server](https://modelcontextprotocol.io/quickstart/server) — Step-by-step server tutorial.
- [Core Architecture](https://modelcontextprotocol.io/docs/concepts/architecture) — How hosts, clients, and servers interact.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. Ensure any project you add is actively maintained and genuinely relevant to the MCP ecosystem.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
