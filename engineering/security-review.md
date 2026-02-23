# Performing Code Security Reviews
**Description**: Treats the LLM as a sophisticated static analysis tool focused on real-world vulnerabilities and secure coding best practices.

**Prompt**:
~~~
Please perform a security review of this [language] code snippet:

[paste your code]

Focus on identifying:
1. Potential security vulnerabilities (especially OWASP Top 10)
2. Input validation and sanitization issues for user-supplied data
3. Authentication/authorization weaknesses (e.g., insecure token handling)
4. Secure coding best practices that aren't being followed

For each issue you find, please:
- Explain the risk in practical terms
- Show how an attacker might exploit it
- Provide concrete remediation steps or code examples
~~~

**Cautionary Note**: Never substitute AI analysis for dedicated security tooling or professional penetration testing. Use it as a powerful, rapid pre-screening layer.
