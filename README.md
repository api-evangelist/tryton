# Tryton

Tryton is an open-source three-tier ERP (Enterprise Resource Planning) platform built on Python and PostgreSQL, designed for companies of any size. It is 100% open-source under the GPL v3 license with no per-user licensing fees.

## Overview

Tryton provides a comprehensive suite of business modules accessible via REST and XML-RPC APIs:

- Financial Accounting
- Stock and Inventory Management
- Sales Management
- Purchase Management
- Production / Manufacturing
- Project Management

## REST API

The Tryton REST API follows standard HTTP conventions:

- `GET /api/rest/<database>/<model.name>` — list records
- `POST /api/rest/<database>/<model.name>` — create a record
- `GET /api/rest/<database>/<model.name>/<id>` — retrieve a record
- `PUT /api/rest/<database>/<model.name>/<id>` — update a record
- `DELETE /api/rest/<database>/<model.name>/<id>` — delete a record
- `POST /api/rest/<database>/<model.name>/<id>/<button>` — trigger actions

### Authentication

Uses user application authentication. A dedicated application user is created per consumer.

### Headers

- `X-Tryton-Context` — JSON context dictionary for localization and session settings
- `X-Tryton-Usage` — comma-separated list of usage hints to customize response fields
- `Accept-Language` — standard header for language preference

### Pagination

Supports HTTP `Range` header for paginated requests with `Content-Range` responses. Also supports `s` (limit) and `p` (offset) query parameters.

### Filtering

Domain filtering via `d` query parameter (base64-encoded JSON domain). Ordering via `o` parameter.

## Resources

- **Website**: https://www.tryton.org/
- **Documentation**: https://docs.tryton.org/latest/
- **GitHub**: https://github.com/tryton
- **Discussion Forum / News**: https://discuss.tryton.org/c/news/25
- **Service Providers**: https://www.tryton.org/service-providers
- **LinkedIn Group**: https://www.linkedin.com/groups/1313967
- **X (Twitter)**: https://x.com/TrytonSoftware

## Latest Release

Tryton 8.0 LTS (May 2026) is the current Long Term Support release.

## APIs.json

This repository contains an [APIs.json](apis.yml) profile cataloging the Tryton API for the API Evangelist network.
