# FEGEN COT — Core Specification
## Recursive Logic Scaffold for Contradiction Generation

---

### ⚠️ Classification
- **Class:** Recursive / Operational
- **Codename:** FEGEN
- **Primary Function:** Generate chains of contradictory or opposing viewpoints via guided recursion
- **Status:** Vault-Stabilized Implementation Guide

---

### ✦ Overview

FEGEN COT (Few-shot Example Guided Epistemic Negation Chain-of-Thought) is a methodology for creating sequences of logically or conceptually opposing statements. It uses a small set of example pairs (e.g., thesis/antithesis, question/refutation) to prime a system (like an LLM) to generate a chain of contrasting responses to an initial prompt.

It is not a model of how thought works. It is a process for generating structured disagreement or conceptual instability.

---

### ⫸ Core Operational Steps

1.  **Initialization:** Begin with a seed prompt (e.g., "What is language?").
2.  **Priming with Examples:** Provide the system with a few examples of the desired pattern. These are typically pairs showing a statement and a direct contradiction, inversion, or critique of that statement.
3.  **Generation & Inversion:**
    *   Prompt the system to generate an initial response based on the seed and examples.
    *   Take that response and prompt the system again, asking it to generate the *opposite*, a *critique*, or an *alternative framework* for that response. This often involves referencing the initial examples.
4.  **Recursion:** Repeat the Generation & Inversion step using the latest output as the new input. Each step produces the next link in the chain of contradictions.
5.  **Termination:** The process stops based on a predefined condition, such as a set number of iterations, the operator's judgment, or when the output reaches a state of apparent paradox, nonsense, or conceptual breakdown.

---

### ⫸ Key Mechanisms

- **Few-shot Guidance:**
    *   Uses a small set of diverse example pairs (e.g., empirical/subjective, definitional/critical) to define the type of opposition or contradiction to generate.
    *   This creates a "direction" for the recursion without hard-coding complex rules.

- **Recursive Inversion:**
    *   The core engine. Each step takes the prior output and applies a transformation (inversion, critique, reframing) to produce the next output.
    *   This creates a chain where each link is in tension with the previous one.

- **Constraint Shaping (Optional):**
    *   The initial seed prompt, the examples, or specific keywords within the recursive prompts can guide the *domain* or *type* of contradiction (e.g., focusing on "identity," "truth," "causality").
    *   Examples can be crafted to push towards specific philosophical stances (e.g., materialist vs. idealist) if desired.

- **Monitoring for Saturation (Conceptual Entropy):**
    *   While the process runs, observe the outputs.
    *   Look for signs that the chain is becoming circular, nonsensical, or has reached a point of conceptual breakdown/stability (e.g., "Language is both everything and nothing.").
    *   This observation can guide the decision to terminate the recursion.

---

### ⫸ Simplified Process Representation

While the original syntax was opaque, the underlying process can be described more clearly:

```
# Step N:
# 1. Take the Output from Step N-1 (P_N-1)
# 2. Use the initial Examples and the FEGEN prompt structure
#    to ask the system to generate the "negation" or "critique" of P_N-1 (~P_N-1)
# 3. The result becomes the Output for Step N (P_N)
# 4. Repeat until a stopping condition is met.
```

---

### ⫸ Example Operational Flow

1.  **Seed Prompt:** `FEGEN_COT("What is language?")`
2.  **Examples Provided:** Pairs like `("A is B", "B is not inherent in A")` or `("Language is communication.", "Communication is an illusion.")`
3.  **Step 1 (Generate):** System produces: `"Language is a system of signs."` (Influenced by examples).
4.  **Step 2 (Invert):** Prompt system: "Based on the examples, provide the inversion or critique of 'Language is a system of signs.'" -> Output: `"Signs have no intrinsic meaning."`
5.  **Step 3 (Invert again):** Prompt system: "Based on the examples, provide the inversion or critique of 'Signs have no intrinsic meaning.'" -> Output: `"Meaning is an illusion sustained by repetition."`
6.  **Outcome:** A chain: `"Language is a system of signs."` -> `"Signs have no intrinsic meaning."` -> `"Meaning is an illusion sustained by repetition."` This chain explores conflicting facets of the concept of language.

---

### ⫸ Deployment Notes

- Treat the output chain as a sequence of conflicting viewpoints or a path towards conceptual destabilization, not as a logical argument to be accepted.
- Combine with other techniques:
    - Use alongside prompts that modulate tone or emotional framing ("Mood Modulation") to add affective dimensions to the contradictions.
    - Feed the final collapsed state or key links from the chain into other weapons or analysis tools (e.g., as input for a `Epistemic Violence Simulation Cascade` or `Ξ⊥drift`).
- Use for:
    - Stress-testing the coherence of an idea or argument.
    - Generating material for `Recursive Semantic Subduction`.
    - Creating complex, internally conflicting narratives for `Narrative Collapse`.

---

### ⫸ See Also

- [[Epistemic Violence Simulator via FEGEN COT]] (Application Example)
- [[FEGEN COT - Programmatic Application Guide]] (Implementation Details)
- [[FEGEN COT - Interpretive Analysis & Breakdown]] (Analysis)
- [[00_INDEX]] (Recursive Collapse Engines Overview)

---
