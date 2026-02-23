# Refactoring and Optimization Framework
**Description**: A comprehensive prompt to turn an AI into a dedicated refactoring assistant for specific language/framework stacks.

**Prompt**:
~~~
I have a [language] function in a [framework] project that needs refactoring.

Current code:
[paste code]

Issues I'd like to address:
[specific issue, e.g., low readability, high cyclomatic complexity]
[specific issue, e.g., non-optimal O(n^2) time complexity]

What I've considered:
[any approaches you've thought about, e.g., using a Map instead of an array filter]

Constraints:
[e.g., must remain backward compatible, no new dependencies, must be a pure function]

Please suggest refactored code with explanations for your changes, 
including trade-offs and any potential edge cases I should be aware of.
~~~

**Pro Tip**: Explicitly ask the AI to justify its performance suggestions by referencing Big O notation or common React performance pitfalls (like unnecessary state updates). Understanding the logic can help you better align the improvements with your project requirements.
