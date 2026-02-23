# Translating Code between Programming Languages
**Description**: Language-aware translation that respects idioms and conventions of the target ecosystem.

**Prompt**:
~~~
Please translate this code from [SOURCE LANGUAGE, e.g., Node.js] to [TARGET LANGUAGE, e.g., Python]:

[paste original code]

Requirements:
- Maintain identical functionality and behavior.
- Preserve error handling patterns (e.g., adapt Promises to Python's async/await or Go's error handling).
- Follow **idiomatic conventions** in the target language (e.g., Python PEP 8).
- Include any necessary library imports or dependencies.
- Adapt any platform-specific features appropriately (I/O, concurrency).

Additional context:
[provide any relevant information about the code's purpose, performance constraints, and environment]
~~~

**Tip**: Always carefully review and test translated code to accommodate language-specific optimizations and ensure adherence to best practices that improve readability and performance.
