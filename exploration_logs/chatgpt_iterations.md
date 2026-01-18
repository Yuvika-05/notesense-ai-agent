## ChatGPT Exploration Log

### Iteration 1
Issue:
The agent jumped directly to final output.

Change:
Added strict "analysis only" instruction.

Reason:
To separate understanding from response generation.

---

### Iteration 2
Issue:
Agent inferred ownership of tasks.

Change:
Explicitly allowed uncertainty and prohibited assumptions.

Reason:
To reduce hallucination and improve reliability.

---

### Iteration 3
Result:
Clean separation between understanding, planning, and output.
