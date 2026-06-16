# First Look: The Intake Gating Playbook
## A One-Pager for T Level Students

---

## Why This Matters

Every software project starts with a request. Most requests are **messy, solution-biased, and don't expose the real problem**. An intake gate forces clarity *before* you start building. It protects users, saves development time, and stops bad projects dead.

---

## The Five Core Principles

### 1. **Consequence First**
Don't ask "Is this important?" Ask **"What breaks if we don't deliver this? Who pays the price?"**

*Example:* A revision app that works = students pass exams. A revision app that crashes = students fail. That's a consequence.

### 2. **Problem Before Solution**
Requests arrive as solutions: *"We need an app… a dashboard… a workflow tool."*

Your job: **Strip away the solution. What's the actual problem?**

*Example:* "We need a workflow tool" → Really? Or do you need to stop people sending emails to the wrong person?

### 3. **Front Line Weighting**
Users under pressure get the priority. 

A small reduction in user burden outweighs a large reduction in admin inconvenience.

*Example:* If a checkout system is confusing and users abandon it, that's a big deal. If an admin tool is slightly clunky, that's not.

### 4. **Burden Placement**
Every feature shifts work somewhere. **Who carries the cost?**

- Cognitive load (thinking)
- Operational cost (time spent using it)
- Integration cost (how messy is setup)
- Maintenance cost (who fixes it when it breaks)

*Example:* Adding a sign-up form seems simple. But if it adds friction, users never make it to the product. Burden lands on the user.

### 5. **Governance with a Spine**
The intake gate is **mandatory**. No bypassing it. Not for urgency. Not for rank.

This keeps decision-making fair and stops political pressure distorting the backlog.

---

## The Two Foundational Questions

Ask these first. They collapse 80% of the ambiguity.

### **1. What do you need to be able to do that you cannot do now?**
This forces the requester into **problem space**, not solution space.

### **2. Who exactly are the users? Not broad groups—personas.**
*Persona = a specific type of person with a specific context and need.*

*Example:* Not "students" — but "A-level biology students sitting exams in May who need to revise 200 topics in 12 weeks."

---

## The Admission Tiers

Every request gets sorted into one of three buckets:

| Tier | What It Means | Examples |
|------|-------------|----------|
| **Tier 1: Accept** | Mission critical, user safety critical, or strategically essential. Delivers real consequence. | A system to prevent student data loss. A tool that stops exam cheating. |
| **Tier 2: Investigate** | Ambiguous. Might be a local optimization disguised as a strategic need. Requires digging. | A dashboard to track revision progress. A notification system for assignment deadlines. |
| **Tier 3: Reject** | Cosmetic, convenience, or misaligned. Adds burden with no consequence reduction. | A "Spotify-style" interface for the library catalogue. A fun colour scheme for the admin panel. |

---

## Fast Kill Criteria: Reject Immediately If...

- **It's the wrong domain.** (Hardware, networking, infrastructure: not your problem.)
- **It adds burden to users.** (Makes their job harder, not easier.)
- **It's cosmetic or convenience-based.** ("Nice to have" is not a consequence.)
- **It's a local optimization.** (Solves one person's problem, breaks others.)
- **It's technically irresponsible.** (Asks for 100GB download over a 2MB connection—obviously broken.)
- **It's a solution with no problem.** (Someone had an idea. They didn't uncover a real need.)

---

## Pattern Recognition: Red Flags

Watch for these phrases. They signal solution bias or hidden complexity:

| Red Flag | What It Really Means |
|----------|-------------------|
| "We need an app…" | Solution bias. Ask: what's the problem? |
| "We just need a simple dashboard…" | Hidden complexity. Dashboards are never simple. |
| "Our area is unique…" | Local optimization. Probably not. |
| "We already have a spreadsheet…" | Process problem, not a software problem. Fix the process first. |
| "It should only take a few weeks…" | Massive scope underestimation. Run. |

---

## The Exercise: Live Decision-Making

In the session, you'll work through a **messy request** and decide:

1. **What's the real problem?** (Strip the solution.)
2. **Who are the users?** (Define personas.)
3. **What breaks if we don't deliver?** (Consequence.)
4. **Where does burden land?** (Operator, requester, or admin?)
5. **Which tier?** (Accept, Investigate, or Reject.)

This is how real intake gates work.

---

## The Big Takeaway

> **An intake gate creates clarity so better decisions get made.**

It's not about saying "no." It's about saying "yes" to the right things and "yes, but with clarity" to everything else.

The students who master this—**translating messy intent into clear decisions**—are the ones who build products that actually work.

