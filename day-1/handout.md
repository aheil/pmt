# Handout

## Day 1

### Project Management and Scrum

Presentation and handout

Second-year Computer Science

***

## Learning Outcomes

After this day, students can:

* describe projects and project success;
* formulate SMART goals;
* explain the magic triangle and Gantt plans;
* distinguish phases and milestones;
* relate the four Agile Manifesto values to practice;
* name Scrum roles, events, and artifacts;
* explain transparency, inspection, and adaptation in Scrum.

***

## Daily Schedule

| Time        | Topic                                      |
| ----------- | ------------------------------------------ |
| 09:00-10:15 | Project management: fundamentals and goals |
| 10:30-11:30 | Magic triangle and Gantt exercise          |
| 11:45-12:30 | Agile values and principles                |
| 13:30-15:00 | Scrum theory, roles, events, and artifacts |
| 15:15-16:15 | Scrum map and value discussion             |

These times are suggestions and can be adapted to the available teaching schedule.

***

## What Is a Project?

A project is a temporary, unique endeavor.

* defined or testable goal;
* limited time, cost, and resources;
* unique organizational arrangement;
* separate from routine operations;
* solution path is often initially unknown;
* greater uncertainty than a routine task.

DIN 69901 and the PMBOK describe projects as temporary efforts to create a unique product or result.

***

## When Is a Project Appropriate?

### Suitable

* new products and product development;
* innovations;
* new sales channels;
* work involving several disciplines;
* unique, novel undertakings.

### Less suitable

* assembly-line or routine work;
* service operations;
* individual tasks;
* pure basic research.

***

## Project Success

A project may:

* deliver the agreed functions;
* finish on time;
* stay within budget;
* and still create no value.

**Project success = goal achievement and value**

Project leadership must therefore consider the result, quality, time, cost, and impact on customers and users.

***

## Exercise: Project Reality

**Goal:** identify a project and distinguish goal achievement from value.

**Process**

1. Form groups of 4-5.
2. Choose one local news project, university project, or known software launch.
3. Assign the following roles. The fifth person, if present, serves as facilitator and quality checker.
   * **Source Finder:** locate one reliable primary or original source and one secondary source if available; record title, date, URL, and key verified facts; separate published evidence from opinions or later claims.
   * **Goal and Stakeholder Reviewer:** restate the project's original goal from evidence; identify the sponsor, customer, users, and other relevant stakeholders; explain who would judge goal achievement.
   * **Constraint Reviewer:** identify scope/quality expectations, deadline, budget or resources, dependencies, and unique project conditions; list at least one known constraint and one known risk.
   * **Success Reviewer:** compare available evidence against scope/quality, time, budget/resources, and value; mark each dimension as achieved, not achieved, or unknown; challenge unsupported success claims.
   * **Facilitator/Quality Checker (5th member):** maintain the 20-minute schedule, ensure every role has evidence, coordinate the group response, and check that the table and presentation contain no unsupported assertions.
4. Collect evidence for at least two success dimensions.
5. Mark uncertain facts as "unknown" and name the missing evidence.
6. Prepare a three-minute presentation.

**Presentation**

* Project and goal - 30 seconds
* Constraints and stakeholders - 30 seconds
* Success decision - 60 seconds
* Ambiguity - 60 seconds

**Time:** 20 minutes

**Deliverable**

Submit one table containing source, goal, constraints, stakeholders, scope/quality, time, budget/resources, value, ambiguity, and a short justification.

***

## Components of Project Management

Project management includes more than programming:

* project definition;
* project planning;
* project organization;
* quality management;
* project control;
* project documentation;
* project execution;
* project review and closure.

Good project management reduces complexity, coordination effort, and risk.

***

## The Magic Triangle

```
          Scope / Quality

                  △
                 / \
                /   \
               /     \
          Time -------- Budget
```

Changes are interconnected:

* more scope requires more time or budget;
* less budget requires less scope or more time;
* less time requires more resources or less scope.

***

## Exercise: Goal Conflict

**Scenario:** develop a campus study-room booking application.

**Process**

1. Individually write one outcome goal, process goal, and non-goal - 3 minutes.
2. Compare proposals and choose or combine the strongest outcome goal.
3. Rewrite the outcome goal until every SMART criterion is explicit.
4. Document the original scope/quality, time, and budget.
5. Change **one** dimension once: scope/quality, time, or budget.
6. Add a compensating measure for the remaining affected dimensions.
7. Describe the new risk and create a five-phase Gantt table.
8. Mark at least two milestones.

