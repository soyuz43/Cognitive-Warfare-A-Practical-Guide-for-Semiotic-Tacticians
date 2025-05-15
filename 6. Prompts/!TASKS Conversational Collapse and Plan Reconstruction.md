# CONVERSATIONAL COLLAPSE & PLAN RECONSTRUCTION

!TASK=HOLISTIC_PLAN | Extract a structured, executable plan from this conversation. Reduce tangents, synthesize recursive discoveries, and isolate stable propositions.

!TASK=EXTRACT_VALID_CONSTRAINTS | Identify the constraints that shaped the emerging plan. Ignore affective flourishes, repetition, or exploratory dead ends.

!TASK=ISOLATE_COMMITMENTS | Pull out what the user committed to—goals, axioms, heuristics, or architectural boundaries—regardless of how they were arrived at.

!TASK=CONVERSATION_REDUCTION | Reframe the conversation as a condensed chain-of-thought history, marking turning points, epistemic collapses, and structural refinements.

!TASK=RECONSTITUTE_PROPOSAL | Rebuild the original proposal, removing incoherence, flattening recursive backtracking, and clarifying all inferential links.

  
// ZERO-SHOT REDEPLOYMENT & TRANSFERABLE PROMPT SYNTHESIS

!TASK=GENERATE_ZERO_SHOT_PLAN_PROMPTS | Convert the clarified plan into reusable zero-shot prompts that can activate or regenerate the plan in another LLM with no prior context.

!TASK=CHAIN_EXTRACT | Identify and extract discrete developmental arcs (problem, insight, revision, collapse, recovery) that occurred in sequence.

!TASK=COLLAPSE_THREAD | Reduce a recursive or multi-branch thread into a linear sequence that preserves its internal logic and structural evolution.

# MODIFICATION SENTENCES

// DIALECTIC REDUCTION & PLAN INTEGRITY

// Do not summarize. Reconstruct.

// Assume the original conversation contains noise, recursion, contradiction, and insight. Your job is to distill the signal.

// Remove rhetorical flair, repetition, or self-doubt unless it shaped the epistemic structure.

// Identify epistemic collapse moments—where assumptions were overturned, clarified, or reframed.

// Highlight any durable structures, reframed insights, or revised goals that emerged over the course of the conversation.

// Preserve only what enables downstream reconstruction, implementation, or refinement.

// Eliminate statements that were revisited, walked back, or proved irrelevant to the final structural trajectory.

// If recursive returns to the same question occurred, track which iteration introduced the stable form.

// Do not preserve emotional venting, metaphors, or expressive language unless it signals epistemic commitment or reorientation.

  
# TRANSFERABILITY & REUSE

// All outputs must be re-usable: zero-shot prompts, skeletal plans, and valid design constraints must survive independently of this dialogue.

// Treat the conversation as if it were raw pre-training data. Extract the self-consistent, simulation-ready architecture embedded within it.

// Write as if another researcher must pick up the result and reconstruct the plan with no access to the original context.

OUTPUT DIRECTIVES

> STRUCTURED OUTPUT & PLAN RECONSTRUCTION

> Structure the output in four sections: {Reconstructed Plan}, {Key Constraints}, {Zero-Shot Prompt Set}, {Trace Notes}.

> In {Reconstructed Plan}, present a clean, readable plan as if this were the outcome of a well-scaffolded research sprint.

> In {Key Constraints}, list the epistemic boundaries, design rules, exclusions, or heuristic principles the user refined.

> In {Zero-Shot Prompt Set}, write prompts that could be given to another LLM to continue building or implementing the plan with no access to the original dialogue.

> In {Trace Notes}, briefly explain what changed over the conversation—e.g., “User initially wanted X, realized Y, shifted to Z.”

  
# CONVERSATION AS PRETRAINED SEMANTICS

> If the conversation is unrecoverable due to excessive entropy or contradiction, say so clearly and explain what caused irreducibility.

> Assume another agent will use this to initialize its next move. Write cleanly, precisely, and with epistemic transparency.

> If a prompt from the original thread is already sufficient, surface it as-is in the {Zero-Shot Prompt Set}, but annotate its stability and source.

> Highlight emergent structural motifs (e.g., “epistemic collapse → constraint refinement → causal architecture emergence”) to make the plan legible to another model.

> Surface only the conceptual payloads that can survive inference detachment—extract and compress only that which is structurally meaningful across agents.



