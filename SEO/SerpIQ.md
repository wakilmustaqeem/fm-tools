# serpIQ

- Official repository: manojahi/serpiq
- License: MIT.
- Type: SEO audit CLI that reads a codebase and can use Google Search Console data.
- Offline: Partial — codebase analysis can run locally; GSC and cloud LLM providers require network access.
- AI required: No for basic codebase inspection; AI is used for the strategy/keyword-analysis workflow. Local Ollama is supported.
- API key: Cloud LLM providers require their own keys; GSC requires OAuth credentials. Ollama does not require a cloud API key.
- Local/self-hosted: Yes for the CLI and local Ollama path.
- Basic non-cloud workflow: inspect a local codebase with GSC skipped; use local Ollama only when AI analysis is desired.
- Runtime prerequisite: Node.js/TypeScript CLI environment plus the project's documented provider configuration.
- Internet boundary: local codebase inspection can remain local; GSC, cloud LLMs and other remote data sources need network access.
- Limitation: this is an SEO audit/strategy CLI, not a standalone offline SERP database.
- Source verified: official GitHub repository.
