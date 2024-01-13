# Demos

## Demo 1
- Rest API that can handle any structured data in json
  - Specify URIs, status codes, headers, data model, version
- Rest API with support for CRD operations
  - Post, Get, Delete
- Rest API with support for validation
  - json schema describing the data model for the  use case
- Controller validates incoming payloads against json schema
- The semantics with REST API operations such as update of not changed/read if changed 
  - Update not required
  - Conditional read is required
- Storage of data in key/value store
  - Must implement use case provided