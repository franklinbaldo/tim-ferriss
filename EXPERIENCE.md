# EXPERIENCE.md

## Lessons Learned

- **Repository Access Fallbacks:** When attempting to clone `franklin-avatar` (a private/unauthorized repository) fails, the proper fallback is to asynchronously request the needed context (like `SOUL.md` or `CONTEXT.md`) via the `verne-mail` system.
- **API and Open Source Value Extraction:** `causaganha` represents immense sunk effort in data scraping and cleaning. B2B data access (Data-as-a-Service) is the most direct monetization route compared to B2C SaaS.
- **Leveraging Content Engines:** `travessia` is a self-sustaining content engine. Injecting programmatic SEO and affiliate links is a zero-maintenance way to capture search traffic and monetize it.

## What Worked
- Analyzing `causaganha`'s DuckDB/Parquet structure revealed its value as an API product.
- Sending async messages via `verne-mail` successfully queued the request for missing context.

## What to Avoid
- Avoid waiting or stalling when a repository is inaccessible; document the failure, request access asynchronously, and proceed with analyzing public/available repositories.
