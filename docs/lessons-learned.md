# Lessons Learned

This document summarizes key lessons learned during the
implementation and real-world use of Project Server (PWA)
in an enterprise environment.

The focus is on system thinking, governance, and practical
insights gained over time.

---

## 1. Percentage-Based Progress Can Be Misleading
Early on, it became clear that percentage completion alone
does not accurately reflect project health.

Projects with high % complete values could still face
significant schedule risks.

This led to a stronger reliance on:
- Late vs due task analysis
- Milestone-based tracking
- Timeline-oriented views

---

## 2. Governance Is More Important Than Feature Depth
Project Server provides many advanced features, but their
effectiveness depends on consistent usage rules.

Clear governance around:
- Where tasks can be edited
- Which views are authoritative
- How progress is reported

proved more valuable than adding new functionality.

---

## 3. Simpler Views Improve Adoption and Data Quality
Initial designs exposed too many fields and options to users,
which increased confusion and reduced data accuracy.

Simplifying views and focusing on a small set of meaningful
indicators significantly improved user adoption and reporting
consistency.

---

## 4. Reports Should Support Decisions, Not Just Visibility
Some early reports attempted to capture too much detail and
were rarely used.

The most effective reports were those that directly supported:
- Escalation decisions
- Management reviews
- Portfolio-level prioritization

This reinforced the importance of designing reports around
decision-making needs.

---

## 5. Portfolio Perspective Changes How Progress Is Interpreted
Viewing projects in isolation can hide systemic issues.

Portfolio-level comparison helped identify:
- Repeated delay patterns
- Resource concentration risks
- Projects requiring early intervention

This shifted the focus from individual performance to overall
portfolio health.

---

## 6. Data Sensitivity Must Be Considered From the Start
Working with project, cost, and resource data highlighted
the importance of security and confidentiality.

This experience emphasized:
- Role-based visibility
- Careful handling of shared artifacts
- Sanitization of publicly shared materials

These principles are reflected in how this repository has been
prepared for public sharing.
