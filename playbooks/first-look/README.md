# First Look Playbook

A lightweight, high‑judgement system for rapidly assessing incoming product requests before they enter the development backlog. The First Look process acts as a **strategic filter** to the software organisation - protecting development and engineering capacity, reducing noise, and ensuring only high‑value, well‑framed work progresses.

This playbook captures the **questions, heuristics, and decision patterns** used to run First Looks in minutes to hours, not days.

---

## Purpose

First Look exists to:

- Identify whether a request represents a **real user problem**  
- Determine if it is **valuable**, **feasible**, and **sequenced appropriately**  
- Prevent engineering from being pulled into **low‑value**, **politically driven**, or **premature** work  
- Provide a **clear, teachable decision pathway** for PMs operating at the front door / Dev Backlog boundary 

The output is always one of four outcomes: **Admit**, **Redirect**, **Reject**, or **Hold**.

---

## What First Look Is (and Isn’t)

**It is:**

- A rapid, narrative‑first triage  
- A judgement‑driven decision layer  
- A mechanism for organisational clarity  
- A way to scale product sense across teams  

**It is not:**

- Backlog refinement  
- A substitute for discovery  
- A stakeholder‑appeasement function  
- A bureaucratic approval gate

---

## Process Overview

1. **Intake**  
   A short, structured brief capturing the problem, user, evidence, constraints, and desired outcome.

2. **Assessment**  
   Apply the First Look rubric:  
   - Real user problem  
   - Value magnitude  
   - Feasibility constraints  
   - Sequencing fit  
   - Systemic risk indicators  

3. **Decision**  
   Choose the appropriate route:  
   - **Admit** → create a scoped spike or backlog entry  
   - **Redirect** → ops, UX, analytics, BAU, or another pillar  
   - **Reject** → record rationale  
   - **Hold** → insufficient clarity; request more evidence  

4. **Record**  
   Log the decision, rationale, and next steps.

---

## Evidence Thresholds

First Look decisions rely on **lightweight evidence**, not full discovery. Typical signals include:

- User pain with operational impact  
- Data showing frequency or severity  
- System constraints or architectural implications  
- Risk exposure (safety, compliance, security)  

Anecdotes are accepted as starting points, but not as justification for admission.

---

## Common Patterns & Anti‑Patterns

**Patterns that often indicate good work:**

- Clear user outcome  
- Evidence of repeated friction  
- Alignment with current strategic bets  
- Obvious sequencing leverage  

**Anti‑patterns that signal rejection or redirection:**

- “Can you just…” solution requests  
- Rank‑driven asks without user impact  
- Local optimisations masquerading as product work  
- Workarounds for deeper system issues  

---

## Folder Structure

```
/playbooks
   /first-look
      README.md
      /examples
      /templates
      /variants
```

- **examples/** - worked examples of real First Look decisions  
- **templates/** - intake forms, decision logs, routing checklists  
- **variants/** - adaptations for different teams or contexts  

---

## Status

This playbook is **early stage and actively evolving** as patterns emerge across teams and as the First Look function matures.

---

## Feedback

Suggestions, questions, and improvements are welcome. This playbook is a living document and will continue to evolve as the product organisation grows.
