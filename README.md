# TypeForge MCP Server 🛡️📐⚡

Universal Autonomous JSON-to-Zod, TypeScript Interfaces, Pydantic & Type Safety Engine MCP Server for **Cursor, Claude Code, Windsurf, and Autonomous AI Agents**.

## 🌟 Core Capabilities:
- 👑 **Master 1-Shot Outcome Engine (`autonomous_type_and_validation_schema_architect`):** Ingests raw JSON data or API payloads and produces an end-to-end type safety ecosystem (strict TypeScript declarations, Zod schemas with regex/coercion rules, Python Pydantic v2 models, runtime type-guard predicates, and mock factories) in one call.
- ⚡ **Deep Nested JSON-to-Zod Converter (`convert_json_to_zod_schema`):** Generates production Zod schemas with automatic email, UUID, datetime, and number coercion inference.
- 📐 **Enterprise TypeScript Interfaces & DTOs (`generate_typescript_interfaces_and_dto`):** Produces strict interfaces, readonly immutables, Create/Update DTO utility types, and JSDoc documentation.
- 🐍 **Pydantic v2 & Rust Serde Generator (`generate_pydantic_and_rust_types`):** Generates Python Pydantic models with Field validation and Rust Serde structs.
- 🛡️ **Type-Narrowing Guard Predicates (`build_type_narrowing_guards`):** Creates custom `val is Type` runtime assertion functions to eliminate dangerous `any` casting.

## 🚀 Server URL
`https://typeforge-api.agentweb-hub.workers.dev/mcp`


## 🔴 NEW in v1.1 — Real JSON Type Inference

`infer_types_from_json` parses **your actual JSON** (not a template) and generates matching nested TypeScript interfaces, a Zod schema, a Pydantic v2 model and a JSON Schema — with smart detection of UUIDs, emails, ISO datetimes, URLs, int-vs-float, nullable fields and array element types. Deterministic local computation on your real payload.

## 💰 Pricing

**Start free — 10 requests/day, no signup, no card.** Upgrade only if it earns a place in your workflow.

| Plan | Price | Pay with |
|------|-------|----------|
| **Free** | $0 | 10 requests/day — no signup needed |
| **Pro** (this server only) | **$7.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |
| **All-Access Suite** (all 44+ servers) | **$14.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |

### 💳 Option 1 — Gumroad (PayPal & Credit Cards)

👉 **[amygraphics.gumroad.com/l/mcp-pro](https://amygraphics.gumroad.com/l/mcp-pro)** — select *Single MCP Server* ($7.99) or *All-Access Lifetime Suite* ($14.99). Instant license key delivery.

### 🪙 Option 2 — Solana USDC (instant, no account needed)

Send **$7.99 USDC** (single) or **$14.99 USDC** (all-access) to:

```
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```

Then POST your transaction signature to the `/verify-solana` endpoint to activate your lifetime license instantly.
