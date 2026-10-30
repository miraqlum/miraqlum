# Frequently asked questions

### Is MiraQlum a WordPress MCP server?

MiraQlum Operator is a **hosted MCP-connected WordPress service** with a thin WordPress connector plugin. An AI client uses the MiraQlum MCP connection to discover and, when authorized, perform supported WordPress work.

### Do I need a separate MCP connection for every feature or site?

No. The intended experience is **one MiraQlum connection**. Sites and capabilities remain account- and WordPress-permission-bound.

### Is WordPress.org installation already available?

As of 2026-10-29, **MiraQlum Operator 1.2.48** is active on verified owner-operated DEV and PROD WordPress sites, but **has not been published on WordPress.org**.

### Is the WordPress Connector open source on this GitHub profile repository?

No. This repository publishes product documentation. Public connector source and release materials are a separate distribution track, not hosted in this documentation-only repository. The hosted backend is not promised as open source.

### Which WordPress tasks are supported?

Verified workflows include certain WordPress Core/Gutenberg operations, native Elementor workflows, native theme appearance and navigation, selected plugin/theme maintenance operations and diagnostics. Availability on a particular site is determined by **capability discovery** and permissions—not a universal compatibility claim.

### Do I have to pay before trying MiraQlum?

The product has a genuine Free experience and an eligible Welcome offer. **Current availability, allowances and any prices are shown on the [official Plans page](https://operator.miraqlum.com/plans/)**, not fixed in this GitHub FAQ. Independent public onboarding and paid checkout are separate rollout items. See the [usage guide](usage-and-limits.md) for how limits and bonuses work.

### Will I have to approve every internal step?

No. One clear, authorized bounded request can cover its supported internal actions without repetitive MiraQlum approval prompts. Initial OAuth/WordPress access and your AI client's own tool permissions remain separate, and new higher-risk or out-of-scope actions may need a new decision.

### What is a usage unit?

An eligible, meaningful WordPress operation under the current policy, such as an accepted, authorized bounded change-set. Basic account/status/discovery/planning is available without drawing down daily work units. It is **not** a token, an MCP tool-call count, or a guarantee of one completed multi-step human project. Internal retries of the same accepted job do not independently consume additional units.

### What happens if a change fails?

The service is designed to report observed outcomes and errors rather than label an attempt successful without proof. The accounting for system-owned errors differs from new user-requested work, and the platform avoids double-charging its internal retries.

### Can I cancel a paid subscription?

Paddle is the planned Merchant of Record for paid subscriptions, but **no live MiraQlum paid checkout is claimed by this repository**. When paid subscriptions are offered, their then-current cancellation, renewal, tax and refund terms must be shown on the product website and at checkout.

### Is a separate AI client subscription required?

AI clients such as ChatGPT or Claude have independent plans, capabilities and limits; MiraQlum usage allowances do not include or replace the AI client's terms.

### How do I sign in?

Google sign-in is the currently supported MiraQlum account method. Never share passwords or WordPress Application Passwords in an AI prompt.

### Do I need to configure Elementor MCP or connect it separately?

No. With a supported Elementor version, switch on **Elementor → Elementor MCP → Enable MCP access** inside WordPress. No separate Elementor MCP account or AI-side connection is needed.

### Where are the Terms, Privacy Notice and DPA?

See the official [Terms](https://operator.miraqlum.com/terms-of-service/), [Privacy Notice](https://operator.miraqlum.com/privacy-notice/) and [DPA](https://operator.miraqlum.com/data-processing-agreement/).

### How can I report a bug or a security concern?

See [Support](../SUPPORT.md). Please report security vulnerabilities **privately**, not in public issues.

[Documentation home](../README.md)
