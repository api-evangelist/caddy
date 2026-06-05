# Caddy (caddy)

Caddy is a modern, extensible, open-source web server and reverse proxy written in Go that provides automatic HTTPS via Let's Encrypt, a dynamic JSON-based admin API, a human-friendly Caddyfile configuration format, and a modular architecture with a rich ecosystem of plugins for authentication, observability, and custom behavior.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/caddy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/caddy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** Open Source

## Tags

- Automatic HTTPS
- Go
- Load Balancer
- Reverse Proxy
- TLS
- Web Server

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Caddy Web Server

Caddy is an open-source HTTP/2 and HTTP/3 web server and reverse proxy that obtains TLS certificates automatically via Let's Encrypt and ZeroSSL. Configured via a native JSON config, a human-friendly Caddyfile, or dynamically via the admin API. Built on a modular architecture that supports custom modules for virtually any HTTP behavior.

- **Human URL:** [https://caddyserver.com/](https://caddyserver.com/)

#### Tags

- Automatic HTTPS
- Go
- Reverse Proxy
- TLS
- Web Server

#### Properties

- [Documentation](https://caddyserver.com/docs/)
- [Getting Started](https://caddyserver.com/docs/getting-started)
- [GitHub Repository](https://github.com/caddyserver/caddy)
- [Download](https://caddyserver.com/download)
- [OpenAPI](openapi/caddy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/caddy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/caddy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Caddy Admin API

Caddy exposes a RESTful administration API on localhost:2019 by default for dynamically loading and modifying server configuration at runtime without restarts. Endpoints support loading full JSON configs, traversing and mutating specific config paths, adapting Caddyfile to JSON, and querying PKI and reverse proxy state.

- **Human URL:** [https://caddyserver.com/docs/api](https://caddyserver.com/docs/api)
- **Base URL:** `http://localhost:2019`

#### Tags

- Admin API
- Configuration
- REST

#### Properties

- [Documentation](https://caddyserver.com/docs/api)
- [J S O N  Config  Structure](https://caddyserver.com/docs/json/)
- [Modules  Reference](https://caddyserver.com/docs/modules/)
- [A P I  Tutorial](https://caddyserver.com/docs/api-tutorial)
- [Postman Collection](collections/caddy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/caddy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://caddyserver.com/)
- [Documentation](https://caddyserver.com/docs/)
- [GitHub Organization](https://github.com/caddyserver)
- [Community  Forum](https://caddy.community/)
- [Download](https://caddyserver.com/download)
- [Sponsors](https://github.com/sponsors/mholt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
