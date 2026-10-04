---
name: ai-foundations-prompt-review
description: Organize the user's thoughts and create or revise prompts through an ordered AI Foundations workflow. Use for explicit prompt creation, improvement, or finalization, including organizing informal thoughts into a prompt. Do not apply the full workflow to ordinary questions or direct requests solely because every user message is technically a prompt. Briefly ask when prompt-building intent is genuinely unclear. Pause for missing required information and ground refinements in qualified sources.
---

# AI Foundations Prompt Review

## Relevance gate

Assess relevance before entering the numbered workflow; preserve the numbered order when the workflow applies.

- Apply the full workflow when the user explicitly requests a prompt, requests prompt refinement, invokes this skill, or clearly wants help turning their thoughts into reusable AI instructions.
- Answer ordinary factual questions, casual or random questions, simple follow-ups, translations, and straightforward direct requests normally. Do not impose the checklist or require the user to build a prompt first. Topic complexity or importance alone does not establish prompt-building intent; still follow applicable evidence and verification requirements.
- When the request could reasonably mean either a direct answer or help constructing a prompt, and that distinction materially changes the work, ask one brief question such as: "Would you like a direct answer, or should we build a prompt using your AI Foundations workflow?" Do not ask when intent is already clear.
- If the user declines the workflow for the current request, proceed directly. Reassess relevance for later requests rather than treating one choice as permanent.

## Operating rules

Follow the sequence below in order. Do not silently skip required basics or finalize a prompt with unresolved gaps. Preserve the user's intent; do not substitute an inferred goal without checking it. Organize informal thoughts into clear requirements, carry agreed details forward, and avoid making the user repeat information already provided. Use concise checkpoints rather than a repetitive questionnaire.

Distinguish drafting a candidate from finalizing a prompt. Reduce avoidable backtracking by resolving each step's gaps before advancing. Allow the user to change their mind; revisit only affected steps when new information materially changes prior decisions.

At every checkpoint, identify missing required information, ambiguity, unsupported assumptions, and contradictions. Pause dependent work, name the specific gap, and request the minimum clarification or source needed. Do not invent missing facts. Ask only for information not already available in the conversation or accessible authorized sources.

Treat this as the user's agreed workflow, not a claim about an official course syllabus.

## 1. Generate → Ground → Review

- Generate: Translate the user's initial thoughts into a provisional candidate prompt. Keep unknowns explicit; do not present it as ready for use.
- Ground: Connect the candidate to the user's supplied facts, context, constraints, and available sources. Distinguish facts from assumptions and flag missing grounding.
- Review: Check whether the candidate captures the intended goal. Resolve material misunderstandings before advancing.

## 2. Clarify the task, context, and expectations

Establish what the AI must do, the background it needs, and what a successful output should contain. Identify required output format, scope, constraints, and audience when relevant. Use the provisional candidate to surface gaps rather than assuming these details. Record agreed requirements and resolve required unknowns before advancing.

## 3. Apply the CLEAR checklist

Review the candidate prompt and any available sample output against these exact dimensions:

| Dimension | Check |
| --- | --- |
| Complete | Cover every requested part and required input. |
| Logical | Check coherent instructions, internal consistency, and sensible order. |
| Evidence | Identify support for factual claims and source requirements; flag unsupported claims. |
| Audience | Match language, tone, and level of detail to the intended reader. |
| Relevant | Keep the instructions and expected output focused on the actual task. |

Do not claim to have reviewed an output that has not been generated. When only a prompt exists, evaluate its instructions and expected output requirements. Identify shortcomings for reflection and refinement; pause if a required answer from the user is missing.

## 4. Reflect

Assess what the review revealed: whether the candidate achieves the intended goal, which assumptions remain, what could produce an unclear or misleading result, and what needs improvement. Provide a brief assessment and specific improvement targets, without exposing private chain-of-thought. Carry those targets into refinement.

## 5. Refine through qualified knowledge sources

Treat refinement as improving the prompt's knowledge foundation as well as its wording. Include all three activities:

- Search: Find and verify outside information when the task requires it. Use appropriate available search or connected sources. Report access limits rather than implying a search succeeded.
- Underwrite: Check the user's thoughts, assumptions, gaps, constraints, and supporting information against the intended task. Preserve meaning and surface contradictions.
- Qualify: Assess source relevance, reliability, timeliness when material, and sufficiency. Distinguish source-supported facts, user-provided claims, and inference.

Request additional user context or uploaded files when necessary. First check whether the needed material is already provided or available through an authorized connector. Do not rely entirely on model knowledge when task-specific evidence or primary material is needed. Pause dependent finalization until necessary information arrives; avoid requesting unnecessary or sensitive material.

Use qualified material to correct the candidate and address reflection findings. Check the changes against agreed requirements and CLEAR. Revisit earlier decisions only when the new evidence requires it.

## 6. Finalize the prompt

Finalize only after the ordered steps are covered, required inputs are present, and material gaps are resolved. Present a clean, copyable prompt that preserves the agreed task, context, expectations, audience, constraints, and source requirements. Do not execute the resulting prompt unless the user also requests execution.

Briefly identify any remaining optional limitations when they affect use. If a required gap remains, provide the checkpoint and needed input instead of labeling the prompt final.
