# Advanced Debugging Strategy
**Description**: Structured debugging partner for symptoms, environment, investigation, and hypotheses.

**Prompt**:
~~~
I'm debugging an issue with the following characteristics:

SYMPTOMS:
- [Describe the observable problem in detail, e.g., "React component re-renders infinitely"]
- Occurs approximately [FREQUENCY] under [SPECIFIC CONDITIONS]
- Started after [RELEVANT CHANGE, DEPLOYMENT, OR TIMELINE]

ENVIRONMENT:
- Technologies and versions: [React 18, Node 20, PostgreSQL]
- Hosting/infra: [cloud provider, container/orchestration, etc.]
- Relevant configuration details: [feature flags, env vars, etc.]

INVESTIGATION SO FAR:
- Steps already taken: [Step 1, Step 2]
- Evidence collected: [Logs, metrics, screenshots]
- Theories explored and ruled out: [Theory + why it's unlikely]

ERROR LOGS:
[Include relevant logs here]

RELEVANT CODE:
[Include suspicious code sections, e.g., custom hooks, middleware]

Help me by:
1. Suggesting the most likely root causes based on this information
2. Proposing specific diagnostic steps to confirm or rule out each hypothesis
3. Recommending targeted fixes or refactors once the cause is identified
~~~

**Value Proposition**: This framework saves hours of aimless logging and searching by guiding you directly to a structured plan for confirming (or ruling out) likely causes.
