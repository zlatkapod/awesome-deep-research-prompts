# Multi-Persona Code Review
**Description**: Simulates a mini review panel with three different lenses: security specialist, performance engineer, and maintainability expert.

**Prompt**:
~~~
Please review this code from three different perspectives:

1. As a security specialist:
   - Identify potential vulnerabilities, injection risks, or authentication issues
   - Mention any OWASP Top 10 concerns (e.g., XSS in React, prototype pollution in Node)

2. As a performance engineer:
   - Highlight inefficient patterns, memory leaks, or bottlenecks
   - Suggest more optimal data structures or algorithms if relevant (e.g., using memoization)

3. As a maintainability expert:
   - Point out unclear naming, complex logic, or architectural concerns
   - Suggest how to make the code easier to test and extend (e.g., better dependency injection)

CONTEXT:
- Tech stack: [React/Node.js/TypeScript]
- Runtime: [Node version / browser targets]
- Known constraints: [e.g., cannot introduce new dependencies]

CODE:
[YOUR CODE HERE]

For each role, provide:
- Concrete issues you see
- Suggested improvements
- Short rationale for each change
~~~

**Value Proposition**: The multi-persona approach ensures that performance isn’t gained at the expense of security, and code clarity isn’t sacrificed for minor optimization gains. It delivers deeper, more balanced feedback than a standard, single-focus prompt.
