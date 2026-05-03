# Vegeta (vegeta)
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
