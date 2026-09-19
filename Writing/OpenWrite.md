# OpenWrite

- Official repository: ilrein/openwrite
- License: AGPL-3.0.
- Type: self-hostable AI-assisted long-form fiction writing platform for novels, screenplays and creative writing.
- Offline: Partial. Local development uses a local Cloudflare D1/SQLite database, but the normal web app, authentication and provider-backed AI are network-oriented.
- AI required: No for basic manuscript editing, chapter management and Markdown export; AI is optional for story-map generation and writing assistance.
- API key: Cloud AI providers require the user's own provider key. Local Ollama can avoid a cloud API key.
- Local/self-hosted: Yes. The project documents local development and Cloudflare Worker + D1 self-hosting.
- Basic non-AI workflow: run the local app, create a project, organize chapters, write in the rich-text editor, track word counts/progress, and export the manuscript as Markdown without enabling AI.
- Runtime prerequisites: Bun, local Wrangler/Cloudflare D1 tooling, and the repository's environment variables for auth/encryption. The project uses React/TanStack Router, Hono, D1/SQLite, Drizzle and Vitest.
- Internet boundary: local development can use local D1, but deployment, hosted access, external authentication and cloud AI providers require network access.
- Limitation: several roadmap items remain incomplete, including DOCX/EPUB export and real-time collaboration; this is a focused fiction-writing platform rather than a general-purpose notes editor.
- Source verified: official GitHub repository and current README/license information.
