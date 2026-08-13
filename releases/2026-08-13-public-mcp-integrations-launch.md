# Public MCP, API, AI Merch Consultant, and content modules launch

**2026-08-13**

SoMerch has shipped several major platform capabilities:

## Added

### AI-powered Merch Consultant
- AI chat for merch planning, product recommendations, and catalog navigation
- Embeddable widget for external sites
- Admin analytics dashboard for consultation tracking

### Public MCP server
- MCP server at `somerch.co/mcp` for AI agent integration
- MCP server card at `/.well-known/mcp/server-card.json` (SEP-1649)
- Agent skills discovery at `/.well-known/agent-skills/`
- Supports all major MCP clients (Claude, ChatGPT, Cursor, OpenCode, etc.)

### Public REST API
- REST API at `/api/public/v1/` with OAuth, webhooks, events, jobs, actions, and connections
- OpenAPI spec at `/api/public/openapi.json`
- Integration documentation at `somerch.co/docs/integrations`

### Content modules
- **Merch Atlas** — curated knowledge hub of merch articles with tags and multi-language support (EN/DE/FR)
- **Merch Calendar** — seasonal and timed content for merch planning
- **Merch Guide** — categorized field guides with subcategories and tags
- **Gift Ideas** — curated gift idea articles by tag and category

### Employee flows
- Redeem links for employee self-service ordering
- Address and size collection workflows
- Per-order design review and approval

## Improved

- Public documentation at `docs.somerch.co` with expanded coverage
- Product data schema examples aligned with live platform data
- SEO and AEO structured data for all content modules
- Multi-language support (EN, DE, FR) across content modules

## Public resources

- Website: https://somerch.co
- Web App: https://app.somerch.co
- Docs: https://docs.somerch.co
- GitHub: https://github.com/SoMerch
- MCP: https://somerch.co/mcp
- API: https://somerch.co/api/public/openapi.json
- Staff MCP: https://somerch.co/staff/mcp