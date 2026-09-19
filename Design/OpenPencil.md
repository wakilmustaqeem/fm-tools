# OpenPencil

- Official repository: ZSeven-W/openpencil
- License: MIT.
- Type: open-source AI-native vector design editor with native desktop, web, CLI, MCP, Figma import and .op JSON documents.
- Offline: Partial to Yes for core local editing. Native desktop and local/headless modes support local files without a cloud account; online collaboration, hosted services and remote AI providers require network access.
- AI required: No for core drawing, editing, saving and export. Built-in AI/agent features are optional.
- API key: Not required for core editing. Optional AI providers may require provider credentials.
- Local/self-hosted: Yes. Desktop binaries, local/headless server and self-hosted web/server workflows are documented.
- Basic non-AI workflow: launch the desktop app, create/open a .op document, edit vectors/text/layout manually, save locally, and export PNG/JPEG/WEBP/PDF. Figma .fig import is also available.
- Runtime prerequisites: prebuilt desktop releases are available for supported platforms. Source builds use the pinned Rust toolchain and WebAssembly target; the repository documents Rust 1.94, wasm32-unknown-unknown, and Bun for web SDK tooling.
- Internet boundary: downloading releases and optional remote providers require internet. Local desktop/file-backed workflows can operate without cloud AI.
- Limitation: some collaboration, hosted web and provider-backed AI features are network-dependent; local operation does not make remote model providers offline.
- Source verified: official GitHub repository, current README and release information.
