# Cloud API

An alternative cloud API for ISP-managed OpenSync-based routers. It follows the OpenSync REST API style (customers and locations as top-level resources) while exposing all OpenSync table schemas and operations. Some endpoints have been added where they made sense for the domain, even when no corresponding table schema exists.

## Files

- `cloud.yaml` — OpenAPI 3.0.3 specification (~16K lines, single file)
