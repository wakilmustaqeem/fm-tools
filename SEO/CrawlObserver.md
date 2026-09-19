# CrawlObserver

- Official repository: SEObserver/crawlobserver
- License: AGPL-3.0.
- Type: self-hosted high-performance SEO crawler with web UI, CLI, REST API and native desktop app.
- Offline: Partial — the crawler/UI can run locally, but crawling websites requires network access; ClickHouse can be installed locally for offline/local operation.
- AI required: No. Core crawling, SEO signal extraction, reporting and PageRank are non-AI workflows.
- API key: Not required for local crawling; project-scoped API keys are available for its REST API.
- Local/self-hosted: Yes; local binary and Docker/ClickHouse options are documented.
- Basic non-AI workflow: run locally, create a crawl session from seed URLs, inspect SEO signals/indexability/links, and export reports.
- Runtime prerequisites: platform-specific binary or Go 1.25+ for source builds; Windows uses Docker Desktop for the ClickHouse database.
- Internet boundary: target-site crawling and update/download operations require network access; local analysis/storage can remain on the machine.
- Source verified: official GitHub repository.