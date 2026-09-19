# SerpBear

- Official repository: towfiqi/serpbear
- License: MIT.
- Type: self-hosted search-engine position tracking and keyword research app.
- Offline: No for live rank tracking — SERP collection requires external search/scraping sources or proxies; the application/database itself can run locally.
- AI required: No. Core rank tracking and keyword workflows are non-AI.
- API key: Usually required for a SERP scraping provider unless using configured proxies; Google Ads/Search Console integrations require their own credentials.
- Local/self-hosted: Yes; Next.js application with SQLite and Docker/deployment options.
- Basic non-AI workflow: deploy locally, add a domain and keywords, configure a SERP source/proxy, run tracking, then inspect rankings and reports.
- Runtime prerequisites: Node/Next.js or the documented Docker/deployment path; a SERP data source is needed for live tracking.
- Internet boundary: live Google/SERP retrieval, Search Console, Google Ads keyword research and email notifications require network access.
- Source verified: official GitHub repository; latest documented release is v3.1.0 (2026-03-27).