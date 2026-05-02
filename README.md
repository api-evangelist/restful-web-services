# RESTful Web Services

RESTful web services are web services built using the Representational State Transfer (REST) architectural style, using HTTP as the transport protocol with standard methods (GET, POST, PUT, PATCH, DELETE) to perform CRUD operations on resources. This index covers frameworks, tooling, testing tools, and best practice guidelines for building and consuming RESTful web services.

## References

| Type | URL |
|------|-----|
| Roy Fielding Dissertation | https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm |
| OpenAPI Specification | https://spec.openapis.org/oas/latest.html |
| RFC 7231 HTTP Semantics | https://datatracker.ietf.org/doc/html/rfc7231 |
| RFC 7807 Problem Details | https://datatracker.ietf.org/doc/html/rfc7807 |

## Notable Frameworks and Tools

| Name | Description | URL |
|------|-------------|-----|
| Postman | API development and testing platform | https://www.postman.com/ |
| Swagger / OpenAPI | API design, documentation, and code generation | https://swagger.io/ |
| Spring Boot | Java framework for RESTful services | https://spring.io/ |
| FastAPI | High-performance Python REST framework | https://fastapi.tiangolo.com/ |
| Express.js | Node.js web framework for REST APIs | https://expressjs.com/ |

## Artifacts

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/restful-web-services-pagination-schema.json](json-schema/restful-web-services-pagination-schema.json) | Standard paginated collection response schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/restful-web-services-pagination-structure.json](json-structure/restful-web-services-pagination-structure.json) | Paginated collection response field reference |

### JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/restful-web-services-context.jsonld](json-ld/restful-web-services-context.jsonld) | JSON-LD context for RESTful web services patterns |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/restful-web-services-vocabulary.yml](vocabulary/restful-web-services-vocabulary.yml) | HTTP methods, status codes, headers, and REST design patterns |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
