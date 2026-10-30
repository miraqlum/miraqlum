<div align="center">

<strong>miraQlum™</strong>

# MiraQlum Operator

### Your AI can work on your WordPress site — with MCP.

**Connect WordPress to ChatGPT or Claude through MCP. Ask once for supported work. See verified results.**

[Official product website](https://operator.miraqlum.com/) · [Knowledge Base](https://operator.miraqlum.com/knowledge-base/) · [Support](mailto:support@operator.miraqlum.com)

</div>

---

## AI-powered WordPress operations, beyond suggestions

MiraQlum Operator connects an AI assistant to WordPress through the **Model Context Protocol (MCP)**. Instead of only suggesting edits, the assistant can discover the site's supported capabilities, prepare and carry out a user-authorized bounded task without repeated MiraQlum approval at every internal step, and check what actually happened. Initial connection and AI-client permissions, and newly higher-risk or out-of-scope work, can still require a separate authorization.

**One MiraQlum connection. A small, stable MCP control surface. A growing universe of WordPress capabilities.**

| Ask once | Check the scope | MiraQlum works | Verify |
|:---:|:---:|:---:|:---:|
| Give one clear authorized task | Discover the site's supported, permitted actions | Carry out the bounded work without repetitive MiraQlum approval prompts | Read back the WordPress result and report its state |

### Real workflows demonstrated

- **Content & Gutenberg:** draft creation, targeted editing, publication workflows, and WordPress content management.
- **Native Elementor:** editable sections and elements, not a single uneditable HTML blob. Verified in owner-controlled WordPress workflows.
- **Site maintenance:** supported plugin and theme management with targeted verification.
- **Native site design:** selected theme appearance settings and WordPress menus in demonstrated environments, without requiring a new MCP connection.
- **WordPress diagnostics:** site-health and environment checks, with clear boundaries around what can be repaired from WordPress.
- **Usage visibility:** account-scoped daily allowance, remaining capacity, optional monthly bonuses, and readable reset information.

These are **verified in specified owner-controlled environments**, not a promise to support every WordPress site, plugin, theme, hosting stack, or AI client.

## Free usage, clear boundaries

MiraQlum provides a real Free experience with a daily allowance, an eligible new-account Welcome period and optional bonuses. **Current plan details, fair-use rules and any prices are published on the [official product and plans page](https://operator.miraqlum.com/plans/)**, not fixed in this repository or in a WordPress plugin release. The applicable offer and, where relevant, tax-inclusive purchase total must be shown before purchase.

Basic account and site information, relevant capability discovery, planning and accepted-job status are available within the current policy without separately spending daily work units. Authorized material WordPress change-sets are metered once; internal retries of the same accepted work do not count as a fresh user request. Other resource-intensive analysis is subject to fair use.

To see **your own exact balance, bonuses and reset time**, ask your connected MiraQlum assistant. [Usage and limits explained →](docs/usage-and-limits.md)

## Built with distinct responsibilities

**WordPress Connector (plugin):** a thin, site-side integration that exposes supported WordPress capabilities under WordPress permissions.

**MiraQlum hosted service:** identity, site authorization, planning, approved execution, result verification, and usage enforcement. Hosted service internals are not part of this public profile repository.

**AI client:** ChatGPT or Claude can communicate with MiraQlum through MCP, subject to the client's supported features and the user's connection.

[Technical overview →](docs/architecture.md) · [WordPress connector & source availability →](docs/wordpress-connector.md)

## Current availability — verified 29 October 2026

**MiraQlum Operator 1.2.48 is active on two owner-operated WordPress sites.** Separate DEV and PROD plugins were updated from 1.2.47 without disconnecting or changing their Site IDs. Real WordPress page reads succeeded and complete site-specific capability discovery returned 77 (DEV) and 65 (PROD) capabilities. Those counts are specific to the tested sites.

A first Slovak customer earlier reported completing independent onboarding; their first WordPress write task remains a separate verification boundary.

**WordPress.org submission, review and directory publication are pending.** This repository is a public documentation home, **not a plugin ZIP/source release or hosted-service source**. The Free offer is available within current policies. Paid Paddle checkout is not claimed as live.

## Documentation

| Start here | Purpose |
|---|---|
| [Product overview](docs/overview.md) | What MiraQlum does—and does not claim |
| [Getting started](docs/getting-started.md) | The current supported onboarding journey |
| [Usage & limits](docs/usage-and-limits.md) | Free, Welcome, bonuses, and accounting |
| [Architecture](docs/architecture.md) | MCP, approval, verification, and boundaries |
| [WordPress connector](docs/wordpress-connector.md) | Plugin/source/release status |
| [FAQ](docs/faq.md) | Practical user and developer questions |
| [Changelog](CHANGELOG.md) | User-facing product milestones |
| [Security](SECURITY.md) · [Support](SUPPORT.md) | Private vulnerability reporting and customer help |
| [AI-readable index](llms.txt) · [AI assistant guide](docs/ai-assistant-guide.md) | Canonical public facts and private-usage lookup guidance |

## Terms, privacy and external service

[Free plans](https://operator.miraqlum.com/plans/) · [Terms](https://operator.miraqlum.com/terms-of-service/) · [Privacy](https://operator.miraqlum.com/privacy-notice/) · [DPA](https://operator.miraqlum.com/data-processing-agreement/) · [Full legal library](https://operator.miraqlum.com/legal-compliance/)

MiraQlum Operator uses an explicitly authorized WordPress connection and a separate hosted MCP service. Review the privacy and external-service disclosures before connecting.

## Open development, clear boundaries

Our **WordPress plugin distribution** is intended to be auditable and released with the appropriate GPL-compatible source and licensing information. The public WordPress connector code repository and WordPress.org distribution are being prepared; **this profile repository currently contains documentation, not the distributable connector source**. The hosted service and its internal implementation are separate.

**Contact:** [support@operator.miraqlum.com](mailto:support@operator.miraqlum.com) · [operator.miraqlum.com](https://operator.miraqlum.com/)

<sub>MiraQlum Operator · MCP / WordPress / AI-assisted workflows · Last public documentation review: 2026-10-29.</sub>
