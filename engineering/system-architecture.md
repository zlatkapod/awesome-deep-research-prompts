# Designing System Architecture
**Description**: Helps reason through modern system design with focus on statelessness, caching, scalability, and security.

**Prompt**:
~~~
To optimize the REST and GraphQL APIs for a high-traffic service, suggest a system architecture strategy considering:

CONTEXT:
- Use case: [brief description of the application, e.g., real-time auction platform]
- Traffic profile: [expected users, peak RPS, regions]
- Tech stack: [frontend framework, DB type, hosting/cloud provider]

Please address:
1. Architecture style
   - Separation of frontend and backend (headless) using frameworks like [React/Vue.js]
   - Microservices vs. Monolith approach
2. Performance & caching
   - Multi-layer caching (CDN, reverse proxy like Nginx, application cache like Redis)
   - Load balancing strategies
3. Scalability
   - Horizontal scaling strategies (containers, autoscaling groups)
   - Managing state (stateless services, distributed cache)
4. Observability & operations
   - Monitoring, logging, and alerting recommendations (e.g., Prometheus, ELK)
5. Security
   - Data encryption (in transit and at rest)
   - API hardening and Role-Based Access Control (RBAC)

Provide a detailed architectural recommendation with a high-level diagram description and trade-offs.
~~~

**Technical Focus**: The prompt explicitly asks for topics like Managing state (stateless vs. distributed cache) and Observability (Prometheus, ELK), ensuring the resulting design is production-ready.
