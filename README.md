# Lagou (拉勾招聘)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
