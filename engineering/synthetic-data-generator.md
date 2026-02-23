# Generating Synthetic Data for Testing
**Description**: Generates realistic, varied data for development and testing that adheres to specific schemas and constraints.

**Prompt**:
~~~
I need synthetic test data for my [Node.js service/PostgreSQL database] project.

Data structure details:
- Model name: [entity name]
- Fields: [list all fields with their types and constraints, e.g., user_name: string(unique), price: float(2, > 0)]
- Relationships: [describe any relationships to other data models]

Requirements:
- Number of records: [specify how many records you need]
- Special cases to include: [e.g., very long strings, missing optional fields, unusual characters]
- Format: [JSON, CSV, SQL INSERT statements]
- Constraints: [any specific rules the data should follow]

The data should be varied enough to test:
- Typical user flows
- Edge cases and validation rules
- Filtering, sorting, and pagination behavior in my application
~~~

**Security Note**: This template ensures you get test data that is structurally valid (adhering to the schema) and behaviorally varied (testing edge cases and application features), leading to more robust application stability.
