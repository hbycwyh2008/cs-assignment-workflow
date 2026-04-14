### Reflection examples (after you finish)

[← Full guide: CS_GITHUB_PLANNING_GUIDE.md](CS_GITHUB_PLANNING_GUIDE.md)

Use these when the assignment asks for a written reflection (for example `reflection.md` or LMS prompts). The samples match the **portfolio** and **max/min/average** task ideas from the main guide, but the details are **illustrative**—students should substitute their own experience.

---

#### Strong pattern A — CS1 / web (portfolio-style task)

```markdown
# Reflection

## What changed compared to my plan
In `planning.md` I said I would finish most CSS before starting the contact form. In practice, I built the form HTML on Day 4 earlier than planned because I wanted to see the full page structure first. I also spent extra time on the Projects section grid; I did not expect the cards to wrap awkwardly until I had real content in `index.html`.

## What was difficult
The contact form was harder than I expected. Labels and inputs did not line up until I adjusted the CSS for the form container and added consistent spacing. On small screens, the footer felt too tall next to the form, so I changed padding in `styles.css` and tested with the browser resize tools.

## What I learned
I learned that it helps to build a simple HTML skeleton for every required section early, even if the styling is ugly at first. I also learned to test layout changes at two widths (wide and narrow) so I do not fix one view and break the other.
```

**Why this reads as strong**

- Names real artifacts (`planning.md`, `index.html`, `styles.css`) and concrete problems.
- Explains a genuine plan change and how work was reordered.
- Learning is tied to this assignment, not generic praise.

---

#### Strong pattern B — CS2 / programming (max / min / average style task)

```markdown
# Reflection

## What changed compared to my plan
My plan said I would calculate the average inside the same loop as min and max. I kept that approach, but I almost divided by the wrong value until I reread the instructions. I also added a separate commit for the single-number case after my first tests failed.

## What was difficult
Initializing `min` and `max` was confusing at first. I started both at zero, which broke the case where every number is negative. I fixed it by setting both to the first list element before the loop. Testing edge cases took longer than I expected because I had to think about empty input separately from a one-item list.

## What I learned
I learned that “obvious” starting values for variables are not always correct; the first real data point is often the safest initializer for min/max problems. I also learned to write down two or three test cases before I debug, instead of only testing the happy path.
```

**Why this fits CS2**

- Connects to logic (initialization, division, edge cases) and testing habits.
- Shows specific mistakes and fixes, not only success.

---

#### Weak pattern — what *not* to submit

```markdown
# Reflection

This project was pretty hard. I learned a lot about coding and HTML. Next time I will start earlier and manage my time better. Overall I think it went okay.
```

**Why this is weak**

- No project-specific detail (no files, features, bugs, or comparison to the plan).
- “Learned a lot” does not name what was learned.
- Time-management advice could apply to any course; it does not show thinking about this task.