**Time:** 45 minutes

**Deliverable**

```
Outcome goal:
Process goal:
Non-goal:
SMART rewrite:
Changed dimension:
Compensating measure 1:
Compensating measure 2:
Risk:
Gantt table with 5 phases and dependencies:
```

The Gantt table must include start, end, dependency, responsible role, and result. A milestone must be a verifiable result or decision.

***

## SMART Goals

A good project goal is:

* **Specific** - clear and bounded;
* **Measurable** - with a verifiable result;
* **Attractive/agreed** - relevant and accepted;
* **Realistic** - achievable with available resources;
* **Time-bound** - with a fixed completion date.

The goal should use a result-oriented phrase: "… is achieved."

***

## SMART Goal Example

> By October 30, at least 80% of test users have successfully completed the core "Room Booking" function in under two minutes.

| SMART criterion | Check                            |
| --------------- | -------------------------------- |
| Specific        | Room Booking, test users         |
| Measurable      | at least 80%, under two minutes  |
| Attractive      | important usability outcome      |
| Realistic       | depends on resources and testing |
| Time-bound      | October 30                       |

***

## Phases and Milestones

**Project phase**

* time-bounded section;
* contains related tasks.

**Milestone**

* verifiable result or decision;
* not a normal activity;
* examples: project start, approval, test completion, acceptance.

A good milestone plan makes progress and decision points visible.

***

## Gantt Chart

A Gantt chart shows activities, durations, sequences, and milestones.

| Activity       |  Start |    End | Dependency     |
| -------------- | -----: | -----: | -------------- |
| Requirements   | Week 1 | Week 2 | none           |
| Design         | Week 2 | Week 3 | Requirements   |
| Implementation | Week 3 | Week 6 | Design         |
| Testing        | Week 6 | Week 7 | Implementation |
| Acceptance     | Week 8 | Week 8 | Testing        |

**Milestone:** Acceptance is a result, not a duration activity.

***

## Project Planning

Typical planning artifacts include:

* project description and requirements specification;
* work breakdown structure;
* schedule and milestone plan;
* capacity plan;
* cost and financial plan;
* communication plan;
* assignments and documentation.

Planning supports goal control; it does not create perfect prediction.

***

## Predictive vs. Empirical

| Predictive planning              | Empirical planning                 |
| -------------------------------- | ---------------------------------- |
| scope and sequence mostly known  | requirements or solution uncertain |
| detailed forward plan            | short learning cycles              |
| changes are controlled           | changes are used                   |
| planned-versus-actual comparison | transparency and adaptation        |

**Agile projects** are not "without a plan"; they **plan continuously based on results**.

***

## Agile Manifesto

We value:

* individuals and interactions **over** processes and tools;
* working software **over** comprehensive documentation;
* customer collaboration **over** contract negotiation;
* responding to change **over** following a plan.

The items on the right remain important. The items on the left receive priority.

