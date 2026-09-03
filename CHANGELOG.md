# Changelog

Public changelog for SoMerch roadmap, documentation, platform visibility, and operational workflow updates.

This changelog is intended to document public-facing changes that help customers, partners, and technical teams understand how SoMerch is developing as a software-powered corporate merch platform and service partner.

The changelog is public for transparency, but it is not a contractual commitment. Product priorities, timelines, and availability may change based on customer feedback, operational needs, supplier availability, logistics requirements, and technical planning.

---

## 2026-09-04

### Zapier app approved and listed in the Zapier Marketplace

The SoMerch Zapier app has passed review and is now officially listed in the Zapier Marketplace, so anyone can connect it with one click.

### Added

- **Zapier Marketplace listing** for the SoMerch app: https://zapier.com/apps/somerch/integrations
- Direct connect link for building zaps with SoMerch triggers, searches, and actions.

### Improved

- Zapier references across the public docs, API docs, and brand assets now link directly to the approved marketplace listing instead of a generic Zapier URL.

### Public resources

- Zapier Marketplace listing: https://zapier.com/apps/somerch/integrations

---

## 2026-08-27

### ChatGPT plugin and Zapier app launch

SoMerch shipped two new integrations: a ChatGPT plugin for planning and requesting quotes in chat, and an official Zapier app for no-code automation of merch operations.

### Added

- **ChatGPT plugin** based on the public MCP server: search products, plan merch projects, check feasibility, and submit quote requests directly in ChatGPT (connector URL `https://somerch.co/mcp`).
- **Zapier app** with OAuth 2.0 connections and REST-hook triggers with polling fallback:
  - Triggers: New Order, Order Status Changed, New Shipment, Shipment Updated, New Quote Request.
  - Searches: Find Products, Find Product, Find Order.
  - Actions: Submit Quote Request (idempotent), Create Merch Plan.
- Developer documentation for both integrations in the api-docs repository and on the public docs site.

### Improved

- Public MCP server expanded from read-only catalog browsing to full merch planning with `plan_merch_project`, `show_merch_plan`, and two-phase `submit_quote_request` tools.
- Webhook delivery engine with signature verification, exponential-backoff retries, and polling fallback for Zapier triggers.
- Published complete, up-to-date API documentation covering every endpoint used by the integrations: an OpenAPI 3.1 specification and an interactive reference on `docs.somerch.co`, plus endpoint, actions, and authentication guides in the api-docs repository.

### Public resources

- ChatGPT connector: https://somerch.co/mcp
- Zapier app: https://zapier.com/apps/somerch/integrations
- Integration docs: https://somerch.co/docs/integrations
- Interactive API reference: https://docs.somerch.co/openapi.html
- OpenAPI 3.1 spec: https://docs.somerch.co/openapi.json
- API docs repo: https://github.com/SoMerch/api-docs

---

## 2026-06-05

### Public GitHub and documentation launch

SoMerch published its first public GitHub resources to make the platform direction, documentation, product data concepts, and brand assets easier to understand.

### Added

- Public GitHub organization profile for SoMerch.
- Public roadmap repository.
- Customer-facing documentation hub at `docs.somerch.co`.
- Public API documentation concepts for future developer and integration workflows.
- Product data schema examples for catalog, variants, decoration, inventory, and shipment metadata.
- Brand assets repository with public messaging, app links, media copy, and logo usage guidance.
- Organization-level support, security, contribution, and issue template files.
- Sitemap and robots file for the public documentation site.
- Platform links for web, iOS, Android, and Windows app availability.

### Improved

- Clearer positioning of SoMerch as a software-powered corporate merch platform and service partner.
- Stronger public trust layer across GitHub, documentation, app stores, and official brand resources.
- Better public explanation of core workflows: product selection, quote requests, approvals, production, warehousing, fulfillment, and EU-wide shipping.
- More structured documentation for distributed teams, HR, operations, procurement, marketing, office teams, and agencies.

### Public resources

- Website: https://somerch.co
- Docs: https://docs.somerch.co
- GitHub: https://github.com/SoMerch
- Public Roadmap: https://github.com/SoMerch/public-roadmap
- API Docs: https://github.com/SoMerch/api-docs
- Product Data Schema: https://github.com/SoMerch/product-data-schema
- Brand Assets: https://github.com/SoMerch/brand-assets

---

## Unreleased

### Planned public documentation improvements

- Add more detailed workflow documentation for quote requests, approvals, and order tracking.
- Add more examples for managed inventory and warehousing programs.
- Add more structured guidance for employee gifting, onboarding packs, event kits, and office restocking.
- Expand API documentation with example webhook events and lifecycle diagrams.
- Add more product data schema examples by category.
- Improve documentation site visuals, navigation, and discoverability as the platform evolves.

---

## 2026-08-13

### Public MCP, API, AI Merch Consultant, and content modules launch

SoMerch shipped several major platform capabilities, including an AI-powered Merch Consultant, a public MCP server for AI agent integration, a public REST API with OAuth and webhooks, and four structured content modules (Merch Atlas, Merch Calendar, Merch Guide, Gift Ideas).

### Added

- AI-powered Merch Consultant for planning and recommendations.
- Public MCP server at `somerch.co/mcp` with MCP server card discovery.
- Public REST API at `/api/public/v1/` with OpenAPI spec, OAuth, webhooks, events, jobs, and connections.
- Integration documentation page at `somerch.co/docs/integrations`.
- Merch Atlas, Merch Calendar, Merch Guide, and Gift Ideas content modules with EN/DE/FR support.
- Agent skills discovery endpoints at `/.well-known/agent-skills/`.
- Employee redeem links, address collection, and size selection workflows.

### Improved

- Structured SEO and AEO data across all new content modules.
- Multi-language content coverage (EN, DE, FR).
- Product data schema examples aligned with live platform data.

### Public resources

- Public MCP: https://somerch.co/mcp
- API OpenAPI spec: https://somerch.co/api/public/openapi.json
- Integration docs: https://somerch.co/docs/integrations
