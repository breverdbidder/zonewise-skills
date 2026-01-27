# 🗺️ ZoneWise Skills - Multi-Platform AI Integration

> **"Data is the moat. Everything else is a wrapper."**

## One Dataset, Multiple Platforms

| Platform | Format | Location |
|----------|--------|----------|
| **Manus AI** | .skill | `/manus/` |
| **Craft Agents** | SKILL.md | `/craft/` |
| **Claude MCP** | JSON/TS | `/mcp/` |

## The Data Moat

- **301** Zoning Districts
- **10,092** GIS Polygons  
- **17** Jurisdictions
- **56** Unique Zone Codes

## Installation

### Manus AI
```
Import from GitHub → https://github.com/breverdbidder/zonewise-skills
```

### Craft Agents
```
Connect → https://github.com/breverdbidder/zonewise-desktop
```

### Claude Desktop
Add to `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "zonewise": {
      "command": "npx",
      "args": ["zonewise-mcp"]
    }
  }
}
```

## Quick Queries
```
"Setbacks for R-1 in Satellite Beach?"
"Can I build 50ft in Melbourne?"
"Compare C-1 vs C-2 in Palm Bay"
```

---
*© 2026 Everest Capital USA*
