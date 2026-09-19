# OpenCode

- Official repository: anomalyco/opencode
- License: MIT.
- Type: open-source AI coding agent with terminal UI, client/server architecture, LSP support, agents and optional desktop app.
- Offline: Partial. The agent runs locally, and local models can be used, but provider-backed models, web access and remote services require network.
- AI required: Yes. OpenCode is an AI coding agent; it is not a conventional non-AI developer utility.
- API key: Depends on the configured model/provider. Local models can avoid cloud provider keys; remote providers require their credentials.
- Local/self-hosted: Yes. The agent runs on the user's machine and supports local model/provider configurations.
- Basic non-AI workflow: Not applicable as a true non-AI workflow. For safer operation, use the read-only **plan** agent for code exploration before enabling the full-access **build** agent.
- Runtime prerequisites: prebuilt packages are available for major desktop/CLI platforms; source development uses Bun and the repository's build/test tooling.
- Internet boundary: installation downloads, remote LLM providers, web tools and remote MCP servers require network. Local model configurations can keep model inference local.
- Limitation: OpenCode's permission system is not a security sandbox; the project explicitly recommends Docker or a VM for true isolation. Remote provider data handling follows the provider's policies. citeturn0search6turn0search9
- Source verified: official GitHub repository, current README/package metadata and security documentation. citeturn0search8turn0search9
