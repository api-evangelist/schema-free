# Schema Free (schema-free)

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

Schema Free (schemaless) databases and APIs allow data to be stored and retrieved without a predefined fixed schema. Rather than enforcing structure at the database level, schema-free systems delegate schema management to the application layer. This enables rapid prototyping, flexible document storage, and agile development workflows. Key schema-free technologies include MongoDB (document store), Redis (key-value store), Apache Cassandra (wide-column store), Amazon DynamoDB (managed NoSQL), Elasticsearch (search/document store), and Apache CouchDB. While called "schemaless," these systems typically have implicit application-level schemas that must be managed carefully.

**APIs.json:** [https://github.com/api-evangelist/schema-free](https://github.com/api-evangelist/schema-free)

## Tags

- Schema Free
- Schemaless
- NoSQL
- Document Store
- Flexible Schema
- MongoDB
- DynamoDB
- Elasticsearch

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### MongoDB Atlas Data API

The MongoDB Atlas Data API provides a REST API for accessing data stored in MongoDB Atlas clusters. MongoDB is a document-oriented NoSQL database that stores data in flexible, JSON-like BSON documents without requiring a predefined schema. The Atlas Data API supports CRUD operations, aggregation pipelines, and real-time data access without needing a MongoDB driver.

- **Human URL:** [https://www.mongodb.com/developer/products/atlas/atlas-data-api/](https://www.mongodb.com/developer/products/atlas/atlas-data-api/)
- **Base URL:** `https://data.mongodb-api.com/app/{App ID}/endpoint/data/v1`

#### Tags

- MongoDB
- Document Store
- NoSQL
- Atlas

#### Properties

- [Documentation](https://www.mongodb.com/docs/atlas/app-services/data-api/)
- [Reference](https://www.mongodb.com/docs/atlas/app-services/data-api/openapi/)
- [Postman Collection](collections/schema-free.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-free.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon DynamoDB API

Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database service. DynamoDB tables have a flexible schema — only the primary key attributes need to be defined at table creation. All other attributes can vary from item to item, enabling schema-free document storage with the scalability and management of a managed cloud service.

- **Human URL:** [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)
- **Base URL:** `https://dynamodb.us-east-1.amazonaws.com`

#### Tags

- AWS
- DynamoDB
- NoSQL
- Key-Value
- Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)
- [Reference](https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/)
- [Postman Collection](collections/schema-free.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-free.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Elasticsearch REST API

Elasticsearch is a distributed, RESTful search and analytics engine built on Apache Lucene. Elasticsearch uses a schemaless approach where documents can be indexed without a predefined mapping, with dynamic mapping automatically inferring field types. It is commonly used for full-text search, log analytics, and real-time data exploration.

- **Human URL:** [https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html](https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html)
- **Base URL:** `https://localhost:9200`

#### Tags

- Elasticsearch
- Search
- Document Store
- Analytics

#### Properties

- [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html)
- [Postman Collection](collections/schema-free.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-free.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Redis JSON API (RedisJSON)

RedisJSON is a Redis module that provides native JSON storage and retrieval capabilities. Redis is a key-value store that supports schema-free JSON documents (via RedisJSON), allowing applications to store, update, and query JSON documents without schema constraints.

- **Human URL:** [https://redis.io/docs/data-types/json/](https://redis.io/docs/data-types/json/)
- **Base URL:** `https://your-redis-host:6379`

#### Tags

- Redis
- Key-Value
- JSON
- In-Memory

#### Properties

- [Documentation](https://redis.io/docs/data-types/json/)
- [Postman Collection](collections/schema-free.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-free.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.mongodb.com/resources/basics/databases/nosql-explained/data-modeling)
- [JSON Schema](json-schema/schema-free-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/schema-free-nosql-structure.json)
- [J S O N L D Context](json-ld/schema-free-context.jsonld)
- [Vocabulary](vocabulary/schema-free-vocabulary.yml)
- [Integrations](https://www.mongodb.com/company/partners)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
