# CoWork OS

- Official repository: CoWork-OS/CoWork-OS
- License: MIT
- Offline: Partial. Local workspace state and SQLite data are stored locally; cloud-model prompts and connected services require network.
- AI required: No for exploring/basic workspace use; actual AI task execution requires a working model route such as local Ollama/MLX or a provider account.
- Internet/API: Local model routes can avoid hosted-model APIs; browser, search, remote devices and cloud providers require network.
- API key: Optional; local Ollama/MLX can avoid provider API keys.
- Local/self-hosted: Yes; local-first desktop/CLI runtime, with Windows 10/11 and macOS 13+ current desktop support.
- Basic non-AI workflow: use the local workspace, files, artifacts and supported deterministic tools without connecting a cloud model; keep permissions in approval mode and test on a sample workspace.
- Runtime prerequisites: prebuilt desktop releases are available; source development uses Node.js 24+ and npm, with platform-specific native build prerequisites.
- Limitation: provider eligibility, limits and charges belong to the selected provider; cloud-model prompts leave the device, and the project is still evolving.
- Source verified: official GitHub repository/documentation.
