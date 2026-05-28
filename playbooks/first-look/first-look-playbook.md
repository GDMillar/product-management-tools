# First Look Playbook

## Playbook Overview

This playbook defines the **First Look** operating model: a lightweight, high‑judgement intake and triage process for software requests entering Data & Navy Application (DNA) as the software delivery pillar of Navy Digital. It captures the principles, boundaries, and decision logic that ensure only strategically aligned, operationally meaningful work enters the development pipeline.

---

### Purpose

The purpose of First Look is to:

- Convert messy intent into clear, decision‑ready narrative
- Protect development capacity by filtering misaligned or low‑value work  
- Prioritise front line impact by weighting operational burden correctly  
- Provide a consistent governance gate for all software requests  
- Enable senior leaders to make fast, high‑quality decisions

This playbook documents *how* that happens. Not through rigid checklists, but through disciplined judgement.

---

### Scope and Audience

This playbook is written for:

- First Look Leads
- Chiefs of Staff
- Heads of DNA and Heads of Development
- Senior PMs, Discovery Leads, and Technical Architects
- Federated development governance leads

It assumes some familiarity with UK Defence context, operational tempo, and the realities of front line burden.

**In scope:** Software requests, capability changes, data‑driven workflows, and digital processes.  
**Out of scope:** Hardware, infrastructure, networking, and platform‑level issues - these are redirected immediately.

---

### Core Principles

These principles underpin every First Look decision.

- **Consequence first**  
  Prioritise by the operational, safety, or strategic consequence of delivery or non‑delivery.

- **Front line weighting**  
  Reduce cognitive load, context switching, and administrative burden on operators under fatigue, stress, and legal responsibility.

- **Translate intent into clarity**  
  The First Look Lead is the bridge between requester language and software delivery language.

- **Governance with a spine**  
  First Look Review is mandatory. Extraordinary sessions are rare and justified only by genuine operational necessity or Head of DNA direction.

- **AI as a judgement amplifier**  
  Use AI to accelerate sense‑making, stress‑test reasoning, and compress narrative. ***Never*** to replace human judgement.

---

### How to Read This Playbook

- **Start with Approach**  
  Understand the mental models, heuristics, and admission thresholds that shape First Look decisions.

- **Move to Execution**  
  See the operational flow, artefacts, and governance boundaries that make the process real.

- **Use Templates**  
  Adopt the standardised artefacts for Jira narratives, EXECSUMs, and "hostile panel" preparation.

- **Review Governance**  
  Understand the panel’s authority, cadence, and decision outcomes.

- **Study Principles in Practice**  
  Learn from real examples that show how judgement is applied under pressure.

---

### Quick Start Checklist

A minimal, high‑signal orientation for anyone running First Look.

- **Confirm domain**  
  If it’s hardware, infra, or networking, redirect immediately.

- **Ask the two foundational questions**  
  - What must users be able to do that they cannot do now?  
  - Who exactly are the users (by persona, not broad group)?

- **Identify the *likely* problem type**  
  Data integration, process automation, or custom software.

- **Prepare the EXECSUM**  
  This should be distilled for brevity, but maintaint the essence of the research - index for consequences of action/inaction.

- **Run a hostile‑panel simulation**  
  Stress‑test assumptions before the real panel.

- **Bring the Jira Narrative**  
  Context, Problem, As Is, To Be, Impact if Not Delivered, Risks, Dependencies, Access at Sea.

---

### What This Playbook Is Not

- **Not a procedural manual**  
  It does not prescribe tool‑level steps or UI walkthroughs.

- **Not a junior PM training guide**  
  It assumes senior level judgement and operational literacy.

- **Not a catch‑all for digital work**  
  It explicitly excludes hardware, infra, and networking.

- **Not a bypass mechanism**  
  It reinforces governance, not shortcuts.

---

### Versioning and Change Control

- Maintain a **changelog** with the DNA Transition Manager for updates to governance, templates, or decision logic.  
- Route contributions through the **Head of DNA** or delegated governance owner.  
- Treat this playbook as a **living document** — updated as patterns emerge and organisational needs evolve.

