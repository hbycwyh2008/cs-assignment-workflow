# Planning.md

[← Full guide: CS_GITHUB_PLANNING_GUIDE.md](CS_GITHUB_PLANNING_GUIDE.md) · [VEX workflow notes (Part K)](CS_GITHUB_PLANNING_GUIDE.md#part-k)

## Task
I need to program our VEX V5 robot to run a short **autonomous routine** on the classroom field:

- drive forward a **fixed distance** using drivetrain encoder feedback (or motor rotation counts)
- turn about **90°** using the **Inertial Sensor** (calibrate at the start of autonomous)
- stop cleanly at the end of the routine

The teacher also wants **driver control** set up so we can test the drivetrain manually while we tune autonomous.

The goal is code that is **repeatable on the tile** (not only “works once if you’re lucky”).

## Problem Breakdown
I will break the task into these parts:

1. Clarify hardware + sensors on our bot
   - which motors are left/right drive
   - where the inertial sensor is mounted
   - gear ratio / wheel size (so distance math matches real movement)

2. Plan the autonomous sequence as small steps
   - calibrate inertial and wait until ready
   - drive forward: target distance in inches (convert to motor units)
   - turn: target angle with a simple control loop (or commanded turn routine)
   - brake / hold at end

3. Implement driver control first (simple arcade or tank)
   - map joysticks to drivetrain
   - test that wiring and motor directions are correct

4. Implement autonomous functions one at a time
   - forward distance move
   - turn move
   - combine into `autonomous()` in the right order

5. Test on the field and iterate
   - mark start line with tape; measure error
   - adjust constants (speed, timeouts, turn gain) in small steps
   - log what changed when behavior improves

6. Clean up + document
   - comment the main constants (distance, angle, speeds)
   - make sure the project opens cleanly in VEXcode for grading

## Time Plan
Day 1:
- confirm drivetrain motor ports and inertial sensor in code
- write `planning.md` and commit it
- basic driver control + sanity test (robot moves the right direction)

Day 2:
- autonomous: forward distance function + first on-field tests

Day 3:
- autonomous: turn function + combine forward → turn → stop

Day 4:
- tune constants; fix overshoot / drift issues

Day 5:
- final reliability pass (run routine multiple times)
- reflection (if the assignment requires it)
- submit / push final state to GitHub

## Possible Challenges
- wheel slip makes encoder distance inaccurate on certain tiles
- inertial sensor drift if calibration wait is skipped
- motor directions inverted so “forward” in code goes backward
- tuning turns without overshooting (needs slower speed or better stopping logic)

## First Step
My first step is to verify motor ports and drivetrain direction with **driver control**, then write pseudocode for the autonomous sequence (calibrate → drive → turn → stop) before I tune numbers on the field.
