# Mautic

- Official repository: mautic/mautic
- License: GPL-3.0 (current 7.x composer metadata; the repository license file states GPL v3).
- Offline: Partial. The self-hosted application can run locally, but outbound email, DNS and external integrations require network access.
- AI required: No for core marketing automation.
- Internet/API: Required for email delivery and external integrations; local development/testing can run without cloud AI.
- API key: Not required for core self-hosted operation; individual integrations and delivery providers may require their own credentials.
- Local/self-hosted: Yes.
- Basic non-AI workflow: run a self-hosted installation, manage contacts, segments, campaigns, forms and email marketing locally, then add only the integrations needed for delivery/measurement.
- Runtime prerequisites: current 7.x source metadata targets PHP 8.2; Composer is required for source installation, and the project also documents DDEV as an alternative development/setup path. Production users are directed toward packaged releases rather than raw source.
- Limitation: GitHub-source installation requires CLI work and source outside a tagged release is considered alpha by the project; production deployment should follow the supported packaged/release installation guidance.
- Source verified: official Mautic GitHub repository and current 7.x documentation.