---

Below is the **full, detailed, senior‑grade Approach section** for your playbook.  
It is written to the same altitude and tone as the Overview: authoritative, operational, and grounded in Defence reality.  
It captures your mental models, heuristics, shortcuts, and decision taxonomy — the *thinking engine* behind First Look.

---

## Approach

The Approach section defines the **judgement framework** that underpins First Look.  
It captures the mental models, heuristics, and decision thresholds that allow a First Look Lead to convert ambiguous, inconsistent, or politically charged requests into clear, consequence‑driven decisions.

This is the intellectual spine of the playbook.

---

### Operating Philosophy

The First Look Lead is not the decider.  
The First Look Lead is the **sense‑maker**.

Your role is to:

- translate requester intent into a problem the software organisation can understand  
- surface operational and strategic consequences  
- identify risks, dependencies, and burden placement  
- prepare the panel to make a high‑quality decision  
- protect development capacity  
- protect front line operators from unnecessary burden  

This is a **judgement role**, not an administrative one.

---

### Mental Models

These are the core mental models that shape every First Look decision.

#### Consequence First  
The primary lens is not “importance” or “urgency”.  
It is **consequence**.

- What happens if we deliver this?  
- What happens if we do not?  
- Who carries the burden?  
- What is the operational, safety, or strategic effect?  

This prevents the backlog from being captured by loud voices or local optimisations.

#### Front Line Weighting  
Front line operators carry:

- cognitive load  
- legal responsibility  
- fatigue  
- environmental stress  
- safety risk  

Rear echelon staff do not.

Therefore:

> A small reduction in front line burden outweighs a large reduction in rear echelon inconvenience.

This is a deliberate weighting, not a moral stance.

#### Problem Before Solution  
Most requests arrive as solutions:

- “We need an app…”  
- “We want a dashboard…”  
- “Can you build a workflow that…”  

Your job is to strip away the solution and expose the **problem**.

#### Burden Placement  
Every request shifts burden somewhere.

You ask:

- Who pays the cognitive cost?  
- Who pays the operational cost?  
- Who pays the integration cost?  
- Who pays the maintenance cost?  

If the burden shifts to the front line, the bar is extremely high.

#### System Integrity  
The First Look process is only credible if:

- nothing bypasses the panel  
- extraordinary sessions are rare  
- decisions are consistent  
- governance is respected  

This protects the organisation from political gravity and “special case” erosion.

---

### Foundational Questions

These two questions collapse 80% of ambiguity:

1. **What do you need to be able to do that you cannot do now?**  
2. **Who exactly are the users? Not groups — personas.**

These force the requester into:

- problem space  
- operational reality  
- user specificity  

They expose assumptions instantly.

---

### Admission Thresholds

Every request is evaluated against a four‑tier threshold model.

#### Tier One  
**Obviously clears threshold. Mission critical, safety critical, or strategically essential.**  
These are accelerated.

Example:  
Assuring safe navigation through mined waterways.

#### Tier Two  
**Clears threshold but low momentum.**  
Valid, aligned, but likely to be overtaken by higher‑tempo work.

Example:  
Push notifications for a BYOD HR app.

#### Tier Three  
**Ambiguous. Might clear threshold. Requires investigation.**  
Often local optimisations disguised as strategic needs.

Example:  
Replicating a centralised MS Dynamics app for a local area.

#### Tier Four  
**Does not meet threshold. Reject.**  
Cosmetic, convenience, or misaligned.

Example:  
Uber‑style bus stop displays on a naval base.

This model keeps the backlog coherent and protects development capacity.

---

### Fast Kill Criteria

These are the immediate reject or redirect signals.

#### Not Our Domain  
If it involves:

- hardware  
- infrastructure  
- networking  

It is not DNA. Redirect immediately.

#### Misaligned Work  
Reject if:

- it adds burden to the front line  
- it is cosmetic or convenience based  
- it is a local optimisation with no organisational value  
- it is technically irresponsible (for example, 100GB over a 2MB per second bearer)  
- it is a solution with no problem  

