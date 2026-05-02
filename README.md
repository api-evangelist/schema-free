# Schema Free

Schema Free (schemaless) databases and APIs allow data to be stored and retrieved without a predefined fixed schema. Rather than enforcing structure at the database level, schema-free systems delegate schema management to the application layer. Key schema-free technologies include MongoDB, Redis, Apache Cassandra, Amazon DynamoDB, and Elasticsearch.

**URL:** [https://github.com/api-evangelist/schema-free](https://github.com/api-evangelist/schema-free)

## Tags

 - Schema Free, Schemaless, NoSQL, Document Store, Flexible Schema, MongoDB, DynamoDB, Elasticsearch

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### MongoDB Atlas Data API

The MongoDB Atlas Data API provides a REST API for accessing data stored in MongoDB Atlas clusters without requiring a MongoDB driver. MongoDB stores data in flexible, JSON-like BSON documents without a predefined schema.

**Human URL:** [https://www.mongodb.com/developer/products/atlas/atlas-data-api/](https://www.mongodb.com/developer/products/atlas/atlas-data-api/)

#### Tags

 - MongoDB, Document Store, NoSQL, Atlas

#### Properties

- [Documentation](https://www.mongodb.com/docs/atlas/app-services/data-api/)
- [Reference](https://www.mongodb.com/docs/atlas/app-services/data-api/openapi/)

### Amazon DynamoDB API

Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database with flexible schema — only the primary key attributes need to be defined at table creation.

**Human URL:** [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)

#### Tags

 - AWS, DynamoDB, NoSQL, Key-Value, Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)
- [Reference](https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/)

### Elasticsearch REST API

Elasticsearch is a distributed, RESTful search and analytics engine with dynamic mapping that automatically infers field types without predefined schema definitions.

**Human URL:** [https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html](https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html)

#### Tags

 - Elasticsearch, Search, Document Store, Analytics

#### Properties

- [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html)

### Redis JSON API (RedisJSON)

RedisJSON is a Redis module providing native JSON storage and retrieval capabilities for schema-free document storage in Redis.

**Human URL:** [https://redis.io/docs/data-types/json/](https://redis.io/docs/data-types/json/)

#### Tags

 - Redis, Key-Value, JSON, In-Memory

#### Properties

- [Documentation](https://redis.io/docs/data-types/json/)

## Common Properties

- [Website](https://www.mongodb.com/resources/basics/databases/nosql-explained/data-modeling)
- [JSON-LD](json-ld/schema-free-context.jsonld)
- [Vocabulary](vocabulary/schema-free-vocabulary.yml)

## JSON Schema

| Schema | Description |
|---|---|
| [schema-free-document-schema.json](json-schema/schema-free-document-schema.json) | Schema for a schema-free document with metadata conventions |

## JSON Structure

| Structure | Description |
|---|---|
| [schema-free-nosql-structure.json](json-structure/schema-free-nosql-structure.json) | Structural patterns for NoSQL document design |

## JSON-LD

| Context | Description |
|---|---|
| [schema-free-context.jsonld](json-ld/schema-free-context.jsonld) | JSON-LD context for schema-free document vocabulary |

## Examples

| Example | Description |
|---|---|
| [schema-free-mongodb-document-example.json](examples/schema-free-mongodb-document-example.json) | MongoDB document example demonstrating flexible schema patterns |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [schema-free-vocabulary.yml](vocabulary/schema-free-vocabulary.yml) | Schema-free database domain terminology and concepts |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
