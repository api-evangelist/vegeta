# Vegeta (vegeta)

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

Vegeta is an open source HTTP load testing tool and library written in Go for generating constant request rates to measure API performance and reliability under sustained load. Supports CLI and library usage with attack plans, rate limiting, duration control, and detailed result metrics including latency histograms and success rates.

**URL:** [https://github.com/tsenart/vegeta](https://github.com/tsenart/vegeta)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Go, HTTP, Load Testing, Performance, Testing

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-03

## APIs

### Vegeta Load Testing Tool
Vegeta is an open source HTTP load testing tool and library written in Go for generating constant request rates. Supports targets from files or stdin, rate limiting (req/s), duration control, configurable timeouts, TLS settings, and multiple output formats (text, JSON, binary). Produces detailed result metrics including latency histograms, success rates, status code distributions, and throughput measurements.

**Human URL:** [https://github.com/tsenart/vegeta](https://github.com/tsenart/vegeta)

#### Tags:

 - Go, HTTP, Load Testing, Performance, Testing

#### Properties

- [Documentation](https://github.com/tsenart/vegeta#readme)
- [GitHub Repository](https://github.com/tsenart/vegeta)
- [JSONSchema - Attack Configuration Schema](json-schema/vegeta-attack-schema.json)
- [JSONSchema - Result Schema](json-schema/vegeta-result-schema.json)
- [JSONSchema - Metrics Schema](json-schema/vegeta-metrics-schema.json)
- [JSONStructure - Attack Configuration Structure](json-structure/vegeta-attack-structure.json)
- [JSONStructure - Result Structure](json-structure/vegeta-result-structure.json)
- [JSONStructure - Metrics Structure](json-structure/vegeta-metrics-structure.json)
- [Example - Attack Configuration Example](examples/vegeta-attack-example.json)
- [Example - Result Example](examples/vegeta-result-example.json)
- [Example - Metrics Example](examples/vegeta-metrics-example.json)

## Common Properties

- [Website](https://github.com/tsenart/vegeta)
- [Documentation](https://github.com/tsenart/vegeta#readme)
- [GitHub Organization](https://github.com/tsenart)
- [GitHub Repository](https://github.com/tsenart/vegeta)
- [Vocabulary - Vegeta Vocabulary](vocabulary/vegeta-vocabulary.yml)

## Features

| Name | Description |
|------|-------------|
| Constant Rate Attack | Generates HTTP requests at a constant rate (requests per second) for a specified duration, simulating sustained load on API endpoints. |
| Multiple Output Formats | Supports text, JSON, and binary result output formats with encoding/decoding support for pipeline-based workflows. |
| Latency Histograms | Produces detailed latency histograms with configurable buckets for analyzing p50, p95, p99, and max latency distributions. |
| Target Formats | Accepts HTTP targets from files or stdin with support for custom headers, request bodies, and per-target configuration. |
| TLS and Redirects | Configurable TLS settings including certificate pinning, insecure mode, and redirect following for testing secured endpoints. |
| Library API | Go library (vegeta/lib) for programmatic integration of load testing into test suites, CI/CD pipelines, and monitoring tools. |

## Use Cases

| Name | Description |
|------|-------------|
| API Performance Benchmarking | Measure API throughput, latency percentiles, and success rates at various request rates to establish performance baselines and SLA compliance. |
| Load Testing in CI/CD | Integrate vegeta as a library in Go test suites to run automated load tests as part of continuous integration pipelines. |
| Capacity Planning | Determine maximum sustainable request rates before latency degradation or error rates exceed acceptable thresholds for capacity planning. |
| Regression Detection | Compare latency and throughput metrics across API versions to detect performance regressions before deployment to production. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [vegeta-attack-schema.json](json-schema/vegeta-attack-schema.json)
- [vegeta-metrics-schema.json](json-schema/vegeta-metrics-schema.json)
- [vegeta-result-schema.json](json-schema/vegeta-result-schema.json)

### JSON Structure

- [vegeta-attack-structure.json](json-structure/vegeta-attack-structure.json)
- [vegeta-metrics-structure.json](json-structure/vegeta-metrics-structure.json)
- [vegeta-result-structure.json](json-structure/vegeta-result-structure.json)

### Examples

- [vegeta-attack-example.json](examples/vegeta-attack-example.json)
- [vegeta-metrics-example.json](examples/vegeta-metrics-example.json)
- [vegeta-result-example.json](examples/vegeta-result-example.json)

## Vocabulary

- [Vegeta Vocabulary](vocabulary/vegeta-vocabulary.yml) — Domain vocabulary covering 3 resources, 5 actions, and 3 personas for load testing attack configuration, result collection, and metrics analysis

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