These are fast, principled decisions.

---

### Heuristics

These heuristics classify the nature of the problem in seconds.

- **Is this a data integration problem?**  
  Likely Foundry.

- **Is this a process automation problem?**  
  Likely Power Platform.

- **Does it need to be accessed outside MODNET, at sea, or internet facing?**  
  Likely custom.

This collapses the solution space quickly and accurately.

---

### Pattern Recognition

With exposure, certain patterns become obvious:

- “We need an app…” → solution bias  
- “Starlink is fast now…” → technical naivety  
- “Our area is unique…” → local optimisation  
- “We just need a simple dashboard…” → hidden complexity  
- “We already have a spreadsheet…” → process problem, not software problem  

These patterns allow you to skip entire branches of analysis.

---

### AI as a Thinking Partner

AI is treated as:

> A very intelligent but contextually naive friend.

You teach it the context.  
It accelerates your thinking.

AI supports:

- question generation  
- transcript summarisation  
- contradiction detection  
- "hostile panel" simulation  
- narrative compression  

It amplifies judgement without replacing it.

---

### Hostile Panel Preparation

Before the real panel, you run adversarial simulations to test:

- assumptions  
- narrative coherence  
- risk framing  
- user need clarity  
- consequence articulation  

This is why you can operate reactively and fluently in the room.

---

### Room Reading

During the panel, you watch for:

- friction  
- hesitation  
- divergence  
- misalignment  
- technical discomfort  
- architectural concern  

You adjust altitude instantly:

- operational detail  
- user nuance  
- strategic alignment  
- technical feasibility  
- risk framing  

You re‑anchor when needed.

---

### Decision Interpretation

The panel outputs one of five decisions:

- Accept to Dev Backlog with Discovery  
- Accept to Dev Backlog without Discovery  
- Refer for Federated Development  
- Refer for Additional Clarity  
- Refer for Withdrawal  

Your job is to execute the decision cleanly and communicate it clearly.

---

### Summary

The Approach section defines the **thinking engine** of First Look:

- consequence first  
- front line weighting  
- problem before solution  
- burden placement  
- governance integrity  
- AI‑assisted sense making  
- principled thresholds  
- fast kill criteria  
- pattern recognition  
- hostile‑panel preparation  

To restate from the begginning of the chapter, this is the intellectual foundation of the entire playbook.

---

## Execution

The Execution section describes how the First Look system actually operates: the cadence, artefacts, governance boundaries, an AI-assisted accelerators that turn judgement into a repeatable, high-quality intake process. It is intentionally non-granular. The goal is to make the system *real* without reducing it to a checklist.

Treat this as the application of the approach.

### 1. Cadence and Flow 

First Look runs on a predictable, lightweight rhythm that preserves tempo without sacrificing rigour.

#### **1. Intake (from the Front Door)**

Requests arrive via the Navy Digital Front Door. As a member of the triage forum, the First Look Lead sees them early, shapes expectations, and prevents misrouted work entering DNA.

#### **2. Interview**

A structured conversation with the requester to uncover:

- the real problem
- the operational context
- the user population (by persona)
- the consequence of inaction
- the hidden assumptions

This is where solution bias is stripped away.

#### **3. Sense‑Making and Artefact Creation**

The raw submission and interview are transformed into:

- a structured Jira Narrative  
- a concise EXECSUM  
- a clear articulation of known risks, dependencies, and burden placement  

This is the conversion of intent into decision‑ready clarity.

#### **4. First Look Review Panel**

A weekly governance forum where:

- the problem is examined  
- the risks are surfaced  
- the technical and operational perspectives converge  
- a formal decision is made  

This is the mandatory decision gate.

#### **5. Outcome Communication**

The requester receives:

- the decision  
- the rationale  
- the next steps  
- the pathway (Discovery, Dev, Federated, Clarification, Withdrawal)  

This closes the loop cleanly and transparently.

---

### 2. Core Artefacts

Execution produces two artefacts that encode the narrative and enable decision‑making.

#### **A. Jira Narrative (Full Context Artefact)**

A structured, canonical description of the problem, including:

