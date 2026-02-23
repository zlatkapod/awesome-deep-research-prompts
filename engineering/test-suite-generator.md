# Test Suite Generator
**Description**: Expands test coverage across Functionality, Performance, Integration, and Security dimensions.

**Prompt**:
~~~
I need to create a comprehensive test suite for this function:

[FUNCTION CODE]

Please generate tests organized into these categories:

1. FUNCTIONAL CORRECTNESS
   - Happy path tests with various valid inputs
   - Edge case handling (empty inputs, boundary values, etc.)
   - Expected error conditions and error handling

2. PERFORMANCE CHARACTERISTICS
   - Tests verifying performance under expected loads
   - Tests for memory usage patterns
   - Time complexity verification for key operations

3. INTEGRATION POINTS
   - Tests for interactions with external dependencies
   - Mocking strategies for isolating the function
   - Testing side effects on the system

4. SECURITY CONSIDERATIONS
   - Input validation and sanitization tests
   - Authorization bypass attempts
   - Potential injection vectors

Use [Jest/Mocha/YOUR TESTING FRAMEWORK] syntax and follow AAA (Arrange-Act-Assert) pattern. 
Include setup and teardown where appropriate.
~~~

**Value Proposition**: By including PERFORMANCE CHARACTERISTICS, you force the LLM to generate micro-benchmarks or time complexity verification tests, making performance an inherent part of your testing workflow.
