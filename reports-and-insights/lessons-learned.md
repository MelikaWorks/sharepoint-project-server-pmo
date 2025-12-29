# Lessons Learned

This document summarizes key lessons learned during the
implementation and operation of the Project Server (PWA)
environment in a real-world enterprise setting.

The focus is on practical insights rather than technical
limitations.

---

## 1. Progress Percentage Alone Is Not Enough
One of the earliest observations was that percentage-based
progress can be misleading when viewed in isolation.

A project might appear healthy in terms of % complete while
still carrying significant schedule risks.

This led to a stronger emphasis on:
- Late vs due task analysis
- Milestone-based tracking
- Timeline-driven interpretation of progress

---

## 2. Governance Matters More Than Tool Features
The effectiveness of Project Server depended less on its
advanced features and more on how consistently it was used.

Clear rules around:
- Where tasks could be edited
- How progress was reported
- Which views were considered authoritative

proved to be more important than adding new functionality.

---

## 3. Simplicity Drives Adoption
Initial designs attempted to expose too many fields and views
to end users.

Over time, simplifying views and focusing on a small set of
meaningful indicators significantly improved adoption and
data quality.

---

## 4. Reporting Must Serve Decisions, Not Data Collection
Reports that attempted to capture every possible metric
quickly became unused.

The most effective reports were those that directly supported:
- Escalation decisions
- Prioritization discussions
- Management reviews

This reinforced the idea that reporting should be designed
around decisions, not raw data.

---

## 5. Early Alignment With Stakeholders Is Critical
Differences in expectations between project teams, PMO, and
management surfaced early in the implementation.

Regular feedback cycles and iterative refinement of views
helped align the system with real operational needs.

---

## 6. Security and Data Sensitivity Cannot Be an Afterthought
From the beginning, it was clear that project and cost data
required careful handling.

This experience reinforced the importance of:
- Sanitizing shared artifacts
- Role-based visibility
- Avoiding unnecessary exposure of sensitive information

These principles are reflected in how this repository has been
prepared for public sharing.
