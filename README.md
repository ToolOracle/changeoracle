# 🔄 changeOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/change/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "changeoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/change/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_change` | Register an ICT change request with full DORA traceability. |
| `list_changes` | List changes with optional filters. |
| `change_risk_assess` | Automated risk assessment based on type, scope, and controls. |
| `approval_check` | Verify approval chain, SoD compliance, and prerequisites. |
| `test_evidence` | Record or view test execution evidence for a change. |
| `rollback_plan` | Validate rollback plan readiness for a change. |
| `patch_compliance` | Patch lag analysis — overdue patches against scheduled deadlines. |
| `sod_check` | Detect Segregation of Duties violations across all changes. |
| `change_stats` | Dashboard: volume, risk distribution, test/rollback coverage, emergency ratio. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

changeOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/change/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
