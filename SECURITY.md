# Security Policy

Security Operation Center Integrated Suites (SOCIS) takes the security of our platforms, our website, and our infrastructure seriously. We appreciate the work of security researchers and the community in helping us keep SOCIS Enterprise, SOCIS Trace, SOCIS Sentinel AI, SOCIS HexCage, and everything at [socis.io](https://socis.io) secure.

## Reporting a Vulnerability

If you believe you've found a security vulnerability in any SOCIS product, repository, or the socis.io website, please report it to us privately and responsibly.

**Email:** [security@socis.io](mailto:security@socis.io)

Please **do not** open a public GitHub issue for security vulnerabilities. Public issues are visible to everyone, including potential attackers, before we've had a chance to investigate and remediate.

### What to include in your report

To help us triage and respond quickly, please include as much of the following as you can:

- A clear description of the vulnerability and its potential impact
- Steps to reproduce, including any proof-of-concept code, screenshots, or requests/responses
- The affected product, repository, URL, or component and version/commit
- Any suggested remediation, if you have one

### What to expect from us

- **Acknowledgment:** We aim to acknowledge receipt of your report within **3 business days**.
- **Assessment:** We will investigate and provide an initial assessment of severity and validity within **10 business days** of acknowledgment.
- **Resolution:** Timelines for a fix depend on severity and complexity. We will keep you informed of progress throughout.
- **Credit:** With your permission, we're happy to credit you for the discovery once a fix is released. Let us know in your report if you'd prefer to remain anonymous.

We ask that you give us a reasonable amount of time to investigate and remediate an issue before any public disclosure, and we commit to working with you in good faith toward a resolution.

## Scope

This policy covers:

- Repositories under the [socisio](https://github.com/socisio) GitHub organization
- The SOCIS website ([socis.io](https://socis.io) and its subdomains)
- SOCIS product platforms: SOCIS Enterprise, SOCIS Trace, SOCIS Sentinel AI, SOCIS HexCage
- SOCIS AI, our security intelligence assistant

## Out of Scope

The following are generally **not** considered valid security reports unless you can demonstrate real, exploitable impact:

- Vulnerabilities requiring physical access to a user's device
- Social engineering of SOCIS staff or contractors
- Denial-of-service attacks achieved through volumetric traffic (e.g. basic flooding)
- Missing security headers or best-practice suggestions with no demonstrated exploit
- Vulnerabilities in third-party dependencies that have no working proof-of-concept against SOCIS deployments (please report these upstream instead, and let us know if we're affected)
- Issues on out-of-date browsers or unsupported platforms

## Supported Versions

For open-source or publicly available components under this organization, we support and provide security fixes for the **latest released version** of each project unless otherwise noted in that project's own `SECURITY.md` or release notes.

## Safe Harbor

We will not pursue legal action against researchers who:

- Make a good-faith effort to avoid privacy violations, data destruction, and service disruption
- Report vulnerabilities promptly and do not exploit them beyond what's necessary to demonstrate the issue
- Do not access, modify, or exfiltrate data beyond what's needed to prove the vulnerability exists
- Give us a reasonable opportunity to investigate and remediate before any public disclosure

Thank you for helping keep SOCIS and our community safe.
