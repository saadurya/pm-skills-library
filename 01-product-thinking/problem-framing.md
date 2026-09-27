# Problem Framing

## What is Problem Framing?

Problem framing is the process of clearly defining **what problem we are trying to solve, who is experiencing it, and why it matters** before jumping into solutions.

A PM should avoid immediately asking:

> "What feature should we build?"

Instead, start with:

> "What problem are we actually trying to solve?"

---

## Why PMs Use Problem Framing

Good problem framing helps a PM:

- Understand the actual user problem
- Separate problems from symptoms
- Avoid jumping to solutions too early
- Align stakeholders around the same problem
- Identify the right users and context
- Determine what evidence is needed
- Choose an appropriate product approach
- Define what success should look like

The goal is not to find the solution immediately.

The goal is to make sure we are solving the **right problem**.

---

## Problem vs Symptom

A common PM mistake is treating a symptom as the problem.

### Example

**Symptom:**

> Checkout conversion dropped by 15%.

This tells us **what changed**, but not necessarily **why**.

Possible underlying problems could include:

- Payment failures
- Increased checkout abandonment
- Slow checkout experience
- Unexpected fees
- Login issues
- Shipping problems
- A broken UI element
- A change in user behaviour

Therefore:

**Metric change ≠ Root problem**

The PM needs to investigate before deciding what to build.

---

## Basic Problem Framing Structure

A useful starting structure is:

> **Who → What problem → Context → Impact → Evidence**

### 1. Who?

Identify the affected user.

Ask:

- Who is experiencing the problem?
- Which user segment?
- New users or existing users?
- Are there different affected segments?

### 2. What problem?

Describe the user's difficulty without prescribing a solution.

Avoid:

> "Users need a better recommendation feature."

Instead:

> "Users struggle to discover products that match their preferences."

### 3. Context

Understand when and where the problem occurs.

Ask:

- When does it happen?
- Where in the user journey?
- How frequently?
- Under what conditions?

### 4. Impact

Understand why the problem matters.

Potential impact:

- User frustration
- Lower conversion
- Lower retention
- Increased support requests
- Revenue impact
- Increased operational cost

### 5. Evidence

Identify what supports the problem statement.

Possible evidence:

- User interviews
- Customer feedback
- Product analytics
- Funnel data
- Support tickets
- Reviews
- Experiments
- Market research

---

## Problem Statement Template

Use this template:

> **[User] struggles to [achieve goal] because [barrier/problem], resulting in [impact].**

### Example

> Beginner gym users struggle to stay consistent with their workouts because planning and navigating workouts can feel overwhelming, resulting in missed workouts and lower consistency.

---

## Problem Framing Questions

Before moving toward a solution, ask:

### User

- Who is experiencing the problem?
- Is this a specific segment?
- How important is this problem to them?

### Problem

- What exactly is the user struggling with?
- Is this the actual problem or a symptom?
- How frequently does it happen?
- How severe is it?

### Context

- When does the problem occur?
- Where in the user journey does it occur?
- What triggers it?

### Current Behaviour

- How do users solve this today?
- What alternatives do they use?
- What are they doing instead of using our product?

### Impact

- What happens if the problem remains unsolved?
- Does it affect users, the business, or both?

### Evidence

- What evidence do we currently have?
- What assumptions are we making?
- What evidence is missing?

---

## Problem Framing vs Solution Framing

### Solution-first thinking

> "We should build an AI chatbot."

This immediately locks the team into a solution.

### Problem-first thinking

> "Users struggle to get quick answers to complex questions while using the product."

Now multiple solutions can be explored:

- Better search
- Improved help centre
- Contextual guidance
- AI assistant
- Human support
- Better product UX

The second approach keeps the solution space open.

---

## Example: Conversion Drop

### Situation

> Checkout conversion dropped by 15%.

### Poor problem framing

> "We need to redesign checkout."

This assumes the solution before understanding the cause.

### Better framing

> "Checkout conversion has declined by 15%, and we need to identify which user segments and checkout stages are contributing to the decline."

### Investigation

A PM could then examine:

```text
Conversion Drop
      ↓
Funnel Analysis
      ↓
Segmentation
      ↓
Identify Drop-off
      ↓
Generate Hypotheses
      ↓
Investigate Evidence
      ↓
Identify Root Cause
      ↓
Decide Solution
