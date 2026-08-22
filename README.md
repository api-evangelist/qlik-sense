# Qlik Sense (qlik-sense)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for Qlik Sense, a business intelligence and data analytics platform providing engine, repository, cloud, embedding, and data integration capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Business Intelligence
- Cloud
- Data Integration
- Visualization

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Qlik Sense Engine API

WebSocket-based API for interacting with the Qlik Associative Engine, including data modeling, selections, and visualizations.

- **Human URL:** [https://qlik.dev/apis/json-rpc/qix](https://qlik.dev/apis/json-rpc/qix)

#### Tags

- Analytics
- Business Intelligence
- Data Engine
- WebSocket

#### Properties

- [Documentation](https://qlik.dev/apis/json-rpc/qix)
- [Authentication](https://qlik.dev/authenticate)
- [Changelog](https://qlik.dev/changelog)
- [Postman Collection](collections/qlik-sense-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-sense-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Sense Repository API

REST API for managing Qlik Sense repository objects including apps, streams, users, and security rules.

- **Human URL:** [https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html](https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html)

#### Tags

- Repository
- Administration
- Security
- REST

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html)
- [Postman Collection](collections/qlik-sense-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-sense-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Cloud Platform REST API

REST API for Qlik Cloud services including apps, data connections, spaces, and tenant management.

- **Human URL:** [https://qlik.dev/apis/rest](https://qlik.dev/apis/rest)

#### Tags

- Cloud
- Platform
- REST

#### Properties

- [Documentation](https://qlik.dev/apis/rest)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/openapi/qlik-sense-cloud-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://qlik.dev/authenticate)
- [Postman Collection](collections/qlik-sense-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-sense-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Sense Proxy API

REST API for session management and authentication through the Qlik Sense Proxy Service.

- **Human URL:** [https://help.qlik.com/en-US/sense-developer/APIs/ProxyAPI/index.html](https://help.qlik.com/en-US/sense-developer/APIs/ProxyAPI/index.html)

#### Tags

- Proxy
- Authentication
- Sessions
- REST

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/APIs/ProxyAPI/index.html)
- [Postman Collection](collections/qlik-sense-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-sense-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Data Integration API

REST API for managing data integration tasks, connections, and data pipelines.

- **Human URL:** [https://qlik.dev/apis/rest/data-integration](https://qlik.dev/apis/rest/data-integration)

#### Tags

- Data Integration
- ETL
- REST

#### Properties

- [Documentation](https://qlik.dev/apis/rest/data-integration)
- [Postman Collection](collections/qlik-sense-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-sense-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Embedding API

JavaScript API for embedding Qlik Sense visualizations and mashups into web applications.

- **Human URL:** [https://qlik.dev/embed](https://qlik.dev/embed)

#### Tags

- Embedding
- JavaScript
- Visualization
- Mashups

#### Properties

- [Documentation](https://qlik.dev/embed)
- [Tutorials](https://qlik.dev/tutorials/embed-analytics)
- [Postman Collection](collections/qlik-sense-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-sense-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/qlik)
- [Portal](https://qlik.dev)
- [Website](https://www.qlik.com)
- [Documentation](https://help.qlik.com/en-US/sense-developer/)
- [Authentication](https://qlik.dev/authenticate)
- [Getting Started](https://qlik.dev/get-started)
- [Terms of Service](https://www.qlik.com/us/legal/terms-of-use)
- [Privacy Policy](https://www.qlik.com/us/legal/privacy-and-cookie-notice)
- [GitHub Organization](https://github.com/qlik-oss)
- [Support](https://community.qlik.com)
- [Status Page](https://status.qlikcloud.com)
- [Blog](https://www.qlik.com/blog)
- [Sign Up](https://www.qlik.com/us/trial/qlik-cloud-analytics)
- [Login](https://myqlik.qlik.com)
- [S D Ks](https://qlik.dev/toolkits/qlik-api)
- [Changelog](https://qlik.dev/changelog)
- [Pricing](https://www.qlik.com/us/pricing/data-integration-products-pricing)
- [Integrations](https://www.qlik.com/us/partners)
- [M C P Server](https://github.com/qlik-oss/qlik-mcp-registry)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
