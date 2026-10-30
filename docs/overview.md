# MiraQlum Operator — Product overview

**MiraQlum is an MCP-connected WordPress operator.** Users describe a supported, bounded WordPress task to an AI assistant; that authorized request can cover its permitted internal steps, followed by an independently checked WordPress outcome.

## The workflow

1. **Connect** an AI client to the MiraQlum service and link an authorized WordPress site.
2. **Discover** relevant WordPress capabilities through the connected site. Available operations vary by WordPress/editor/plugins/permissions.
3. **Plan** a concrete, bounded operation; unavailable actions are explicitly reported as unsupported for that context.
4. **Authorize once within scope:** your clear, permitted bounded task request is sufficient for its approved internal steps; it is not a series of redundant MiraQlum confirmations. Initial identity/host permissions and new material or higher-risk work can require another decision.
5. **Execute and verify** against WordPress. A successful API response alone does not guarantee the intended WordPress result.
6. **Review** the reported outcome and, if useful, [remaining daily usage](usage-and-limits.md).

## Demonstrated outcomes

| Capability area | Evidence boundary |
|---|---|
| Gutenberg & WordPress Core | Owner-controlled WordPress content workflows |
| Elementor | Specific native, editable Elementor page workflows |
| Maintenance | Supported plugin/theme lifecycle work and verified result states |
| Diagnostics | Targeted WordPress health and environment findings |
| Native site presentation | Demonstrated global appearance changes and WordPress-native menu assignments |
| Daily usage | Account-scoped metering, quota, Welcome period and bonus activation in owner-operated DEV/PROD |

These outcomes do not imply universal compatibility, autonomous access without user authorization, or self-repair of every hosting-side failure.

## Product shape

- The **WordPress connector** is a thin site-side plugin.
- The **hosted MiraQlum service** manages connection, authorization, bounded execution and usage.
- The **AI client** presents natural-language interaction.
- The **MCP** connection is the integration between the assistant and MiraQlum.

There is no requirement for one separate MCP connection per WordPress feature.

## Current launch status — 29 October 2026

On two owner-operated sites, **MiraQlum Operator 1.2.48** is installed and active in the separate DEV and PROD channels. The 1.2.47 → 1.2.48 update preserved each Site ID and existing account connection. Real page readbacks and complete site-specific discovery succeeded (77 DEV / 65 PROD). A first Slovak external customer reported independent onboarding; this does not certify every customer workflow.

The WordPress.org public directory release is **not yet approved or published**. The [legal library](https://operator.miraqlum.com/legal-compliance/) includes [Terms](https://operator.miraqlum.com/terms-of-service/), [Privacy](https://operator.miraqlum.com/privacy-notice/) and [DPA](https://operator.miraqlum.com/data-processing-agreement/). Free access has real usage limits; Paddle paid checkout is not claimed as live.

[Documentation home](../README.md) · [Changelog](../CHANGELOG.md) · [Support](../SUPPORT.md)
