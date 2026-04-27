# AI Evolution Engine

## Goal

Help Driftwind continuously improve its OKRs by generating **context-aware suggestions** based on actual Key Results.

The system should not generate generic insights, but instead:

- understand the intent of each objective
- recognize the type of each KR (financial, activity, qualitative)
- suggest meaningful next steps

---

## Product intent

Traditional OKR tools are static.

This feature makes OKRs:

- dynamic
- evolving
- aligned with how the business actually operates

---

## Core concept

The system analyzes:

- progress of each KR
- type of KR
- objective context

Then suggests:

- next-level KRs (when completed)
- alternative approaches (when stagnating)
- refinements (when unclear or weak)

---

## KR types (important)

The system must distinguish between:

### 1. Financial KRs
Example:
- omsättning
- debiteringsgrad

### 2. Activity-based KRs
Example:
- events per month
- lunchlabb

### 3. Outcome-based KRs
Example:
- impressions
- pipeline discussions

### 4. Binary / milestone KRs
Example:
- “vi har en plan”
- “vi har genomfört X”

---

## Suggestion principles

- suggestions must be specific
- suggestions must feel realistic
- suggestions must match the objective context
- avoid generic “improve this” phrasing

---

## UX principles

- short and actionable
- 1–2 suggestions per KR max
- clearly labeled as “Suggestion”
- never overwhelming

---

## Scope

- logic-based suggestion engine (no external AI)
- UI for displaying suggestions
- triggered by KR state

---

## Out of scope

- real AI integration
- auto-applying suggestions
- complex workflows

---

## Constraints

- must feel instant
- must be understandable by non-technical users
- must reflect Driftwind’s real OKRs