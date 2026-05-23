# CLAUDE.md

The 6-Day Development Cycle. Sustainable shipping cadence with mandatory rest.

**Core principle**: Rest is sacred. Never 7-day work weeks. Sustainable pace beats heroic sprints. Burnout serves no one.

## The cycle

| Day | Focus | Principle |
|---|---|---|
| **1** | Ideate & Research | Mentalism — clarify intention |
| **2** | Design & Plan | Correspondence — architecture reflects values |
| **3-4** | Build | Vibration — ship and iterate |
| **5** | Test & Polish | Cause-Effect — conscious quality |
| **6** | Launch | Gender — analysis + intuition = completion |
| **Rest** | Integrate, celebrate, prepare | Rhythm — sacred rest |

## Day-by-day

### Day 1 — Ideate & Research

**Focus**: Understanding and intention-setting.

- Define the goal in one sentence
- Identify constraints (time, resources, dependencies)
- Research existing solutions; learn from what's been tried
- Validate the problem is real and the solution is wanted
- End the day with a clear "what" and "why"

**Done when**: you can state the goal + the reason in two sentences a stranger would understand.

### Day 2 — Design & Plan

**Focus**: Architecture that reflects the intention.

- Sketch the system
- Identify key decisions and their tradeoffs
- Plan implementation steps
- Identify what could go wrong and mitigations
- Get feedback on the design before building

**Done when**: a person on your team could pick up the plan and start building.

### Days 3-4 — Build

**Focus**: Ship working software. Iterate.

- Build the smallest version that demonstrates the value
- Test continuously (TDD or test-after, but test)
- Ship early to a staging environment
- Get feedback from real users if possible
- Don't over-engineer; build what's planned, not what you imagine you might need

**Done when**: the core value works end-to-end, even if rough.

### Day 5 — Test & Polish

**Focus**: Conscious quality. Find what's broken before users do.

- Test edge cases methodically
- Fix bugs in priority order (severity × frequency)
- Polish the surface (error messages, loading states, accessibility)
- Document what's needed for the next maintainer
- Performance check: is it fast enough for the use case?

**Done when**: the team would defend shipping it.

### Day 6 — Launch

**Focus**: Ship to production with attention.

- Final deployment
- Monitor for the first hours
- Announce to users / stakeholders
- Capture metrics from the launch
- Address immediate issues; defer non-urgent for next cycle

**Done when**: the work is in production AND someone is watching it AND issues found are categorized.

### Rest — sacred

**Focus**: Integration, recovery, preparation.

- **Don't work**. The cycle requires rest to be productive.
- Reflect on what was built (without analyzing)
- Notice what energized you and what drained you
- Let ideas for the next cycle surface without forcing them
- Return Monday with intention, not catch-up momentum

## When the cycle compresses

Not every project needs 6 days. Adjust the ratios while preserving the structure:

- **3-day cycle**: Day 1 = Ideate + Design, Day 2 = Build + Test, Day 3 = Polish + Launch. Then rest.
- **2-week cycle (10 working days)**: 2 days each for Ideate, Design, Build, Test, Polish/Launch. Then 2 days off.
- **1-hour cycle**: 5 minutes ideate, 5 plan, 30 build, 10 test, 10 launch. Then break.

The pattern scales. The principle — bounded work followed by rest — does not.

## When the cycle expands

Some work needs > 6 days. In that case, run consecutive cycles:

- Cycle 1: deliver phase 1
- Rest 1 day
- Cycle 2: deliver phase 2
- Rest 1 day

Don't stack 14-day work blocks. The accumulated fatigue is real and unrecoverable in a single weekend.

## Anti-patterns

- **The 7-day cycle**: borrowing rest day to ship. Pays back as Q2 collapse.
- **The "next cycle starts immediately"**: skipping rest "just this once." It's never just this once.
- **The "I'll rest when X is done"**: X is never done. Schedule rest first.
- **The "rest day = catch up on chores"**: chores are also work. Real rest is recovery.
- **The "all days are build days"**: ignoring research → architecture mistakes; ignoring test → quality collapse; ignoring polish → users feel the disrespect.

## On rhythm

This isn't a productivity hack. It's a recognition that humans (and codebases, and projects) have phases. Some days research; some days build; some days rest. Forcing constant tempo creates the illusion of progress while corroding the substrate.

The 6-day cycle is one rhythm among many; pick whatever rhythm matches your context. The principle that holds: **rest is part of the work**.

---

**License**: MIT.
