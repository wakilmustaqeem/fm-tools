# ScribeDog

- Official repository: snooky234/scribedog
- License: MIT.
- Type: private/local-first WYSIWYG Markdown writing studio with optional local or cloud AI.
- Offline: Yes for ordinary local writing/editing/export; optional update checks and cloud providers need network.
- AI required: No for core writing, note management and export. Local AI via Ollama, Jan.ai or LM Studio is optional.
- API key: Not required for non-AI/local use or local model use. Cloud AI uses the user's provider key.
- Local/self-hosted: Yes. Native desktop app and a self-hosted Server Edition are documented.
- Basic non-AI workflow: open a local folder, create/edit Markdown in WYSIWYG mode, organize linked notes/files, save locally, then export to PDF/DOCX/ODT/HTML.
- Runtime prerequisites: prebuilt desktop releases are available; source development uses Node/npm plus the Tauri toolchain. The project package currently uses Tauri 2, React 19, TypeScript and Vite.
- Internet boundary: ordinary local writing can stay on-device; cloud AI and the optional release-update check are network features.
- Limitation: cloud AI is outside the offline boundary; portable installers are unsigned according to the project documentation, so platform security warnings may appear.
- Source verified: official GitHub repository, current README/package metadata.