- Context  
- Problem  
- As‑Is  
- Statement of User Need  
- Impact if Not Delivered  
- To‑Be  
- Dependencies  
- Risks  
- Complexity Assessment  
- Benefits  
- Security Classification  
- Access at Sea (Y/N)  
- Requester and Contact History  

This is the artefact inherited by Discovery or Development teams.

#### **B. EXECSUM (Decision Artefact)**

A concise, verbal‑ready summary used in the panel:

- consequence‑led  
- risk‑aware  
- aligned to the decision surface  

This is the artefact that enables fast, high‑quality decisions.

---

### 3. AI‑Assisted Acceleration

AI is used as a **judgement amplifier**, not a substitute for expertise.

#### **A. Pre‑Interview Preparation**

AI accelerates:

- foundational question generation  
- clarifying question sets  
- persona probes  
- operational‑context checks  

This ensures the interview is sharp and high‑yield.

#### **B. Capturing the Interview**

When using MS Teams, be sure to turn on the recording and transcription functions - as these artefacts will be significant time savers in the post-interview analysis and write-up. This must be explicitly put to all people on the call to give the opportunity for objections.

#### **C. Post‑Interview Structuring**

AI assists with:

- transcript summarisation  
- contradiction detection  
- assumption surfacing  
- narrative structuring  

This reduces cognitive load and increases consistency.

#### **D. Hostile‑Panel Simulation**

Before the real panel, the First Look Lead should run adversarial simulations with M365 Copilot to test:

- the strength of the narrative  
- the defensibility of assumptions  
- the clarity of the user need  
- the coherence of the recommended pathway  

This can equip the Lead to operate reactively and fluently in the room, having consciously sought to illuminate blindspots in thinking and analysis.

#### **E. Bounded Outputs**

AI is instructed to produce outputs to suit the forum, for example:

- 2‑minute briefs  
- 200‑word summaries  
- 5‑bullet EXECSUMs  

This keeps communication tight and decision‑ready.

---

### 4. Governance Boundaries

Execution is anchored in clear, non‑negotiable governance.

#### **A. Nothing Bypasses First Look Review**

No matter the requester’s rank or urgency, the panel is the mandatory gate. Extraordinary Reviews may be convened out of sequence, but never simply accepted out-of-committee.

#### **B. Extraordinary Sessions Are Rare**

Used only for:

- genuine operational necessity - eg. Urget Capability Requirements (UCR)
- direction from two‑star prioritisation (or above)

This prevents normalising process bypass.

#### **C. Escalation Belongs to the Head of DNA**

The First Look Lead provides subject matter expert (SME) support, but escalation authority sits above them.

#### **D. Decision Outcomes Are Explicit**

The panel selects one of five pathways:

1. Accept to Dev Backlog - Discovery Required  
2. Accept to Dev Backlog - No Discovery Required  
3. Refer for Federated Development (many FedDev candiates are filtered out prior to First Look)
4. Refer for Additional Clarity  
5. Refer for Withdrawal  

Each outcome has a defined next step and communication pattern.

---

### 5. Role of the First Look Lead

The First Look Lead is the **translator and sense‑maker**, not the decider.

Their responsibilities include:

- extracting the real problem from solution‑biased requests  
- surfacing operational and strategic consequences  
- identifying risks, dependencies, and burden placement  
- preparing the panel to make high‑quality decisions  
- maintaining governance integrity  
- protecting development capacity  
- ensuring front line user pain is correctly weighted  
- accelerating sense‑making through AI‑assisted workflows  

In short:

> **The First Look Lead creates clarity so others can make good decisions.**

---

### 6. What This Section Is Not

This chapter deliberately avoids:

- procedural checklists  
- step‑by‑step tooling instructions  
- screenshots  
- personal productivity habits  

The First Look system is a **judgement framework**, not a script.

Competent operators can adapt the “how” to their own style, tools, and context.

---

### 7. What This Section Enables

This Execution chapter makes the system:

- legible  
- repeatable  
- teachable  
- defensible  
- scalable  

Without reducing it to a junior PM's manual.

---

