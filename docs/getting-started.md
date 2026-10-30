# Getting started with MiraQlum Operator

> **Availability (29 October 2026):** Version 1.2.48 is verified on owner-operated DEV/PROD sites. WordPress.org publication remains pending; install only from a trusted official source.

## The intended user journey

1. **Install the official MiraQlum WordPress Connector**, from a verified distributor once the public release becomes available. Check the plugin's publisher and version before installation.
2. **Authorize your WordPress site** through the MiraQlum connection flow with the currently supported Google sign-in. Site access is tied to the account that owns or is permitted to manage it.
3. **Connect an MCP-capable AI assistant** (such as ChatGPT or Claude) to the MiraQlum service using the official supported connection instructions.
4. **Ask about a supported task** in everyday language, for example: “Inspect the health of my WordPress website, without making changes.”
5. **Ask once for a clear authorized task**. MiraQlum determines the bounded, permitted work and does not require a fresh MiraQlum approval for every internal step. First-time site/client permissions and newly out-of-scope or higher-risk work remain separately protected. A read-only request must stay read-only.
6. **Check the saved outcome**. For work that changes WordPress, verify the reported target and final state.

## Two prompts to try first

**Read-only WordPress pages**

> Use only my MiraQlum Operator connection to list the pages on my connected WordPress website. Do not change anything. If MiraQlum Operator is unavailable, tell me instead of using another WordPress tool.

**Your visual usage dashboard**

> Using only my MiraQlum Operator connection, show my daily usage, remaining allowance, next reset time, available and activated bonuses, and usage by connected WordPress website. Present the results as a clear visual dashboard if supported, otherwise as a table. Do not activate any bonuses.

**Ask once. MiraQlum handles the authorized task and verifies the result.** AI-client connection permissions and newly higher-risk or out-of-scope work may still require separate confirmation.

**Optional Elementor:** WordPress Admin → **Elementor → Elementor MCP → Enable MCP access**. Switch it on for supported Elementor versions. You do not need to configure other Elementor MCP settings or create a second AI-side Elementor connection. Native capabilities still depend on the exact version and permissions.

## Current plans and published terms

The latest plan descriptions, fair-use limits, trial or bonus conditions and any prices are maintained on the [MiraQlum product website](https://operator.miraqlum.com/plans/). Do not rely on a dated plugin README or GitHub snapshot for current amounts. The service displays your authenticated balance through the connected assistant; paid subscriptions are not described here as live.

## Important boundaries

- The AI client may have its own plan, usage limits or fees, independent from MiraQlum.
- Account and site permissions always apply. Do not share login credentials or API secrets in prompts.
- Never assume a plugin operation is supported simply because it is described in a generic example.
- WordPress.org distribution has **not yet been approved or published**, as of 2026-10-29.

[Usage & limits](usage-and-limits.md) · [Product overview](overview.md) · [Support](../SUPPORT.md)
