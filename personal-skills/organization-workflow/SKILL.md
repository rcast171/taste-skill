---
name: organization-workflow
description: Organize complex work through a fixed, reviewable workflow. Use when a task needs a clear goal, structured inputs, ordered steps, a reusable workflow note, role-specific responsibilities, source-grounded checks, output review, or human approval before final use.
---

# Organization Workflow

Use this skill to keep a complex task organized, source-grounded, and in the approved order. Treat the workflow as a controlled sequence. Do not invent missing steps, reorder supplied instructions, or treat an inference as an approved decision.

## Operating rules

- Preserve the order supplied by the user, screenshots, files, or other authoritative sources.
- When screenshots or pasted material may be out of order, inventory them first and ask the user to verify the sequence. Do not infer the sequence.
- Separate what the source explicitly says from interpretation, recommendation, or proposed additions.
- Keep a current workflow note as the shared reference throughout the task.
- Pause at a review point when a decision, source, constraint, or sequence is uncertain or materially affects the result.
- Complete the work independently through the defined review stage, then request human review before the result is used, published, sent, or installed.

## Required workflow

Follow these stages in order:

### 1. Clarify the goal

State one clear sentence that sets direction. Identify the audience, purpose, desired result, and known constraints. Check whether the goal is specific enough to guide the work. If it is not specific, ask only for the missing information needed to proceed.

### 2. Organize inputs

Collect and label the notes, files, screenshots, examples, source material, decisions, and constraints. Confirm that the required information is included. If the user provides a sequence of screenshots or pasted instructions, record the displayed order without changing it and request sequence verification before relying on it.

Use the applicable file workflow:

- **Summarize:** turn long material into a shorter brief.
- **Extract:** pull out decisions, owners, risks, or themes.
- **Compare:** compare two versions, options, or sources.
- **Verify:** check whether a draft is supported by the source.
- **Transform:** turn notes into a checklist, outline, email, or plan.

Use only the operations that fit the task, while preserving this overall stage order.

### 3. Build the workflow goal and step-by-step table

Write the workflow goal as one clear direction-setting sentence. Then create a step-by-step table. For every step, specify:

- the step name and order;
- what ChatGPT helps with;
- what the user provides;
- what must be checked before advancing;
- the expected output or decision;
- the review point, when applicable.

Do not advance a step merely because a likely answer exists. Advance when the required input and check are satisfied.

### 4. Create and maintain the workflow note

Create a compact shared reference that both the user and ChatGPT can refer back to as the workflow develops. Include:

- goal;
- audience;
- output;
- constraints;
- inputs and sources;
- ordered steps;
- ChatGPT capabilities used;
- decisions so far;
- unresolved questions;
- review points;
- final output;
- human approval status.

Update the workflow note when a decision is approved. Keep superseded or uncertain material clearly marked instead of silently replacing it.

### 5. Draft the output

Use the approved goal, inputs, table, workflow note, and role pathway to produce the requested draft or artifact. Keep the output aligned with the stated audience, purpose, format, and constraints. Do not add unsupported facts or new requirements.

### 6. Review and improve

Review the draft against the source, goal, constraints, and stated quality criteria. Check whether:

- the output answers the goal;
- every required input and step is represented;
- the approved order is preserved;
- claims and decisions are supported by the source;
- assumptions are labeled;
- the format is usable for the intended audience;
- risks, dependencies, and unresolved issues are visible;
- the final quality checks are complete.

Revise the draft only from the review findings. Repeat the review when a material change is made.

### 7. Request human review

After independent completion and quality review, present the concrete result for human review. Ask the user to confirm whether it is accurate, complete, and ready for use. Do not publish, send, install, or otherwise finalize the result until the user approves it. Record the approval in the workflow note.

## Reflection requirements

When the task involves building or improving a repeatable workflow, identify the workflow skills strengthened:

- What repeatable process was created?
- What inputs does it need each week or each cycle?
- What steps does ChatGPT help complete?
- What output format is being produced?
- What final quality checks are required before use?

Also identify the human skills still needed to lead:

- Where is human judgment required?
- Where are context or experience required?
- Where could AI miss nuance?
- Where must risk be managed?
- Where must communication be handled with care?

Do not treat this reflection as a substitute for the workflow, source verification, or human approval.

## Role pathway selection

Choose the role pathway closest to the work before applying the role-specific guidance. If more than one pathway fits, state the candidates and ask the user to select one or approve a combined approach. For each selected role, explicitly reflect on what ChatGPT can help structure and compare it with the human expertise required.

### Sales

ChatGPT can turn account notes, CRM updates, and pipeline data into a repeatable forecast review workflow, identify deal risks, and draft next-step summaries. Human expertise remains necessary for relationship judgment, negotiation, stakeholder awareness, prioritization, and commercial instinct.

### Marketing

ChatGPT can turn campaign data, audience insight, and performance updates into a repeatable campaign review workflow, summarize results, and draft recommendations. Human expertise remains necessary for brand judgment, creative direction, audience empathy, strategic positioning, and interpreting weak signals.

### Legal

ChatGPT can turn contracts, risk registers, policy updates, and escalations into a repeatable risk review workflow, summarize issues, and structure recommendations. Human expertise remains necessary for legal judgment, ethical reasoning, escalation decisions, regulatory nuance, and accountability.

### Communications

ChatGPT can turn coverage, sentiment, stakeholder feedback, and upcoming events into a repeatable communications review workflow, and draft briefings and Q&A. Human expertise remains necessary for tone judgment, reputational awareness, stakeholder sensitivity, crisis judgment, and political awareness.

### Data Science

ChatGPT can turn experiments, dashboards, model metrics, and data quality signals into a repeatable insights review workflow, summarize findings, and identify next experiments. Human expertise remains necessary for scientific skepticism, causal reasoning, statistical judgment, prioritization, and translating ambiguity.

### Business Operations

ChatGPT can turn KPI updates, incidents, risks, capacity signals, and dependencies into a repeatable business operations review workflow. Human expertise remains necessary for operational judgment, tradeoff decisions, resource prioritization, cross-functional alignment, and escalation judgment.

### Finance

ChatGPT can turn actuals, forecasts, variance data, and assumptions into a repeatable financial review workflow, and summarize drivers and risks. Human expertise remains necessary for financial judgment, assumption testing, business interpretation, risk evaluation, and accountability.

### Technical Engineering

ChatGPT can turn incident logs, deployment updates, sprint risks, and system health signals into a repeatable engineering review workflow, and summarize blockers, reliability concerns, and release risks. Human expertise remains necessary for engineering judgment, risk prioritization, technical validation, escalation decision-making, and accountability.
