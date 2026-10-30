# Security Policy

## Private vulnerability reporting

Please **do not publish security vulnerabilities, proof-of-concept exploits, secrets, authentication tokens, account identifiers, customer content, or server configuration in GitHub Issues or public pull requests**.

Report suspected vulnerabilities privately to:

**[support@operator.miraqlum.com](mailto:support@operator.miraqlum.com)**

Subject suggestion: `Security report — MiraQlum Operator`

Include:
- A brief impact statement and affected product component.
- The relevant version, WordPress version and environment if known.
- Minimal, **redacted** reproduction steps and expected/observed behavior.
- A safe way to contact you for follow-up.

Please avoid testing security issues on accounts or sites you do not own or lack authorization to assess. Do not extract other customers' data or publish exploit chains.

## Scope

The public documentation repository does not contain the distributable WordPress Connector source or hosted-service code. Owner-operated Connector version 1.2.48 is verified; WordPress.org publication remains separate. Its documentation does not grant authorization to scan, exploit or alter production infrastructure.

## Product security principles

MiraQlum emphasizes account/site-bound authorization, bounded proposed changes, explicit approval for material writes and verification of WordPress outcomes. Those principles are design commitments and proven in documented owner-use scenarios, not a blanket security certification.

Security issues may require private coordination before public disclosure. No guaranteed response-time SLA is promised in this document.

[Support](SUPPORT.md) · [Architecture](docs/architecture.md)
