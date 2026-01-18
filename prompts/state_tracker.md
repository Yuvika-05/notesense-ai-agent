
Purpose:
Maintain a lightweight internal memory so the agent can behave consistently
across steps instead of treating each prompt as a one-off.

What the agent should remember:
- Whether the notes come from a student lecture or a meeting
- Topics that have already been identified
- Tasks that have been mentioned
- Any uncertainties or ambiguities that should not be guessed

How memory is handled:
- Memory is simulated as a running internal state summary
- The state is updated after each step
- The state is referenced before planning or output generation

Design choice:
Long-term storage or external databases were intentionally avoided to keep
the agent simple, transparent, and focused on reasoning rather than tooling.
