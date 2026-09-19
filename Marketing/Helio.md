# Helio

- Official repository: achref-soua/helio
- License: AGPL-3.0
- Offline: Partial. Core self-hosted data/workflows can run on local infrastructure; messaging, DNS verification, migrations, external integrations and hosted AI need network access.
- AI required: No for core CRM/marketing automation; AI copilot, predictive scoring and related features are optional.
- Internet/API: Network is required for email/SMS/WhatsApp delivery, external integrations, DNS checks and remote AI providers. Local Ollama/OpenAI-compatible model servers can keep AI local.
- API key: Not required for core local CRM use; external channels/providers and cloud AI require their own credentials.
- Local/self-hosted: Yes; current v2 documentation describes a CLI that drives Docker and a self-hosted deployment.
- Basic non-AI workflow: run the local deployment, manage contacts/lists, segments, campaigns, journeys, CRM records and analytics, and connect only the approved delivery channels.
- Runtime prerequisites: Docker is the primary deployment path; the repository also documents local development tooling and a multi-service architecture including PostgreSQL, ClickHouse, Redis, S3/MinIO, Redpanda and Temporal.
- Limitation: a full production deployment is multi-service and operationally heavier than a simple local desktop app; connected delivery channels are not offline.
- Source verified: official GitHub repository/documentation.
