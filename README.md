# Apache Pulsar (apache-pulsar)
Apache Pulsar is a cloud-native, distributed messaging and streaming platform that provides server-to-server messaging with multi-tenancy, high performance, and geo-replication. It combines messaging and stream processing in a single platform.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Native, Messaging, Multi-Tenant, Pub-Sub, Streaming, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Pulsar Admin REST API
The Pulsar Admin API provides REST endpoints for managing tenants, namespaces, topics, subscriptions, functions, connectors, and cluster configuration.

**Human URL:** [https://pulsar.apache.org/admin-rest-api/](https://pulsar.apache.org/admin-rest-api/)

#### Tags:

 - Administration, Multi-Tenant, REST

#### Properties

- [Documentation](https://pulsar.apache.org/admin-rest-api/)
- [OpenAPI](openapi/pulsar-admin.yml)

### Apache Pulsar Messaging API
Pulsar messaging protocol for producing and consuming messages on topics, with support for multiple subscription types (Exclusive, Shared, Failover, Key_Shared), schema enforcement, and both persistent and non-persistent topics.

**Human URL:** [https://pulsar.apache.org/docs/next/client-libraries/](https://pulsar.apache.org/docs/next/client-libraries/)

#### Tags:

 - Messaging, Pub-Sub, Streaming

#### Properties

- [Documentation](https://pulsar.apache.org/docs/next/client-libraries/)
- [AsyncAPI](asyncapi/pulsar-messaging.yml)
- [JSONSchema](json-schema/pulsar-message.json)

## Common Properties

- [GitHubOrganization](https://github.com/apache/pulsar)
- [Documentation](https://pulsar.apache.org/)
- [SpectralRules](rules/apache-pulsar-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-pulsar-vocabulary.yaml)
- [NaftikoCapability](capabilities/pulsar-workflow.yaml)
- [JSON-LD](json-ld/apache-pulsar-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Multi-Tenancy | Native multi-tenancy with tenant and namespace isolation |
| Persistent Messaging | Durable message storage with Apache BookKeeper |
| Geo-Replication | Built-in geo-replication across data centers and clouds |
| Pulsar Functions | Lightweight serverless compute natively integrated with messaging |
| Tiered Storage | Offload old data to object storage (S3, GCS) for cost efficiency |
| Schema Registry | Built-in schema registry for producers and consumers |
| Multiple Subscription Types | Exclusive, Shared, Failover, and Key_Shared subscription modes |

## Use Cases

| Name | Description |
|------|-------------|
| Real-Time Event Streaming | Stream events between microservices with guaranteed delivery |
| Message Queue | Use Shared subscription as a traditional message queue |
| Event Sourcing | Store and replay event streams for event-driven architectures |
| IoT Data Ingestion | Ingest high-volume IoT telemetry into Pulsar topics |

## Integrations

| Name | Description |
|------|-------------|
| Apache Flink | Pulsar connector for Flink stream processing |
| Apache Spark | Spark Streaming integration via Pulsar connector |
| Apache Kafka | Kafka-compatible protocol support for migration |
| Kubernetes | Native Kubernetes deployment via Helm charts |
| Grafana | Built-in metrics exposed to Prometheus and Grafana |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Pulsar Admin REST API](openapi/pulsar-admin.yml)

### AsyncAPI

- [Apache Pulsar Messaging API](asyncapi/pulsar-messaging.yml)

### JSON Schema

- [Pulsar Message](json-schema/pulsar-message.json)
- [Cluster Data](json-schema/apache-pulsar-cluster-data-schema.json)
- [Tenant Info](json-schema/apache-pulsar-tenant-info-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Pulsar JSON Structures](json-structure/)

### JSON-LD

- [Apache Pulsar Context](json-ld/apache-pulsar-context.jsonld)

### Examples

- [Apache Pulsar Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Messaging Workflow](capabilities/pulsar-workflow.yaml) | Apache Pulsar | 8 | Platform Engineer, Application Developer |

## Vocabulary

- [Apache Pulsar Vocabulary](vocabulary/apache-pulsar-vocabulary.yaml) — Unified taxonomy mapping messaging and streaming resources, actions, workflows, and personas

## Rules

- [Apache Pulsar Spectral Rules](rules/apache-pulsar-spectral-rules.yml) — Rules enforcing Apache Pulsar API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
