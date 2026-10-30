# WordPress Connector — plugin and source availability

MiraQlum Operator uses a **WordPress-side connector plugin** and a **separate hosted MCP service**.

## What the connector is for

The connector provides a thin, permission-aware way for MiraQlum to discover supported WordPress capabilities and perform authorized, scoped WordPress operations. It is **not** a general-purpose remote PHP, shell, SQL, file-system, or arbitrary REST executor.

The connector is designed to preserve WordPress-native content/editor state and to avoid provider-specific PHP operation engines embedded in the generic plugin.

## Distribution status — verified 29 October 2026

| Area | Current scope |
|---|---|
| Public-name PROD | **MiraQlum Operator 1.2.48**, active on `operator.miraqlum.com`; WordPress page read PASS |
| Separate DEV | **MiraQlum Operator DEV 1.2.48**, active in a separate owner-controlled DEV environment |
| Normal update | Existing Site IDs and account links preserved on 1.2.47 → 1.2.48; both capability snapshots COMPLETE |
| WordPress.org | **Not yet approved/published** |
| This GitHub | Public **documentation-only** repository — no distributable plugin ZIP/source |
| Hosted service | Separate lifecycle and implementation; not publicly released here |

A tested owner-installed Connector is not automatically a public WordPress.org release.

## Open-source publication policy

The WordPress Connector's eventual public distribution must include its **exact release-matched, auditable, GPL-compatible source and required third-party notices**, with a WordPress.org-compliant `readme.txt`, plugin metadata, installation instructions, and clear disclosures about its hosted-service dependency and external data flows.

The separate MiraQlum hosted service is not represented as an open-source codebase and should not be confused with the plugin's licensing.

The release version and downloadable artifacts will be linked here when the **actual distributable connector source** has been audited and published. We do not supply placeholder files or fabricated install instructions in place of the plugin.

## What may be sent to an external service?

An authorized AI workflow can involve communication between the user's AI client, the MiraQlum hosted service, and the connected WordPress site. The actual categories of data transmitted, purposes, privacy roles, services and service terms must be disclosed accurately in the public release documentation **before general installation**. The [published legal library](https://operator.miraqlum.com/legal-compliance/) includes [Terms](https://operator.miraqlum.com/terms-of-service/), [Privacy](https://operator.miraqlum.com/privacy-notice/) and [DPA](https://operator.miraqlum.com/data-processing-agreement/). The separately hosted MCP service uses `mcp.miraqlum-operator.com` and an authorized Google/Auth0 account connection. Never include secret infrastructure details in the plugin package.

WordPress.org's [Plugin Guidelines](https://developer.wordpress.org/plugins/wordpress-org/detailed-plugin-guidelines/) and [Common Issues guidance](https://developer.wordpress.org/plugins/wordpress-org/common-issues/) govern public submissions.

[Product overview](overview.md) · [Security policy](../SECURITY.md) · [Support](../SUPPORT.md)
