### Middle process: commit history examples

[← Full guide: CS_GITHUB_PLANNING_GUIDE.md](CS_GITHUB_PLANNING_GUIDE.md)

These logs are **illustrative** (fake dates). They show the *shape* of good process: **planning first**, then **small steps** with **clear messages** spread across the days you work.

---

#### Strong pattern A — CS1 / web (portfolio-style task)

```text
Apr 10  Fix contact form layout on narrow screens; adjust footer spacing
Apr 9   Add contact form fields, labels, and basic styling
Apr 8   Style Projects section: grid layout and card spacing
Apr 7   Add global CSS: colors, fonts, nav layout, section spacing
Apr 6   Fill About + Projects content; link nav items to section ids
Apr 5   Create index.html skeleton: header, nav, sections, footer
Apr 4   Add planning.md with task breakdown and time plan
```

**Why this reads as strong process**

- `planning.md` appears **before** the main HTML/CSS build.
- Each message names a **concrete** chunk of work (not “update”).
- History **spreads across days**, matching steady progress instead of one dump at the deadline.

---

#### Strong pattern B — CS2 / programming (max / min / average style task)

```text
Apr 10  Clarify output format; handle empty input safely
Apr 9   Add checks for repeated values and single-number list
Apr 8   Compute average using correct list length; fix rounding display
Apr 7   Loop: update min, max, and running total
Apr 6   Read input into a list; scaffold main() and printing
Apr 5   Add planning.md with pseudocode and variable plan
```

**Why this fits CS2**

- Planning lands **before** the core loop logic.
- Testing and edge cases show up as **their own** commits, not mixed into one “finished program” upload.

---

#### Strong pattern C — CS2 / VEX Robotics (autonomous + driver testing)

```text
Nov 12  Autonomous: slow turn speed; stop overshoot on 90° target
Nov 11  Combine forward → turn → brake in autonomous(); add timeouts
Nov 10  Autonomous turn routine using inertial heading error
Nov 9   Encoder-based forward distance move (inches → motor units)
Nov 8   Driver control: arcade drive; confirm motor directions
Nov 7   Add planning.md (routine steps, sensor plan, field test plan)
```

**Why this fits VEX**

- `planning.md` appears before the main autonomous stack.
- Commits follow **subsystem + tuning** work (driver → forward → turn → integration), which matches real robot iteration.

---

#### Weak pattern — what *not* to do

**Single bulk upload**

```text
Apr 10  final project files
```

**Vague messages, same-day burst**

```text
Apr 10  done
Apr 10  updates
Apr 10  more changes
```

**Why this is weak**

- No readable trail of how the work unfolded.
- Messages do not say **what** changed.
- Everything on **one day** often means the history does not reflect real incremental work.
