# ChatGPT plugin and Zapier app launch

**2026-08-27**

SoMerch shipped two new integrations: a ChatGPT plugin for AI-powered merch planning and an official Zapier app for no-code automation.

## ChatGPT plugin

- Search the SoMerch catalog and compare products with quantity-aware pricing
- Generate merch plans with up to three tiered options and feasibility checks
- Check deadlines, budgets, and market support for the EU and Switzerland
- Submit quote requests with a built-in confirmation step
- Works in English, German, and French
- Connect in ChatGPT via Settings > Connectors > Advanced with `https://somerch.co/mcp`

## Zapier app

- OAuth 2.0 connection for your organization
- Triggers: New Order, Order Status Changed, New Shipment, Shipment Updated, New Quote Request
- Searches: Find Products, Find Product, Find Order
- Actions: Submit Quote Request (idempotent), Create Merch Plan
- REST hooks with automatic polling fallback, signed deliveries, and retries

## Public resources

- ChatGPT connector: https://somerch.co/mcp
- Zapier app: https://zapier.com
- Interactive API reference: https://docs.somerch.co/openapi.html
- OpenAPI 3.1 spec: https://docs.somerch.co/openapi.json
- Integration docs: https://somerch.co/docs/integrations
- API docs: https://github.com/SoMerch/api-docs