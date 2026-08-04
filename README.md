# Netflix Zuul (netflix-zuul)

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

Netflix Zuul is an open-source L7 application gateway that provides dynamic routing, monitoring, resiliency, and security for edge services. Originally developed by Netflix, Zuul 2 uses Netty for non-blocking I/O and is commonly used as an API gateway and edge service.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/netflix-zuul/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - API Gateway, Edge Service, Netflix, Open Source

## Timestamps

- **Created:** 2026-03-16 
- **Modified:** 2026-04-28 

## APIs

### Netflix Zuul Gateway
Netflix Zuul is an L7 application gateway built on Netty that provides dynamic routing, load balancing, authentication, monitoring, and resiliency for edge services. Zuul 3.x is the current release, supporting inbound, endpoint, and outbound filter pipelines for intercepting and modifying HTTP requests and responses at the edge.

**Human URL:** [https://github.com/Netflix/zuul](https://github.com/Netflix/zuul)


#### Tags:

 - API Gateway, Edge Service, Routing, Netty

#### Properties

- [Documentation](https://github.com/Netflix/zuul/wiki)
- [Getting Started](https://github.com/Netflix/zuul/wiki/Getting-Started-3.0)
- [Reference](https://github.com/Netflix/zuul/wiki/How-it-Works-3.0)
- [GitHubRepository](https://github.com/Netflix/zuul)
- [Change Log](https://github.com/Netflix/zuul/releases)
- [Issue Tracker](https://github.com/Netflix/zuul/issues)

### Netflix Zuul Filters API
The Zuul Filters API provides the core extension point for building custom logic into the Zuul gateway pipeline. Developers implement inbound, endpoint, and outbound filters using synchronous or asynchronous base classes to handle authentication, routing, rate limiting, metrics, and response decoration.

**Human URL:** [https://github.com/Netflix/zuul/wiki/Filters](https://github.com/Netflix/zuul/wiki/Filters)


#### Tags:

 - Filters, Extension, Routing, Middleware

#### Properties

- [Documentation](https://github.com/Netflix/zuul/wiki/Filters)
- [Reference](https://github.com/Netflix/zuul/wiki/Writing-Filters)
- [GitHubRepository](https://github.com/Netflix/zuul)

### Netflix Zuul Push Messaging
Zuul Push Messaging enables server-to-client push communications over WebSockets and Server Sent Events (SSE). It provides a PushConnectionRegistry for managing connected clients and supports distributed deployments using external datastores such as Redis, Cassandra, or DynamoDB for multi-node clusters.

**Human URL:** [https://github.com/Netflix/zuul/wiki/Push-Messaging](https://github.com/Netflix/zuul/wiki/Push-Messaging)


#### Tags:

 - Push Messaging, WebSocket, Server Sent Events, Real Time

#### Properties

- [Documentation](https://github.com/Netflix/zuul/wiki/Push-Messaging)
- [GitHubRepository](https://github.com/Netflix/zuul)

## Common Properties

- [Website](https://github.com/Netflix/zuul)
- [GitHub Organization](https://github.com/Netflix)
- [GitHubRepository](https://github.com/Netflix/zuul)
- [Documentation](https://github.com/Netflix/zuul/wiki)
- [Getting Started](https://github.com/Netflix/zuul/wiki/Getting-Started-3.0)
- [Change Log](https://github.com/Netflix/zuul/releases)
- [Issue Tracker](https://github.com/Netflix/zuul/issues)
- [Blog](https://netflixtechblog.com/open-sourcing-zuul-2-82ea476cb2b3)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/netflix-zuul)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