Source: [agilemanifesto.org](https://agilemanifesto.org/)

***

## Agile Values in Practice

### Customer requirement changes

The team updates the backlog and goal rather than hiding the change.

### Technical evidence conflicts with the specification

The team discusses the evidence and adapts the plan with the customer.

### Working prototype instead of extensive design

The prototype becomes a learning tool; documentation remains purposeful.

***

## Scrum Is Not Project Management Ping-Pong

Scrum is a framework for complex work.

Scrum is based on:

* **transparency**
* **inspection**
* **adaptation**

Definitions must be visible and understandable to everyone involved.

***

## Scrum Roles

### Product Owner

* maximizes product value;
* owns the ordering of the Product Backlog.

### Scrum Master

* supports understanding and application of Scrum;
* helps remove impediments.

### Developers

* create a usable Increment;
* plan and manage their own work.

Current roles: [Scrum Guide](https://scrumguides.org/)

***

## Scrum Team

The Scrum Team is:

* small and cross-functional;
* responsible for creating the Increment;
* self-managing;
* collectively responsible for the Sprint Goal.

Older course material may describe the "Team" instead of accountabilities. The [current Scrum Guide](https://scrumguides.org/) uses three accountabilities.

***

## Scrum Events

1. **Sprint**
2. **Sprint Planning**
3. **Daily Scrum**
4. **Sprint Review**
5. **Sprint Retrospective**

Events create regular opportunities for inspection and adaptation.

***

## Sprint Planning

Sprint Planning answers:

1. **Why** is this Sprint valuable?
2. **What** can be delivered in this Sprint?
3. **How** will the work be done?

Outputs:

* Sprint Goal;
* selected Product Backlog items;
* plan for creating a usable Increment.

***

## Scrum Artifacts

| Artifact        | Purpose                                     |
| --------------- | ------------------------------------------- |
| Product Backlog | ordered work inventory for the product      |
| Sprint Backlog  | selected items and plan for the Sprint Goal |
| Increment       | inspectable part of the product             |

**Commitments**

* Product Goal;
* Sprint Goal;
* Definition of Done.

***

## Artifact and Commitment

```
Product Backlog
      ↓
   Product Goal
      ↓
Sprint Backlog
      ↓
   Sprint Goal
      ↓
   Increment
      ↓
Definition of Done
```

An Increment is usable only when it meets the applicable Definition of Done.

***

## Events and Goals

| Event           | Primary purpose                           |
| --------------- | ----------------------------------------- |
| Sprint Planning | establish work and the Sprint Goal        |
| Daily Scrum     | adapt the plan toward the Sprint Goal     |
| Sprint Review   | inspect the result with stakeholders      |
| Retrospective   | identify improvements for the next Sprint |

***

## Exercise: Scrum Map

In groups of 4-5:

1. Draw a vertical Sprint flow on the board.
2. Place Product Goal, Product Backlog, Sprint Goal, Sprint Backlog, Increment, and Definition of Done.
3. Assign the three Scrum accountabilities to their main decisions.
4. Place all five events in sequence. For each event, add its purpose and fixed or maximum time-box, if the guide defines one.
5. Draw arrows for information and work flow.
6. Add one example of inspection and adaptation.
7. Exchange boards with another group.
8. Verify the board against the official Scrum Guide. Report one correct and one incorrect finding, with a source reference.

**Time:** 45-60 minutes

**Deliverable**

* a photograph or export of the Scrum map;
* a five-line role and artifact summary;
* a correction list with Scrum Guide references;
* each group member's name next to the part they explained.

***

## Exercise: Agile Value Ranking

Choose one scenario:

* the customer adds an important feature during a Sprint;
* technical evidence conflicts with the specification;
* a working prototype has incomplete documentation;
* developers do not report impediments.

**Process**

1. Write the selected scenario on the board.
2. Identify the applicable left-hand and right-hand Agile Manifesto value.
3. Explain why the left-hand value has priority in this situation.
4. Explain how the right-hand value remains useful.
5. Define one concrete, observable team action.
6. Add an escalation or control rule for exceptional cases.
7. Prepare a 90-second justification.

**Time:** 30 minutes

**Deliverable**

```
Scenario:
Left-hand value:
Right-hand value:
Priority reason:
How the right-hand value remains useful:
Concrete team action:
Exceptional rule / traditional control:
```

***

## AI in Project Work

AI can accelerate drafts:

* Gantt checklists;
* risk summaries;
* Scrum event agendas;
* summaries of artifacts.

AI must not:

* present estimates or product goals as facts;
* invent unsupported stakeholders;
* replace Scrum definitions;
* take responsibility for human decisions.

***

## AI Practice

Prompt:

> Draft an agenda for Scrum events and a Gantt risk checklist for a four-person software team.

**Process**

1. Submit the exact prompt to an AI tool.
2. Ask the tool to mark uncertain claims or assumptions.
3. Verify every Scrum detail against the official Scrum Guide.
4. Verify every Gantt risk against at least one project assumption.
5. Mark unsupported claims with `[UNSUPPORTED]`.
6. Correct at least three points.

**Time:** 15-20 minutes

**Deliverable**

* the exact prompt;
* an AI output excerpt;
* a marked copy with at least three corrections;
* a five-line human review;
* one remaining limitation or risk.

***

## Day 1 Checklist

Students can:

* explain projects and project goals;
* formulate SMART goals;
* name non-goals and goal conflicts;
* distinguish phases and milestones;
* read Gantt activities and dependencies;
* explain the four Agile values;
* name the three Scrum accountabilities;
* explain the five Scrum events and three artifacts.

***

## Key Messages

1. Projects reduce complexity through goals and structure.
2. The magic triangle makes goal conflicts visible.
3. SMART goals create verifiability.
4. Agile prioritizes learning and collaboration.
5. Scrum provides an empirical framework: transparency, inspection, adaptation.
6. People remain responsible for decisions, including when using AI.

***

## Sources

* **Scrum primary source:** [scrumguides.org](https://scrumguides.org/)
* **Agile Manifesto primary source:** [agilemanifesto.org](https://agilemanifesto.org/)

