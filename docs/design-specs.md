# Design specs – OKR Dashboard

## Goal

Create a visually clear, modern, and premium-feeling OKR dashboard.

The UI should be:
- easy to understand at a glance
- visually structured
- clearly better than task-based tools like Asana

---

## Design principles

### 1. Visual clarity over density
- avoid tables and dense layouts
- prefer cards and whitespace

### 2. Hierarchy first
- objective is the focal point
- key results are secondary
- metadata is subtle

### 3. Fast readability
- user should understand progress in < 5 seconds

---

## Layout

### Objective section (hero)

Displays:

- Objective title (large)
- Progress percentage
- Progress bar
- Status label

Example:

Objective: Increase customer satisfaction  
Progress: 72%  
Status: On track  

---

### Key Results (cards)

Each key result is displayed as a card.

Each card contains:

- title
- current value
- target value
- progress bar
- percentage
- status

---

## Visual styling

### Typography

- large titles
- clear numeric emphasis (progress, values)
- avoid small, dense text

---

### Spacing

- use spacing instead of borders
- generous padding inside cards
- consistent vertical rhythm

---

### Cards

- rounded corners (8–12px)
- soft shadows
- subtle background contrast

---

### Colors

Use status-based colors:

- green → on track
- yellow → at risk
- red → off track

Keep colors subtle, not saturated.

---

### Progress bars

- horizontal bars
- smooth edges
- consistent height
- color reflects status

---

## Interaction

- updates should feel instant
- no heavy loading states
- editing should be lightweight

---

## Constraints

- no tables
- no complex layouts
- no unnecessary UI elements
- keep everything mobile-friendly

---

## Overall feel

The dashboard should feel:

- calm
- focused
- modern
- slightly premium

NOT:

- cluttered
- corporate
- overwhelming