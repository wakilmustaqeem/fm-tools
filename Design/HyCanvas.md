# HyCanvas

- Official repository: hyscaler/HyCanvas
- License: Elastic License 2.0 (source-available; not an OSI-approved open-source license).
- Type: self-hostable AI-native design platform for graphics, presentations, video, whiteboards, docs and print.
- Offline: Partial. The product is web-only, but it can be self-hosted and run locally. Connected services, remote assets, collaboration and provider-backed features require network access.
- AI required: No for core editing/export; AI generation is optional and BYO-key.
- API key: Not required for core local editing. AI/provider integrations and the generation API use configured credentials.
- Local/self-hosted: Yes. Official docs support Docker or a standalone production binary with PostgreSQL.
- Basic non-AI workflow: run a local/self-hosted instance, create/edit a design in the browser, save the project, and export to PNG/PDF or other supported formats without enabling AI.
- Runtime prerequisites: Node 24 and Go 1.25 for source development; PostgreSQL is required. ffmpeg is required for server-side video export/preview. A built production bundle runs as a standalone Go binary.
- Internet boundary: local editing can be kept on the self-hosted instance, but browser-connected external services/assets, remote storage, OIDC, AI providers and hosted sharing/collaboration need network access.
- Limitation: source-available licensing restricts offering HyCanvas itself as a hosted/managed service to third parties without a commercial license.
- Source verified: official GitHub repository and current project README/licensing documentation.
