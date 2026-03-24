# Physics Course – Index & Lesson 1 Pages

Create a premium, interactive physics learning website matching the reference IT course design (dark glassmorphism, animated SVGs, AOS scroll animations, quiz section) but adapted for **Physics Year 1 (STEM) – Unit 3: Motion and Force**.

## Scope

**Lesson 1 content from [content.md](file:///d:/work/projects/physics1th/content.md)** includes:
- Course Introduction (competencies table, skills overview)
- **Lesson 1: Newton's Laws of Motion** covering:
  - Introduction to why objects accelerate
  - The concept of Force (F) – definition, unit, measuring instrument
  - Newton's First Law – statement, mathematical formula (ΣF=0), examples (book on table)
  - Friction & distance relationship (3 cases)
  - Inertia – definition, daily examples (car braking, passengers rushing)
  - Notes on stopping objects (mass & speed dependence)
  - Linear Momentum (P_L = mv)
  - Mass vs Weight comparison table (F_g = mg)
  - Newton's Third Law – daily observations (kicking ball, rocket, car wheels), statement, mathematical formula (F_A on B = -F_B on A), notes on why action-reaction aren't equilibrium
  - Exercise (elephant & girl on roller skates)

> [!IMPORTANT]
> ALL content will be included verbatim – nothing summarized or skipped. Every definition, example, formula, exercise, and note from content.md Lesson 1.

## Proposed Changes

### Course Portal

#### [NEW] [index.html](file:///d:/work/projects/physics1th/index.html)

Physics course portal page matching the reference [index.html](file:///d:/work/projects/physics1th/reference/index.html) design:
- Dark theme with gradient background, glassmorphism cards
- Header: Physics logo, "Physics – Year 1 (STEM)" title
- Lecture grid cards for all 10+ lessons across Unit 3 & Unit 4
- Each card links to its lecture page (only lect01.html will be functional)
- "Coming Soon" badge on lectures not yet built
- Font Awesome icons, Google Fonts (Inter + Cairo)
- Responsive design

---

### Lecture 1 Page

#### [NEW] [lect01.html](file:///d:/work/projects/physics1th/lect01.html)

Single-page interactive lecture covering the Introduction + Lesson 1 content. Structure:

1. **Hero Section** – "Newton's Laws of Motion" title with animated SVG showing force vectors
2. **Introduction Section** – Why objects accelerate, linking to previous chapter concepts
3. **Force Concept Section** – Definition of force with animated SVG (object being pushed), unit (Newton), spring balance
4. **Newton's First Law Section** – Statement, rolling ball animation (SVG showing ball slowing due to friction vs continuing without), ΣF=0 formula, book-on-table example with weight/normal force SVG
5. **Friction & Distance Section** – Interactive SVG showing 3 cases (high friction→short, low friction→long, no friction→infinite)
6. **Inertia Section** – Definition, animated car-braking SVG, passenger rushing examples, mass/speed notes
7. **Linear Momentum Section** – P_L = mv formula, visual SVG
8. **Mass vs Weight Section** – Comparison table (glassmorphism styled), F_g = mg formula, animated weight/mass scale SVG
9. **Newton's Third Law Section** – Action-reaction pairs with animated SVGs:
   - Foot kicking ball with opposite force arrows
   - Rocket launching with gas/thrust arrows
   - Car wheels gripping road
   - Statement + formula (F_A on B = -F_B on A)
   - Notes on why action-reaction ≠ equilibrium
10. **Exercise Section** – Elephant & girl problem with interactive reveal
11. **Quiz Section** – 10+ questions covering all concepts

**Technical Details:**
- Standalone HTML with inline CSS + JS (same pattern as reference)
- Tailwind CSS via CDN + custom styles
- AOS scroll animations
- Font Awesome icons
- Google Fonts (Inter, Cairo)
- KaTeX for math formulas
- Custom animated SVGs for every physics concept
- Glassmorphism card design
- Responsive layout

## Verification Plan

### Manual Verification
1. Open [index.html](file:///d:/work/projects/physics1th/reference/index.html) in browser – verify all lecture cards render, links work, responsive layout
2. Open [lect01.html](file:///d:/work/projects/physics1th/reference/lect01.html) in browser – verify:
   - All content from content.md Lesson 1 is present (no missing text)
   - All SVG animations play correctly
   - Math formulas render via KaTeX
   - Quiz section works (answer checking, show/hide)
   - Responsive on mobile viewport
   - All scroll animations trigger
