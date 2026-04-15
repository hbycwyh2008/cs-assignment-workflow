# Plan — APCSA wrong-question collection (MCQ + FRQ)

[Course artifact: keep `mcq.md`, `frq.md`, and this plan in the same folder.]

## Task

Build and maintain a **single place** in this repository for APCSA exam prep mistakes:

- **`mcq.md`** — wrong answers from **Barron** and *5 Steps* **full-length MCQ** practice tests, plus **past released exams** (multiple choice only).
- **`frq.md`** — missed points and rubric alignment for **Barron** FRQ practice (e.g. Barron Online sets), *5 Steps* FRQs, and **College Board past FRQs**.

Each wrong item becomes **one row** in the correct file and section (Barron / 5 Steps / Past papers).

## Problem breakdown

1. **After each practice session** — While the test is fresh, add rows for questions you missed or almost missed (not only “random guesses”).
2. **MCQ** — Use `mcq.md`: record *Source*, what the item tested, wrong vs correct answer, why you erred, rule/reminder.
3. **FRQ** — Use `frq.md`: record *Source*, skills tested, what the rubric expected, where points were lost, fix and reminder.
4. **Past papers** — When you use official materials, use the **Past papers** tables and put **year + form + question** in *Source*.
5. **Git** — Commit in **small batches** (e.g. after each test or each study block) so history shows steady work, not one upload at the deadline.

## Time plan

| Session focus | Goal |
|---------------|------|
| Early | Finish this `plan.md`; set up (or confirm) column headers in `mcq.md` / `frq.md`. |
| Ongoing | After each full MCQ test → add rows to the right section of `mcq.md`. |
| Ongoing | After each FRQ set or timed FRQ → add rows to `frq.md`. |
| Before exam week | Skim **Reminder** columns only; re-do the highest-value missed topics. |

Adjust dates to your real schedule; the habit matters more than the exact calendar.

## Possible challenges

- Mixing **FRQ rows into `mcq.md`** by mistake — keep FRQ code/tracing write-ups in `frq.md` only.
- **Wide tables** in the editor — keep each cell short; use one line for code when possible.
- **Forgetting source details** — note test name and question number the same day you log the mistake.

## First step

Complete one **real** row in `frq.md` under **Barron** (or your next FRQ source) and one **real** row in `mcq.md` under **Barron** after your next full MCQ test, then commit with a clear message.
