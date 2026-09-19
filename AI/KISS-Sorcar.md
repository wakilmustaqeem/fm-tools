# KISS Sorcar

- Official repository: ksenxx/kiss_ai
- License: Apache-2.0.
- Type: local-first general-purpose AI agent framework with VS Code extension, CLI and web/mobile interfaces.
- Offline: Partial — it can use a local/self-hosted model endpoint; remote providers require internet.
- AI required: Yes for agent workflows.
- API key: Cloud providers require their own keys; a configured local endpoint can avoid cloud API keys.
- Local/self-hosted: Yes; custom local endpoints are documented.
- Basic local workflow: install the CLI/extension, configure an approved local model endpoint, then run agent tasks in a git worktree or configured project environment.
- Runtime prerequisite: Python 3.13+ for the documented Python/CLI installation path.
- Internet boundary: remote model providers, web tools, messaging agents and downloads require network access; local model endpoints can keep inference local.
- Limitation: the framework itself is free/open-source, but model-provider usage can incur cost; local operation still requires suitable local model hardware/software.
- Source verified: official GitHub repository.
