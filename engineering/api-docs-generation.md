# Generating API Documentation
**Description**: Quick production of clean, consistent endpoint documentation including auth requirements and error formats.

**Prompt**:
~~~
Create documentation for this API endpoint:

Endpoint:
- Method: [HTTP method]
- Path: [path]
Purpose:
- [brief description]

Request parameters:
- [list parameters with types and whether they are required/optional]

Authentication:
- [requirements: e.g., Bearer token, API key, cookie-based]

Response format:
- [description of the response object, fields, and types]

Please format the documentation with:
- Clear and concise descriptions
- JSON-formatted request and response examples
- Common error scenarios with status codes and explanations (e.g., 401, 403, 404, 400)
- Markdown formatting suitable for developer docs
~~~

**Pro Tip**: To future-proof your process, ask the LLM to generate the documentation in the OpenAPI (YAML or JSON) format, making it instantly compatible with code generators and mocking tools.
