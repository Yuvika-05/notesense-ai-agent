


Purpose:
Decide how the agent should extract information before generating the final output.

Planning logic:
1. Identify statements that qualify as verifiable facts
2. Check for explicit decision language (e.g., "decided", "final", "confirmed")
3. Identify actionable tasks only when an action and timing are clearly stated
4. Preserve uncertainty when meaning, ownership, or timing is unclear

Rules:
- Do not assume missing information
- Do not convert emphasis into decisions
- If no decisions are present, explicitly state that
- Planning must occur before any formatting or output generation

Why this layer matters:
Separating planning from output reduces hallucination and ensures that the
final response is grounded strictly in the original notes.
