---
name: agent-workflow
description: Follow a chronological workflow for bounded, multi-step agent tasks that create or update a reviewable deliverable. Use when the user requests agent work, invokes this skill, or asks for a project brief, account brief, launch review, operations review, communications review, variance review, experiment review, or release-readiness review. Gather context, define the goal, specify output and constraints, execute independently, review, refine, request mandatory human approval, and reuse proven work. Do not impose the full workflow on casual questions or simple factual answers.
---

# Agent Workflow

Complete the authorized preparation independently. Always present the completed, checked result for human review and stop before proceeding beyond that result. Preserve the chronological order below; apply specialized domain or artifact skills within the relevant step.

## 1. Gather the context

- Gather relevant available notes, documents, messages, meeting records, email, project sources, and memory within the authorized scope. Use current source contents for current facts; do not treat remembered information as a substitute for an available authoritative source.
- Identify the specific bounded job and relevant source types. Consult [applications.md](references/applications.md) for the course examples and output shapes when useful. Treat these as alternative applications, not sequential steps or permission to access every system.
- Organize scattered context into known facts, uncertainties, existing decisions, risks, and next steps. Preserve links or references for material claims.
- Identify authoritative sources, source dates, and conflicts. Do not silently resolve material contradictions by guessing.
- Check available context before asking for inputs. Ask together for essential missing information; do not require the user to repeat information already available. Continue independent work that does not depend on missing answers.
- If a required source is unavailable, explain the precise gap and request it; pause dependent work. Never claim access or source review that did not occur.

## 2. Define the goal

- State the concrete result, intended audience, specific task scope, and observable completion criteria, using the user's instructions and available context.
- Keep each execution focused on one clearly bounded job. Distinguish the desired outcome from evidence that it will occur.
- Identify the trigger or reporting period when relevant. Do not create a recurring schedule merely because a task is repeatable.

## 3. Specify the output and constraints

- Establish the required format, contents, level of detail, template, language, destination, and relevant visual preferences before drafting. Use existing instructions and references first.
- Establish permitted sources, tools, actions, exclusions, dependencies, and stop conditions. Connected tools do not grant unlimited authority.
- Separate preparation from actions taken on the completed result. Prepare drafts or previews for approval before sending, sharing, publishing, scheduling, deploying, or taking a subsequent action based on the result.

## 4. Execute independently and generate a draft

- Gather, organize, and draft in that order. Carry out the authorized preparation through completion rather than stopping at a plan.
- Produce the specified deliverable, keeping facts, proposals, uncertainties, decisions needed, risks, and next steps distinguishable where relevant.
- Do not invent owners, dates, commitments, decisions, results, metrics, causal explanations, or approvals. Mark unconfirmed fields as unconfirmed. Label suggested actions as proposals.
- Use only relevant approved sources; preserve underlying facts when changing wording or design.

## 5. Review carefully

Apply the responsible workflow checklist in this order after each creation or update:

1. Verify that the right sources were used.
2. Identify anything missing, uncertain, or unsupported.
3. Check that no owners, dates, decisions, or commitments were invented.
4. Confirm that improved readability or design preserved the underlying facts.
5. Identify approval needed before sending, sharing, scheduling, publishing, or proceeding.
6. Verify that plugins and connected sources stayed within the intended context and permissions.
7. If repetition is intended, assess whether the workflow is stable enough to reuse or schedule.

Then check output quality:

- **Useful:** Check that the result advances the stated goal.
- **Concrete:** Check that findings, deliverables, and actions are specific and supported; label proposals.
- **Easy to review:** Make results, changes, uncertainties, and approval decisions easy to locate.
- **Clear output:** Match the required structure and make the next step explicit.
- **Scanability:** Use clear headings, readable formatting, and suitable information hierarchy.
- **Summary:** Make the summary clear and action-oriented; identify decisions or help needed where relevant.
- **Factual preservation:** Trace important claims to sources; verify calculations and flag conflicts.
- **Visual fit:** When design applies, inspect the rendered result and check color scheme, readability, and supplied preferences. Do not claim the user likes a design before review.

## 6. Improve the instructions and revise the result

- Correct discovered issues independently within the authorized scope. Improve task instructions where necessary without changing the user's goal or relaxing constraints.
- Repeat relevant review checks after revisions until the deliverable passes or an unresolved blocker is clearly disclosed.
- Preserve useful corrections for the current workflow; obtain authorization before changing another installed skill or expanding task scope.

## 7. Request human review and wait for explicit approval

- Always present the completed deliverable or preview, a concise account of material checks, unresolved issues, and the exact next action requiring approval.
- Explicitly request human review. Stop until the user approves the specific result and next action. Silence, elapsed time, completion of tests, and previous approval of a different result are not approval.
- Follow requested revisions, repeat the checks, and present the revised result for review. Require renewed approval after substantive changes.
- Apply the same review gate to repeated and scheduled runs. A schedule changes the start time, not the user's authority to approve the result.

## 8. Reuse what works

- After approval, preserve proven steps, templates, source-selection rules, constraints, and review criteria when reuse is requested or authorized.
- Keep one-time facts and fixed dates out of reusable instructions. Retain the method while allowing inputs and reporting periods to change.
- Test reusable workflows with fresh information, including a missing field or meaningful contradiction; verify source handling and the approval stop before claiming reliability.
- Schedule, share, or formalize a Workspace Agent only after successful testing and explicit authorization. Consider ownership and shared governance only when the intended use needs them.

## Examples of good review handoffs

Use these fictional examples as patterns; never import their facts into real work.

**Project brief:** “The draft includes confirmed progress, blockers, decisions needed, and next steps. The tracker and meeting notes disagree about readiness; both are identified with their source dates. No owner is confirmed for training. I checked the facts and formatting. Please review the draft and approve it before I share it.”

**Variance review:** “Actual spending exceeded the budget by $2,000. I verified the calculation against the supplied reports. The sources do not establish the cause, so it is marked unresolved. Please review and approve the report before I distribute it.”
