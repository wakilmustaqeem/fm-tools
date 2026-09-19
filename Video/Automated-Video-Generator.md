# Automated Video Generator

- Official repository: itsPremkumar/Automated-Video-Generator
- License: MIT
- Offline: Partial. Core rendering and supported local voice/AI engines can run locally, but stock-media fetching, remote providers and some integrations require internet.
- AI required: No for basic script-to-video workflows using local assets; AI is central to the full agentic pipeline and optional/local engines are supported.
- Internet/API: Free Wikimedia Commons/Openverse/Internet Archive sources can work without API keys, while Pexels/Pixabay and cloud providers may require credentials/network.
- API key: Not required for the documented free-media path; provider-specific integrations can require keys.
- Local/self-hosted: Yes; Windows desktop, local web portal, CLI and Docker are documented.
- Basic non-AI workflow: provide a script plus local images/video, select local/free assets, render with the local pipeline, inspect MP4 output, and keep publishing/manual upload outside the tool.
- Runtime prerequisites: Node.js/npm, FFmpeg and the project's rendering/voice dependencies; GPU acceleration is optional depending on the selected pipeline.
- Limitation: fully autonomous generation still depends on AI/model components; external media sources are not offline and their individual licenses/attribution must be checked before publication.
- Source verified: official GitHub repository/documentation.
