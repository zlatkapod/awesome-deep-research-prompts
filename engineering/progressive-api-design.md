# Progressive API Design
**Description**: Enforces a staged, incremental design process from core resource definition to advanced documentation.

**Prompt**:
~~~
I'm designing a RESTful API for a [SPECIFIC DOMAIN] system.
Let's develop this progressively:

STAGE 1: Core resource definition
- Define the essential resources and their relationships
- Specify primary attributes for each resource
- Outline basic CRUD operations

STAGE 2: Interaction patterns
- Define specialized endpoints beyond CRUD
- Specify query parameters and filtering capabilities
- Design pagination and sorting approaches

STAGE 3: Advanced considerations
- Authentication and authorization patterns
- Rate limiting and quota strategies
- Caching directives and ETag implementation
- Versioning approach
- Error handling standardization (error format, codes)

STAGE 4: Documentation and examples
- Generate OpenAPI specifications
- Provide example requests/responses for common operations
- Document best practices for API consumers

Let's start with Stage 1 using these details:
[YOUR SPECIFIC API DOMAIN DETAILS, BUSINESS RULES, AND CLIENT USE CASES]
~~~

**Pro Tip**: The prompt ensures the output is compatible with industry standards by asking for OpenAPI specifications (Swagger) in the final stage, making documentation generation a seamless step.
