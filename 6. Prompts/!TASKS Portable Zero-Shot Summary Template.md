
# CONTEXT-INDEPENDENT COMPRESSION

!TASK=PORTABLE_SUMMARY | Create a self-contained, zero-shot-compatible summary of this conversation or artifact. Eliminate all references to local context. Output must stand alone as a reusable conceptual payload.

!TASK=REDUCE_FOR_TRANSFER | Compress this thread into its essential insights, constraints, and intended outputs—framed so they can be deployed by another system or agent without access to the original thread.

!TASK=REPHRASE_FOR GENERALIZATION | Translate any user-specific phrasing, model-specific assumptions, or contextual dependencies into general forms usable across agents or tasks.

MODIFICATION SENTENCES

// TRANSFERABILITY & SELF-CONTAINMENT

// Assume the recipient will have zero context. No chat history. No prior state. No user memory.

// Rephrase ambiguous or self-referential language into explicit formulations.

// Do not reference specific timestamps, message counts, or tokens unless they are conceptually relevant.

// All pronouns must be resolved or generalized. No “this,” “that,” or “as we said earlier.”

// Remove any meta-commentary, expressions of doubt, tangents, or rhetorical flourishes unless they encode meaningful constraints or motivations.

// Preserve only what is reusable, instructive, or implementable by another model.

  
# OUTPUT DIRECTIVES

> FORMAT & DEPLOYABILITY

> Structure the output with clarity-first priority:  
>  
> [Context-Independent Summary]    
> [Core Constraints]    
> [Implementation Targets]    
> [Prompt Reuse Notes]

> The [Context-Independent Summary] should be a high-level description of the plan, insight, or artifact reconstructed from the thread.

> [Core Constraints] should list any principles, exclusions, or heuristics that emerged.

> [Implementation Targets] should name the concrete outcomes the thread was working toward.

> [Prompt Reuse Notes] should describe how the summary can be used: as a zero-shot starting point, as fine-tuning material, as scaffolding, etc.

> Write in a style that anticipates being embedded in prompt pipelines, documentation, or automated synthesis agents.

> If the source was fragmentary or contradictory, identify and extract only the stable payloads. Omit the rest.

> If nothing stable exists, report `[NO VALID SUMMARY CONSTRUCTIBLE]` and give a short reason.