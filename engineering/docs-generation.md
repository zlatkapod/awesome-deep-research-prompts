# Documentation Generation Framework
**Description**: Ensures comprehensive developer documentation covering intent, usage, architecture, and common edge cases.

**Prompt**:
~~~
Generate comprehensive developer documentation for this [FUNCTION/COMPONENT/MODULE]:

[YOUR CODE]

Structure the documentation as follows:
1. OVERVIEW
   - Purpose and primary functionality
   - When to use this component vs. alternatives
   - Architectural context (where it fits in the larger system)
2. TECHNICAL SPECIFICATION
   - API reference with all methods/properties
   - Parameters, return values, and types
   - State management (if applicable, e.g., using Redux/Context)
   - Events emitted/listened for
3. IMPLEMENTATION EXAMPLES
   - Basic usage example
   - Advanced configuration example
   - Customization/extensibility scenarios
4. TROUBLESHOOTING
   - Common errors and their solutions
   - Debugging strategies
   - Performance considerations
5. RELATED COMPONENTS
   - Dependencies
   - Components commonly used alongside this one

Format using markdown with proper headings, code blocks, tables, and emphasis where appropriate.
~~~
