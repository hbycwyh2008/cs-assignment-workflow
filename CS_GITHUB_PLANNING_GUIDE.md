# CS1 / CS2: GitHub Assignment & `planning.md` Guide (Instructor + Student)

This document combines **course policy**, a **student one-pager**, a **grading rubric**, and **concrete examples** so assignments stay consistent across CS1 (web) and CS2 (programming).

**Related files (same folder):** [planning_web.md](planning_web.md) · [planning_codes.md](planning_codes.md) · [planing_rubrics.md](planing_rubrics.md)

**Jump to sections:** [Part A — Policy](#part-a) · [Part B — Student one-pager](#part-b) · [Part C — Rubric](#part-c) · [Part D — Web example](#part-d) · [Part E — Code example](#part-e) · [Part F — Weak example](#part-f) · [Part G — LMS](#part-g) · [File map](#file-map)

---

<h2 id="part-a">Part A — GitHub assignment policy (course-level)</h2>

**Purpose.** Strong computer science work does not begin with random coding. It begins with clear planning, visible progress, and honest reflection. Your GitHub repository is the **process record** for that work.

**What students maintain in the repo**

| Artifact | Role |
|----------|------|
| `planning.md` | **Start:** shows how they understood the task before building |
| Commits | **Progress:** small, meaningful steps over time |
| Final code / site | **Result:** working submission |
| Reflection (where assigned) | **Close:** what changed, what was hard, what they learned |

**Expectations**

- `planning.md` must exist **before** substantial implementation work begins (same repo, early commit).
- Commits should be **frequent enough** to show real progress (not one giant upload at the deadline).
- Planning should be **specific**: task, breakdown, time, risks, first step — not vague intentions.

---

<h2 id="part-b">Part B — Student one-pager: what <code>planning.md</code> is for</h2>

Each CS task must include a **`planning.md`** file in the GitHub repository.

Your `planning.md` is **not** just a short note. It should clearly show:

- **What the task is** (restated in your own words)
- **How you break the problem into smaller parts**
- **How you plan your time**
- **What challenges you expect**
- **What you will do first**

This file is part of your grade because planning is part of professional CS practice.

### Writing standard: specific beats vague

A strong `planning.md` should be **specific**. It should **not** rely only on phrases like:

- “I will do the project”
- “I will code first”
- “I will try my best”

Instead, it should clearly explain:

- What the task requires
- What smaller steps you will complete
- When you will complete them
- What might be difficult
- What you will do first

### What to paste in the assignment instructions

Before you begin the main build, you must create a **`planning.md`** file in your GitHub repository.

This file should show:

- How you understand the task
- How you break it down
- How you plan your time
- What you will do first

This is graded work. A good plan is **specific**, **realistic**, and **useful**.

---

<h2 id="part-c">Part C — <code>planning.md</code> rubric (4 points)</h2>

Standalone copy (rubric only): [planing_rubrics.md](planing_rubrics.md)

| Score | Level | Criteria |
|-------|--------|----------|
| **4** | Strong | Clearly explains the task; breaks the task into useful smaller parts; includes a realistic time plan; identifies possible challenges; states a clear first step |
| **3** | Satisfactory | Explains the task; includes some breakdown and time planning; may be missing detail in one area |
| **2** | Weak | Planning is too general; task breakdown is unclear; time plan is incomplete or unrealistic |
| **1** | Very weak | Planning is vague; little or no real problem breakdown; no meaningful time planning |

---

<h2 id="part-d">Part D — Example 1 (CS1 / web): strong <code>planning.md</code></h2>

Standalone copy (example only): [planning_web.md](planning_web.md)

**Assume the assignment:** Build a personal portfolio webpage with a homepage, an about section, a projects section, and a contact form.

### Why this example is “strong”

- States the **actual task** and deliverables  
- **Decomposes** work into ordered steps with sub-bullets  
- Uses a **day-by-day** time plan  
- Names **concrete** risks (layout, nav, form, time management)  
- **First step** is actionable (sketch structure → HTML before CSS)

```markdown
# Planning.md

## Task
I need to build a personal portfolio webpage. The website should include:
- a homepage
- an about section
- a projects section
- a contact form

The goal is to create a clear and organized website that works correctly and looks clean.

## Problem Breakdown
I will break this task into smaller parts:

1. Plan the structure of the webpage
   - decide the sections
   - decide the order of the content

2. Build the basic HTML structure
   - create header
   - create navigation
   - create each section

3. Add CSS styling
   - set colors
   - choose fonts
   - improve layout
   - make spacing cleaner

4. Build the contact form
   - add input fields
   - add submit button

5. Test and improve
   - check if links work
   - check if layout looks correct
   - fix any errors

## Time Plan
Day 1:
- plan the page structure
- create the basic HTML for all sections

Day 2:
- add navigation and improve content structure
- begin CSS styling

Day 3:
- continue CSS styling
- make the page cleaner and easier to read

Day 4:
- build the contact form
- test buttons and layout

Day 5:
- fix problems
- improve small details
- submit final version

## Possible Challenges
- making the layout look clean
- keeping the navigation organized
- making sure the contact form is structured correctly
- managing time so I do not leave all styling to the last minute

## First Step
My first step is to sketch the page structure and then build the basic HTML sections before I focus on styling.
```

---

<h2 id="part-e">Part E — Example 2 (CS2 / programming): strong <code>planning.md</code></h2>

Standalone copy (example only): [planning_codes.md](planning_codes.md)

**Assume the assignment:** Write a program that reads a list of numbers and returns the largest number, the smallest number, and the average.

### Why this fits CS2

It practices **input/output thinking**, **variable planning**, **algorithm breakdown**, and **test-case awareness**.

```markdown
# Planning.md

## Task
I need to write a program that reads a list of numbers and outputs:
- the largest number
- the smallest number
- the average

The program should work correctly for a normal list of integers.

## Problem Breakdown
I will break the task into these parts:

1. Understand the input and output
   - input: a list of numbers
   - output: max, min, average

2. Decide how to solve the problem
   - use variables to store current max and min
   - use a running total to calculate average
   - divide total by the number of items

3. Write the basic program structure
   - read the numbers
   - loop through the list
   - update max and min
   - calculate total
   - print results

4. Test the program
   - test with positive numbers
   - test with repeated numbers
   - test with one number

5. Fix errors and improve code
   - check variable names
   - check logic
   - make output clear

## Time Plan
Day 1:
- understand the problem
- write pseudocode
- decide the main variables

Day 2:
- write the loop
- calculate max, min, and total

Day 3:
- calculate average
- print the results
- fix syntax errors

Day 4:
- test with different inputs
- fix logic mistakes

Day 5:
- clean up the code
- write reflection
- submit final version

## Possible Challenges
- making sure max and min start correctly
- remembering to divide by the correct length
- testing edge cases like a list with only one number

## First Step
My first step is to write pseudocode for how the loop will update max, min, and total.
```

---

<h2 id="part-f">Part F — Weak example: what <em>not</em> to submit</h2>

```markdown
# Planning

I will make the project first.
Then I will do the code.
After that I will finish the design.
I think it will be hard.
I will try my best.
```

### Why this fails the rubric

- No **concrete** description of the assignment requirements  
- No **real** decomposition (only generic phases)  
- No **time plan**  
- No **specific** difficulties  
- “Try my best” adds **no** actionable information  

---

<h2 id="part-g">Part G — Optional LMS blocks (if your platform uses custom callouts)</h2>

If your course site supports tagged callouts (e.g. `:::writing{...}`), you can wrap **Part B** and **Part C** excerpts in those components. The **substance** is already given above in plain Markdown.

---

<h2 id="file-map">File map in this folder</h2>

| File | Contents |
|------|----------|
| [CS_GITHUB_PLANNING_GUIDE.md](CS_GITHUB_PLANNING_GUIDE.md) | **This file:** unified policy + student guide + rubric + examples |
| [planning_web.md](planning_web.md) | CS1 web example only |
| [planning_codes.md](planning_codes.md) | CS2 programming example only |
| [planing_rubrics.md](planing_rubrics.md) | Rubric only (same as Part C) |
