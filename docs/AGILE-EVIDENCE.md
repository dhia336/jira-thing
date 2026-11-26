# BarberPro Manager — Agile Project Evidence

**Jira governance issue:** [SCRUM-19](https://dhianaffeti.atlassian.net/browse/SCRUM-19)  
**Jira project:** [SCRUM](https://dhianaffeti.atlassian.net/jira/software/projects/SCRUM/boards/1)  
**Release:** 1.0.0 — target 27 November 2026  
**Status:** NO-GO until the critical double-booking defect is resolved and verified.

## Project scope

BarberPro Manager is a simulated barbershop-management application. The exercise covers appointment booking, customer profiles, employee schedules, inventory tracking, support incidents, and release governance. This repository contains project-management evidence only; no production application code is required.

## Jira delivery map

- [SCRUM-8](https://dhianaffeti.atlassian.net/browse/SCRUM-8) — Appointments and Customer Management epic
- [SCRUM-9](https://dhianaffeti.atlassian.net/browse/SCRUM-9) — Employees and Inventory Management epic
- [SCRUM-10](https://dhianaffeti.atlassian.net/browse/SCRUM-10) — Appointment booking story
- [SCRUM-11](https://dhianaffeti.atlassian.net/browse/SCRUM-11) — Customer profiles and visit history
- [SCRUM-12](https://dhianaffeti.atlassian.net/browse/SCRUM-12) — Employee daily appointments
- [SCRUM-13](https://dhianaffeti.atlassian.net/browse/SCRUM-13) — Employee working schedules
- [SCRUM-14](https://dhianaffeti.atlassian.net/browse/SCRUM-14) — Inventory tracking
- [SCRUM-15](https://dhianaffeti.atlassian.net/browse/SCRUM-15) — Low-stock notification
- [SCRUM-16](https://dhianaffeti.atlassian.net/browse/SCRUM-16) — Highest-priority double-booking defect
- [SCRUM-19](https://dhianaffeti.atlassian.net/browse/SCRUM-19) — Governance and release-readiness evidence

## Sprint 1

**Goal:** Deliver core appointment and customer workflows, validate scheduling behavior, and record the double-booking defect as the sprint blocker.

The sprint plan uses an assumed capacity of 20 story points, with 18 points committed. The capacity is a planning assumption, not a configured Jira capacity field.

## Release gate

| Gate | Decision |
|---|---|
| Critical double-booking defect fixed | Pending |
| Regression/concurrency verification | Pending |
| Release 1.0.0 | **NO-GO** |

The release must remain unreleased while SCRUM-16 is unresolved. No real customer or employee data is included in this exercise.

## Repository workflow

This change is linked to Jira issue **SCRUM-19**. It is documentation-only and demonstrates the GitHub branch → commit → pull request workflow required by the exercise.
