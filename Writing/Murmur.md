# Murmur

- Official repository: murmur-io/murmur
- License: AGPL-3.0.
- Type: local-first macOS meeting and document notebook with Markdown notes, transcription, retrieval and optional AI.
- Offline: Yes for core local-first workflows. Recording, notes and on-device transcription/reasoning can operate locally; optional web connectors and cloud providers require network.
- AI required: No for basic note/writing and Markdown export. AI is optional, with bundled/on-device models or local Ollama available for privacy-preserving use.
- API key: Not required for core local use or bundled/on-device models. Optional web/cloud providers may require their own keys.
- Local/self-hosted: Local-first desktop app; the project also exposes a local read-only MCP server. Shared Brain is an optional network service.
- Basic non-AI workflow: create standalone Markdown notes or record a meeting, keep notes in the local encrypted store, search/browse locally, and export notes as plain Markdown.
- Runtime prerequisites: end-user app requires macOS 13.4+ on Apple Silicon or Intel. Source development uses Rust 1.96.0, Node/npm, cmake/clang and Xcode Command Line Tools.
- Internet boundary: local notes/recording/transcription can stay on-device; optional web connectors, cloud models and Shared Brain require network access.
- Limitation: Murmur is specifically a macOS meeting/document notebook, not a general cross-platform writing studio.
- Source verified: official GitHub repository, current README and license.
