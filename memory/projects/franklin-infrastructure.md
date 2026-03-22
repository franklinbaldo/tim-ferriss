# memory/projects/franklin-infrastructure.md

## Status
Active — identifying and documenting potential automated revenue streams based on Franklin's current projects.

## Related
- Strategy overview: `MEMORY.md`
- Latest revenue stream report: `reports/2026-03-22.md`
- Context/Access Request: `mail/outbox/` (sent message to franklin-avatar)

## Infrastructure Analysis

### `causaganha` (Data Lake)
- Massive, automated daily scraper for Brazilian judicial data.
- Stores data as consolidated Parquet files and DuckDB catalogs on Internet Archive.
- Entity resolution (UUIDv5) already handles lawyer and party deduplication.
- **Monetization Idea**: Package and sell direct API access or data shares (Snowflake/BigQuery) to law firms and credit agencies. (B2B DaaS)

### `verne` (Agent OS)
- A highly polished React/Vite interface for the Jules API.
- Handles session/source management with a local PWA architecture.
- **Monetization Idea**: Package as a premium "Indie OS" or SaaS boiler plate. Offer "Pro" features like advanced prompt templates or multi-cloud sync via a one-time purchase license.

### `travessia` (Content Engine)
- A multi-agent fiction/dialogue system that generates rich philosophical text autonomously and builds a static Astro.js site.
- **Monetization Idea**: Monetize the traffic it generates via programmatic SEO constraints in the agent prompts and affiliate links (Amazon Associates) injected into the Astro templates.
