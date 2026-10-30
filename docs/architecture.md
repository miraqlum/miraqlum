# MiraQlum Operator — public technical architecture overview

**Scope:** a deliberately high-level description for developers and security-conscious WordPress operators. It does not disclose hosted-service implementation details, infrastructure identifiers, secrets or private execution policies.

## Model Context Protocol (MCP)

MiraQlum presents **one MCP connection** with a **small stable set of tools**. Capability discovery identifies WordPress-supported operations from the connected site. The control surface is intentionally stable; supported WordPress capabilities evolve behind it.

```text
AI assistant (ChatGPT / Claude)
             |
             v
      MiraQlum MCP service
       |       |       |
    identity  plan   usage
       |       |       |
       +-------+-------+
               |
      authorized job / verification
               |
       WordPress Connector
               |
         WordPress site
```

The conceptual diagram is not a promise of a specific deployment topology.

## Safety and correctness principles

- **Site-bound authorization:** an account can act only on sites it is authorized to manage.
- **Read first:** discover real capabilities; do not pretend unsupported providers can be controlled.
- **Explicit bounded writes:** a concrete target and approved change should exist before mutation.
- **Durable result semantics:** track the accepted operation and verify the authoritative WordPress result.
- **Replay-aware execution:** a repeat of the same accepted operation should not become a second mutation simply because an AI client retried.
- **WordPress-native ownership:** saved posts, pages, editor data and plugin state remain WordPress-owned.
- **Thin site-side plugin:** the generic Connector is not a container for vendor-specific PHP integrations or an arbitrary code executor.

The exact set of supported actions varies by WordPress permissions and installed extensions. The hosted service has separate security and operations responsibilities and is **not part of this public documentation repository**.

## Product / availability boundary

- An installed owner-operated WordPress Connector and a separate hosted MiraQlum service are in use; the GitHub documentation repository does not contain either the deployable plugin source or the hosted engine.
- Current plan details, usage allowances and potential pricing are published on the [official product website](https://operator.miraqlum.com/plans/) and exposed per account by the connected service — **not hardcoded to a plugin README or a backend version**.
- A first external customer has reported independent onboarding. Owner DEV/PROD 1.2.48 connectors preserved Site IDs after a normal update and returned real WordPress reads. WordPress.org approval and Paddle paid checkout remain separate milestones as of 2026-10-29.
- No public documentation grants arbitrary access to WordPress sites, plugin execution, remote shell commands or third-party customer data.

[Overview](overview.md) · [Usage policy](usage-and-limits.md) · [WordPress connector](wordpress-connector.md) · [Security](../SECURITY.md)
