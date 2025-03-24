# 03. Planning

- [03. Planning](#03-planning)
  - [D6. Work Breakdown Structure (WBS), Prioritization, and Task Planning](#d6-work-breakdown-structure-wbs-prioritization-and-task-planning)
    - [1. Work Breakdown Techniques](#1-work-breakdown-techniques)
      - [Types of Work Breakdown Techniques:](#types-of-work-breakdown-techniques)
    - [2. Project Lifecycle Models](#2-project-lifecycle-models)
      - [Traditional (Waterfall) Model](#traditional-waterfall-model)
      - [Incremental Model](#incremental-model)
      - [Prototyping Model](#prototyping-model)
      - [Component-Based Model](#component-based-model)
      - [Rapid Application Development (RAD)](#rapid-application-development-rad)
      - [Spiral Model](#spiral-model)
      - [Formal Methods](#formal-methods)
      - [Rational Unified Process (RUP)](#rational-unified-process-rup)
      - [Agile Methodology](#agile-methodology)
    - [3. Iterative Incremental Model](#3-iterative-incremental-model)
      - [Example of Online Shop Requirements:](#example-of-online-shop-requirements)
      - [Iterations and increments:](#iterations-and-increments)
    - [4. Release Planning](#4-release-planning)
      - [Prioritizing User Stories:](#prioritizing-user-stories)
      - [Releases and Iterations:](#releases-and-iterations)
      - [Estimating Initial Velocity:](#estimating-initial-velocity)
    - [5. Iteration Planning](#5-iteration-planning)
    - [6. Monitoring and Velocity Tracking](#6-monitoring-and-velocity-tracking)
    - [7. Real-World Example: Online Bookshop](#7-real-world-example-online-bookshop)
      - [Example of Release Planning:](#example-of-release-planning)
    - [8. Task Scheduling](#8-task-scheduling)
      - [Task Scheduling Approaches:](#task-scheduling-approaches)
  - [D7. Time Management and Scheduling](#d7-time-management-and-scheduling)
    - [Overview](#overview)
    - [Principles of Software Project Scheduling](#principles-of-software-project-scheduling)
      - [1. Compartmentalization](#1-compartmentalization)
      - [2. Interdependency](#2-interdependency)
      - [3. Time Allocation](#3-time-allocation)
      - [4. Defined Responsibilities](#4-defined-responsibilities)
      - [5. Effort Validation](#5-effort-validation)
      - [6. Defined Outcomes](#6-defined-outcomes)
      - [7. Defined Milestones](#7-defined-milestones)
    - [Scheduling Techniques](#scheduling-techniques)
      - [Gantt Diagrams](#gantt-diagrams)
      - [PERT (Program Evaluation and Review Technique)](#pert-program-evaluation-and-review-technique)
        - [Elements of PERT:](#elements-of-pert)
        - [PERT Chart Representation](#pert-chart-representation)
        - [Transforming Tables to PERT Charts](#transforming-tables-to-pert-charts)
    - [Estimating Time with PERT](#estimating-time-with-pert)
      - [Earliest and Latest Times](#earliest-and-latest-times)
      - [Slack/Float](#slackfloat)
      - [Critical Path](#critical-path)
    - [Practical Examples for Clarification](#practical-examples-for-clarification)
      - [Example 1: Task Dependencies and Critical Paths](#example-1-task-dependencies-and-critical-paths)
      - [Example 2: Complex Dependencies](#example-2-complex-dependencies)
      - [Example 3: Real-World Task Sequencing](#example-3-real-world-task-sequencing)
    - [Advantages of PERT Charts](#advantages-of-pert-charts)
    - [References](#references)

## D6. Work Breakdown Structure (WBS), Prioritization, and Task Planning

Effective project management starts with careful planning, using techniques to clarify project scope and task responsibilities. Among these techniques are the Work Breakdown Structure (WBS), prioritization strategies, and detailed task planning.

---

### 1. Work Breakdown Techniques

Work breakdown techniques enable project teams to define and organize project scope clearly.

#### Types of Work Breakdown Techniques:

- **Work Breakdown Structure (WBS)**: Defines scope with increasing detail at each subsequent level:
  1. Life cycle phases
  2. Standard tasks within each phase
  3. Specific project tasks

- **Workflow Diagrams & Workflow Systems**: Provide visual flow of tasks and responsibilities.

---

### 2. Project Lifecycle Models

Different lifecycle models dictate project planning and execution approaches. Key lifecycle models include:

#### Traditional (Waterfall) Model
- **Phases**: Requirements → Design → Implementation → Testing → Deployment → Maintenance
- **Characteristics**:
  - Difficult to accommodate changes
  - Limited client/user engagement
  - Testing occurs at the end
  - Clearly defined structure and objectives

#### Incremental Model
- Develops projects through incremental improvements
- Repeated cycles of Design → Develop → Test → Implement
- Regularly provides partial functionalities

#### Prototyping Model
- Quick design → Prototype → Client feedback → Refine → Engineering
- Allows quick client involvement and iterative feedback

#### Component-Based Model
- Focuses on reusing existing software components
- Phases: Requirements → Component analysis → Requirements modification → System design → Integration → Validation

#### Rapid Application Development (RAD)
- Iterative rapid cycles of Design and Production
- Typically completed in 60-90 days
- Strong emphasis on reuse and rapid prototyping

#### Spiral Model
- Combines elements of prototyping and waterfall, emphasizing risk analysis

#### Formal Methods
- Mathematical specification and verification
- High accuracy, suitable for critical systems

#### Rational Unified Process (RUP)
- Iterative, flexible framework
- Based on stakeholder needs and use cases

#### Agile Methodology
- Emphasizes collaboration, flexibility, continuous improvement
- Principles include frequent delivery, embracing change, sustainable development pace, and face-to-face communication

---

### 3. Iterative Incremental Model

Combines iterative cycles (mini-projects) with incremental functionality enhancements.

#### Example of Online Shop Requirements:
- Search products, filter by attributes, view details, check availability, make payments, view related products.

#### Iterations and increments:
Each iteration involves analysis, design, implementation, and testing.

---

### 4. Release Planning

Involves selecting iterations, estimating velocity, prioritizing user stories, and allocating tasks to iterations.

#### Prioritizing User Stories:
- Maximize organizational value
- Consider:
  - Risk and complexity
  - Impact on other stories
  - User desirability (both broad and niche groups)
  - Story cohesiveness
- Utilize MoSCoW rules:
  - **Must-have**, **Should-have**, **Could-have**, **Won't-have**

#### Releases and Iterations:
- Velocity: Amount of work achievable per iteration
- Stories should be small enough to fit within iteration constraints
- Acceptance tests ensure stories meet user expectations

#### Estimating Initial Velocity:
- Historical data
- Educated guesses
- Initial iteration feedback

---

### 5. Iteration Planning

Detailed iteration-level task breakdown:
- Break user stories into tasks
- Assign clear developer responsibilities
- Evaluate if team capacity matches tasks allocated

**Example Tasks for "Hotel Search" story:**
- Design UI, HTML coding for details, SQL retrieval, help documentation, etc.

---

### 6. Monitoring and Velocity Tracking

Regular monitoring ensures project stays on track:
- **Burndown Charts:** Visual representation of remaining work
- Daily tracking helps in adapting to changes swiftly

---

### 7. Real-World Example: Online Bookshop

Detailed stories organized by priority:
- Basic search, shopping cart, account management, reviews, administrative tasks, order tracking, etc.

#### Example of Release Planning:
- Defined iterations with clear deliverables

---

### 8. Task Scheduling

Key scheduling variables:
- **Duration**: Total time required
- **Work**: Hours needed
- **Units**: Number of people involved
- **Daily hours (hd)**: Constant work hours per day

#### Task Scheduling Approaches:
- **Fixed Units**: Adjust duration/work if personnel or estimates change
- **Fixed Work**: Add resources to complete tasks within fixed deadlines
- **Fixed Duration**: Adjust workload or team size without changing deadlines

---

## D7. Time Management and Scheduling

---

### Overview

Effective scheduling ensures achieving project goals within the allotted timeframe by distributing estimated effort across specific tasks.

- **Scheduling definition (Project Management Institute)**: Planning activities strategically to meet goals and priorities within available time.
- **Scheduling in Software Projects (Allen B. Tucker)**: Allocating estimated effort across the project's duration to specific engineering tasks.

---

### Principles of Software Project Scheduling

#### 1. Compartmentalization
- Breaking down a project into manageable tasks.
- Both product and process require decomposition.

#### 2. Interdependency
- Some tasks must follow a sequential order.
- Others can proceed independently.

#### 3. Time Allocation
- Assign work units (e.g., person-days) and define start/end dates.

#### 4. Defined Responsibilities
- Clearly assign each task to specific team members.

#### 5. Effort Validation
- Ensure allocated effort does not exceed available personnel capacity.

#### 6. Defined Outcomes
- Each task must have clear deliverables, usually forming part of larger work products.

#### 7. Defined Milestones
- Tasks are grouped around milestones, which represent significant project achievements after review and approval.

---

### Scheduling Techniques

#### Gantt Diagrams
- Visual timelines displaying task duration and dependencies.
- Facilitates easy understanding of project progress and schedule.

#### PERT (Program Evaluation and Review Technique)
- Visualizes task sequences and dependencies, suitable for complex projects.

##### Elements of PERT:
- **Activity**: Task to perform (shown by arrows).
- **Event**: Start/end of activities (shown by nodes).
- **Predecessor**: Tasks required to complete before others start.

##### PERT Chart Representation
- Clearly depicts task sequences and dependencies.
- Dummy activities indicate indirect dependencies.

##### Transforming Tables to PERT Charts
- Lists tasks, durations, and predecessors clearly, translating them visually to facilitate better understanding of the project timeline.

---

### Estimating Time with PERT

#### Earliest and Latest Times
- Calculate the earliest start and latest finish for activities to manage project timing effectively.
- Assess the impact of delays on subsequent activities.

#### Slack/Float
- Measures flexibility in scheduling tasks without delaying the project.

#### Critical Path
- Sequence of tasks with no slack; delays directly impact overall project duration.

---

### Practical Examples for Clarification

#### Example 1: Task Dependencies and Critical Paths
- Demonstrates task interdependencies and their impacts on project timing.

#### Example 2: Complex Dependencies
- Illustrates managing multiple dependencies clearly through graphical representation.

#### Example 3: Real-World Task Sequencing
- Offers clarity on managing practical complexities encountered in actual projects.

---

### Advantages of PERT Charts

- Clear graphical visualization.
- Effective handling of complex dependencies.
- Precise estimation of earliest/latest start and finish times.
- Easy identification of floats and critical paths.

---

### References

- "User Stories Applied for Agile Software Development" by Mike Crohn, Addison Wesley (2009)
- *A Guide to the Project Management Body of Knowledge (6th ed.)*, Project Management Institute, 2017.
- *Computer Science Handbook*, Allen B. Tucker, CRC Press, 2004.
- PM Project Manager - [PERT Chart Guide](https://www.projectmanager.com/guides/pert-chart)
- Corporate Finance Institute - [PERT Overview](https://corporatefinanceinstitute.com/resources/knowledge/other/project-evaluation-review-technique-pert/)
