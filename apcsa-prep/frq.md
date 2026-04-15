# APCSA — FRQ

One table per section. Add a row for each part you miss or want to review.

## Barron

| Source | Topic | My wrong code snippet | Correct version | Error type | Why I got it wrong | Correct pattern / rule | Reminder |
|--------|-------|----------------------|-----------------|------------|-------------------|------------------------|----------|
| Barron Online FRQ 3 Q1 | Array traversal | `for (int i = 0; i <= arr.length; i++)` | `for (int i = 0; i < arr.length; i++)` | Boundary error | I used `<= arr.length`, so the loop went one step too far. | When traversing an array, the last valid index is `length - 1`, so the loop condition should usually be `i < arr.length`. | The last index is never `length`. |
| Barron Online FRQ 3 Q2 | Counting with condition | `if (arr[i] > target) count = 1;` | `if (arr[i] > target) count++;` | Logic error | I reset the counter instead of increasing it. | In counting problems, initialize once before the loop, then update with `count++` inside the condition. | Count means accumulate, not restart. |
| Barron Online FRQ 3 Q3 | ArrayList remove | `for (int i = 0; i < list.size(); i++) { if (list.get(i) < 0) list.remove(i); }` | `for (int i = list.size() - 1; i >= 0; i--) { if (list.get(i) < 0) list.remove(i); }` | Traversal/removal error | I removed elements while moving forward, so some elements were skipped after shifting. | When removing from an `ArrayList`, go backward if index shifting can affect later checks. | Remove while going backward. |
| Barron Online FRQ 3 Q4 | String processing | `word.substring(1, word.length() - 1)` (needed full tail, not trimming last char) | `word.substring(1)` | Method misuse | I mixed up the two versions of `substring` and cut off the last character by mistake. | `substring(start)` goes to the end. `substring(start, end)` stops before `end`. | Right endpoint is excluded. |
| Barron Online FRQ 3 Q5 | Return value in method | `System.out.println(total);` | `return total;` | Requirement mismatch | I printed the answer instead of returning it. | If the method header says it returns a value, the final result should be returned, not printed. | Return is not print. |
| | | | | | | | |

## 5 Steps to a 5

| Source | Topic | My wrong code snippet | Correct version | Error type | Why I got it wrong | Correct pattern / rule | Reminder |
|--------|-------|----------------------|-----------------|------------|-------------------|------------------------|----------|
| | | | | | | | |

## Past papers

| Source | Topic | My wrong code snippet | Correct version | Error type | Why I got it wrong | Correct pattern / rule | Reminder |
|--------|-------|----------------------|-----------------|------------|-------------------|------------------------|----------|
| | | | | | | | |
