# Apache Pulsar (apache-pulsar)

Apache Pulsar is a cloud-native, distributed messaging and streaming platform that provides server-to-server messaging with multi-tenancy, high performance, and geo-replication. It combines messaging and stream processing in a single platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Native
- Messaging
- Multi-Tenant
- Pub-Sub
- Streaming
- Apache
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Pulsar Admin REST API

The Pulsar Admin API provides REST endpoints for managing tenants, namespaces, topics, subscriptions, functions, connectors, and cluster configuration.

- **Human URL:** [https://pulsar.apache.org/admin-rest-api/](https://pulsar.apache.org/admin-rest-api/)
- **Base URL:** `http://localhost:8080/admin/v2`

#### Tags

- Administration
- Multi-Tenant
- REST

#### Properties

- [Documentation](https://pulsar.apache.org/admin-rest-api/)
- [OpenAPI](openapi/pulsar-admin.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pulsar-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pulsar-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Pulsar Messaging API

Pulsar messaging protocol for producing and consuming messages on topics, with support for multiple subscription types (Exclusive, Shared, Failover, Key_Shared), schema enforcement, and both persistent and non-persistent topics.

- **Human URL:** [https://pulsar.apache.org/docs/next/client-libraries/](https://pulsar.apache.org/docs/next/client-libraries/)

#### Tags

- Messaging
- Pub-Sub
- Streaming

#### Properties

- [Documentation](https://pulsar.apache.org/docs/next/client-libraries/)
- [AsyncAPI](asyncapi/pulsar-messaging.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/pulsar-message.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/pulsar-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pulsar-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/apache/pulsar)
- [Documentation](https://pulsar.apache.org/)
- [Spectral Rules](rules/apache-pulsar-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-pulsar-vocabulary.yaml)
- [JSON-LD](json-ld/apache-pulsar-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://pulsar.apache.org/ecosystem/)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
