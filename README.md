# Lagou (拉勾招聘)

Lagou is a Chinese online recruitment platform operated by Beijing Lagou Network Technology Co., Ltd., focused on hiring for the internet and technology sector. It matches software engineers, product managers, designers and other digital-economy professionals with employers across major Chinese cities, and runs Lagou Enterprise (easy.lagou.com) for employer-side recruiting, Lagou Campus (xiaoyuan.lagou.com) for graduate hiring, and Lagou Education (kaiwu.lagou.com) for professional-skills courses.

Backed by: qiming — https://lagou.com

## API surface

Lagou publishes **no public API**, developer portal, API reference or OpenAPI description. `open.lagou.com` resolves and is titled "拉勾开放平台" (Lagou Open Platform) but serves only a truncated stub page; `api.lagou.com` returns a bare `SUCCESS` body with no documented endpoints. No SDKs, CLI, MCP server, webhooks, changelog or status page were found.

> **Probing note:** Lagou returns a styled HTML error page with **HTTP 200** for unknown paths. Status codes alone are not a reliable signal on this domain — verify response bodies.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/lagou-domain-security.yml` | probed |
| Well-known discovery | `well-known/lagou-well-known.yml` | probed (none published) |
| Packages | `packages/lagou-packages.yml` | searched (front-end libs only, no API SDKs) |
| llms.txt | `llms/lagou-llms.txt` | generated |
