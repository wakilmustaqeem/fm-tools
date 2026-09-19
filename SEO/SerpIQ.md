# serpIQ

- Official repository: manojahi/serpiq
- License: MIT.
- Type: SEO audit CLI that reads a codebase and can use Google Search Console data.
- Offline: Partial — codebase analysis can run locally, but GSC and cloud LLM providers require network access.
- AI required: Yes for the strategy/keyword-analysis workflow.
- Local AI: Ollama is supported and requires no API key.
- API key: Cloud LLM providers require their own keys; GSC requires OAuth credentials.
- Basic non-cloud workflow: use `--skip-gsc` and a local Ollama provider.
- Privacy: with Ollama, the project states the workflow can keep code/GSC data on the machine; external providers receive data according to their service.
- Source verified: official GitHub repository.
