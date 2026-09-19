# OpenReel Video

- Official repository: Augani/openreel-video
- License: MIT
- Offline: Yes for the core editor after the web app assets are available; editing is client-side and video files are not uploaded.
- AI required: No for core editing; AI upscaling is an optional feature.
- Internet/API: No cloud upload is required for editing, but opening the web app and obtaining its assets normally requires network unless self-hosted locally.
- API key: Not required for core editing.
- Local/self-hosted: Yes; the browser editor can be self-hosted, and desktop/native offload work is documented.
- Basic non-AI workflow: open the local/browser editor, import local video, edit tracks/text/audio/color, preview and export MP4/WebM without uploading source footage.
- Runtime prerequisites: supported Chromium browser with WebGPU/WebCodecs for the browser workflow; source development uses Bun/pnpm/Node-compatible tooling as documented.
- Limitation: some advanced/native export paths depend on FFmpeg licensing/build choices; collaborative editing and some roadmap features remain incomplete.
- Source verified: official GitHub repository/documentation.
