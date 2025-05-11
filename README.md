# 📘 Proyectos de Ingeniería y Gestión de Software

¡Bienvenido! 👋 Este es tu **hub de recursos** para la asignatura **Proyectos de Ingeniería y Gestión de Software (40989 - GII)**. Aquí encontrarás resúmenes, ejemplos, plantillas y consejos prácticos para dominar la gestión de proyectos de software, desde la estimación hasta la calidad y los estándares profesionales.

---

## 📚 Contenido Rápido

- [📘 Proyectos de Ingeniería y Gestión de Software](#-proyectos-de-ingeniería-y-gestión-de-software)
  - [📚 Contenido Rápido](#-contenido-rápido)
  - [🚀 ¿Cómo usar este repositorio?](#-cómo-usar-este-repositorio)
  - [📖 Introduction](#-introduction)
  - [🔢 Estimation](#-estimation)
  - [🗂️ Planning](#️-planning)
  - [⚠️ Risk management](#️-risk-management)
    - [🧩 What is a risk?](#-what-is-a-risk)
    - [🗂️ Risk taxonomy](#️-risk-taxonomy)
    - [🎯 Strategies for managing risks](#-strategies-for-managing-risks)
    - [🚦 Risk discovery and detection](#-risk-discovery-and-detection)
    - [💡 Practical examples of risks and mitigation](#-practical-examples-of-risks-and-mitigation)
    - [🏆 Keys to surviving risk](#-keys-to-surviving-risk)
  - [✅ Software quality](#-software-quality)
    - [🚀 Why care about software quality?](#-why-care-about-software-quality)
    - [📏 Key standards \& structural factors](#-key-standards--structural-factors)
    - [🏆 Software quality factors (ISO/IEC 25010)](#-software-quality-factors-isoiec-25010)
    - [🧠 Shneiderman's 8 Golden Rules for UI Design](#-shneidermans-8-golden-rules-for-ui-design)
    - [🧪 Static vs Dynamic Quality Assessment](#-static-vs-dynamic-quality-assessment)
    - [🧪 Testing taxonomy](#-testing-taxonomy)
    - [📊 Key metrics \& tools](#-key-metrics--tools)
    - [🛡️ Vulnerabilities \& technical debt](#️-vulnerabilities--technical-debt)
    - [✅ Key takeaways](#-key-takeaways)
  - [📏 Standards](#-standards)
    - [🏗️ What are project management standards?](#️-what-are-project-management-standards)
    - [🔍 Methodologies at a glance](#-methodologies-at-a-glance)
    - [🏛️ Métrica 3](#️-métrica-3)
    - [🏰 PRINCE2](#-prince2)
    - [🚀 Scrum](#-scrum)
    - [💻 Extreme Programming (XP)](#-extreme-programming-xp)
    - [🏭 Lean Software Development](#-lean-software-development)
    - [🗂️ Kanban](#️-kanban)
    - [📚 PMBOK (Project Management Body of Knowledge)](#-pmbok-project-management-body-of-knowledge)
    - [🧭 How to choose?](#-how-to-choose)
  - [✨ Créditos](#-créditos)

---

## 🚀 ¿Cómo usar este repositorio?

1. **Explora los resúmenes**: Cada sección condensa lo esencial de la materia, con ejemplos y tablas para repasar rápido antes de exámenes o prácticas.
2. **Busca plantillas y ejemplos** en las carpetas temáticas para tus entregas o proyectos de equipo.
3. **Consulta los cuadros comparativos** para elegir la mejor metodología según tu caso.
4. **¿Dudas?** Usa los callouts y tips destacados para aclarar conceptos clave.

> 💡 **Pro Tip:** ¡No memorices! Relaciona los conceptos con casos reales o tus propias experiencias para interiorizarlos mejor.

---

## 📖 Introduction

Key points from Introduction to Project Management:

**Market Research and SWOT Analysis:**

- Executive Summary includes product description, market analysis, and team composition
- SWOT identifies internal Strengths/Weaknesses and external Opportunities/Threats
- Project objectives should follow SMART criteria (Specific, Measurable, Achievable, Rewarding, Time-based)

**Project Management Approaches:**

- Knowledge areas include Integration, Scope, Time, Quality, Resource, Communications, Risk, and Cost Management
- Predictive (waterfall) approaches work when requirements are clear; Adaptive (agile) approaches for evolving requirements
- Hybrid methodologies combine elements from both approaches based on project needs
- Project management trends include agile, DevOps, mobile technologies, and virtual team management

**Project Manager Roles:**

- Project managers serve as Planners, Organizers, Coaches, Problem Solvers, and Communicators
- Essential skills include budgeting, resource management, emotional intelligence, and conflict resolution
- Common mistakes include poor stakeholder management and unclear responsibility assignment

**Product Backlog Management:**

- User stories follow "As a [role], I want [action], so that [benefit]" format
- INVEST criteria ensures stories are Independent, Negotiable, Valuable, Estimable, Small, and Testable
- Spikes (research tasks) help resolve uncertainty in requirements or implementation approaches
- User stories evolve through discovery, planning, execution, and acceptance testing

---

## 🔢 Estimation

Effective software estimation is essential for project success, yet uniquely challenging due to factors like productivity variability, requirement volatility, and rapid innovation. Below is a summary of key concepts and practices:

**1. Estimation Challenges:**

- Software estimation is less predictable than in other industries due to invisible progress, changing requirements, and wide productivity differences.
- Aim for accuracy (closeness to true value) over false precision; use ranges and review estimation history to improve.

**2. Estimation Phases:**

- **Size Estimation:** How much and how complex? (e.g., user stories, function points, lines of code)
- **Effort Estimation:** How long and how many people? (person-hours, team composition)
- **Cost Estimation:** What is the budget? (labor, infrastructure, operational, contingency)
- These are interdependent—changing one affects the others.

**3. Metrics in Estimation:**

- **Product Metrics:** Size (LOC, functions), complexity, quality
- **Process Metrics:** Time, effort, efficiency, stability
- **Resource Metrics:** Team size, productivity, cost
- **Size-based metrics:** Tangible counts (LOC, modules)
- **Function-based metrics:** Function points, object points, use case points, story points (focus on delivered value)

**4. Estimation Techniques:**

- **Expert Judgment:** Leverages experience; quick but subjective
- **Delphi Method:** Structured, anonymous expert consensus
- **Historical/Analogous:** Based on similar past projects
- **Parametric/Algorithmic:** Uses mathematical models (e.g., COCOMO)
- **Decomposition:** Breaks project into smaller, estimable units
- **Phased Estimation:** Detailed for near-term, rough for future phases
- **Pricing to Win:** Scope adjusted to fit a fixed budget

**5. Agile Estimation Approaches:**

- **Story Points:** Relative complexity, estimated by team consensus
- **Planning Poker:** Consensus-based estimation using cards (often Fibonacci sequence)
- **MoSCoW Prioritization:** Must, Should, Could, Won't have
- **Velocity & Burndown Charts:** Track progress and forecast delivery

**6. Cost Estimation and Pricing:**

- **Cost Models:** Top-down (broad, early), bottom-up (detailed, later), or hybrid
- **Pricing Models:** Cost-plus, opportunity, going rate, monopolistic, loss leader, etc.
- **Per-person-hour cost:** Includes direct labor and overhead (indirect staff, facilities, utilities)
- **Employee cost analysis:** Considers gross salary, taxes, and additional contributions

**7. Practical Example:**

- Estimation connects user stories to release planning, timeline projections, and cost calculation (see online bookshop example in the full document).

> 📌 **Did you know?** ¡La Ley de Brooks dice que añadir más programadores a un proyecto retrasado lo retrasa aún más! Planifica bien tu equipo desde el inicio.

**Key Takeaway:**

- Use a combination of metrics and techniques, adapt to project context, and continuously refine estimates based on feedback and historical data.

---

## 🗂️ Planning

Effective project planning defines the path from idea to delivery, ensuring scope clarity, realistic schedules, and resource alignment. Key concepts and practices include:

**1. Work Breakdown Structure (WBS):**

- Breaks the project into phases, standard tasks, and specific subtasks for clarity and estimation.
- Visual tools like workflow diagrams help clarify responsibilities and dependencies.

**2. Project Lifecycle Models:**

- **Traditional (Waterfall):** Sequential phases; best for stable, well-defined requirements.
- **Incremental/Iterative:** Delivers value in cycles, adding features over time.
- **Prototyping:** Early feedback through quick prototypes and refinements.
- **Component-Based:** Emphasizes reuse of existing modules.
- **RAD/Spiral/RUP:** Focus on rapid delivery, risk management, and stakeholder feedback.
- **Agile:** Emphasizes collaboration, adaptability, and frequent delivery.

**3. Release and Iteration Planning:**

- Organize work into releases and sprints/iterations.
- Prioritize user stories using value, risk, and MoSCoW (Must, Should, Could, Won't have).
- Estimate team velocity to allocate work per iteration.
- Split large stories and validate with acceptance tests.

**4. Iteration Planning and Task Breakdown:**

- Decompose stories into actionable tasks for each iteration.
- Assign responsibilities and estimate effort for each task.
- Encourage team ownership and realistic commitments.

**5. Monitoring and Velocity Tracking:**

- Use burndown charts and velocity metrics to track progress.
- Adjust plans based on actual performance and scope changes.
- Monitor story point evolution to manage scope and predict completion.

**6. Task Scheduling Approaches:**

- **Fixed Units:** Team size is fixed; duration varies with workload.
- **Fixed Work:** Total effort is fixed; team size or duration can change.
- **Fixed Duration:** Deadline is fixed; adjust team size or scope as needed.
- Use formulas and visual tools (Gantt, PERT) to plan and communicate schedules.

**7. Time Management and Scheduling:**

- Break work into manageable tasks (compartmentalization).
- Identify dependencies and allocate time/resources accordingly.
- Define responsibilities, outcomes, milestones, and validate effort.
- Use Gantt charts for timelines and PERT for complex dependencies and critical path analysis.

> 🏁 **Consejo:** ¡No subestimes la importancia de los hitos! Celebrar pequeños logros motiva al equipo y ayuda a detectar desvíos a tiempo.

**Key Takeaway:**

- Combine structured breakdown, iterative planning, and adaptive scheduling to deliver projects on time, within scope, and with high quality. Continuously monitor, adjust, and communicate to keep the project on track.

---

## ⚠️ Risk management

Risk management is the art of anticipating problems before they become crises. It's not just for big companies—every software project, from a class assignment to a global SaaS, needs to think about risks!

---

### 🧩 What is a risk?

> **Risk:** An uncertain event that, if it occurs, will affect one or more project objectives (scope, time, cost, quality)—for better or worse.

- **Risk ≠ Problem:** A risk is a future uncertainty; a problem has already happened.
- **Risk exposure:** Probability × Impact (in money, time, reputation, etc.)

```text
Example: If there's a 20% chance a bug causes a 5-day delay, the risk exposure is 1 day.
```

---

### 🗂️ Risk taxonomy

| Type               | Main examples                                        |
| ------------------ | ---------------------------------------------------- |
| **Technical**      | Requirement changes, tough integration, obsolescence |
| **Management**     | Bad estimation, poor communication, unclear scope    |
| **Organizational** | Lack of resources, budget issues, dependencies       |
| **External**       | Suppliers, regulations, market, natural disasters    |

> 💡 **Tip:** Use this table as a checklist in your planning meetings.

---

### 🎯 Strategies for managing risks

| Strategy     | What it means                                      |
| ------------ | -------------------------------------------------- |
| **Avoid**    | Don't do the risky task (but you lose the benefit) |
| **Mitigate** | Reduce probability/impact before it happens        |
| **Contain**  | Set aside time/money to absorb the hit             |
| **Evade**    | Wait for the risk to disappear on its own          |

- **Mitigation:** Preventive actions (tests, prototypes, training...)
- **Contingency:** Plan B ready to activate if the risk materializes (runbook, rollback, time buffer)
- **Risk reserve:** Time/money buffer proportional to total exposure

> 🛡️ **Pro Tip:** Mitigate what you can, and always have a contingency plan for what you can't control!

---

### 🚦 Risk discovery and detection

- **Postmortem mining:** Analyze past projects and turn problems into future risks.
- **6-3-5 Brainwriting:** Fast team technique to generate dozens of risks.
- **Transition:** A risk becomes a problem when it materializes. Use early warning indicators ("smells like trouble") to get ahead of issues.

> 👀 **Don't ignore small risks!** Big problems often start as overlooked details.

---

### 💡 Practical examples of risks and mitigation

- **Estimation & planning:** Involve the team, iterate quickly, learn from every sprint.
- **Requirements inflation:** Continuous prioritization and frequent client feedback.
- **Staff turnover:** Document, pair program, encourage collaboration.
- **Incomplete specs:** Active Product Owner, JAD sessions, prototypes.
- **Low productivity:** Short iterations, coaching, clear goals.
- **Budget overrun:** Rolling wave planning, review and adjust frequently.
- **Knowledge silos:** Share, document, use cross-functional squads.

---

### 🏆 Keys to surviving risk

- Risks are tomorrow's problems: manage them today!
- Quantify exposure to prioritize (not all risks deserve your time).
- Use taxonomies and structured techniques to cover all bases.
- Team culture matters: encourage transparency and anticipation.
- Mitigate, but always have a plan B.

> 🚀 **Pro Tip:** The best project isn't the one with no risks—it's the one that manages them best!

---

## ✅ Software quality

Software quality is more than "it works"—it means your code is safe, maintainable, scalable, and makes users happy. High-quality software is cheaper to maintain, easier to evolve, and less likely to cause disasters.

---

### 🚀 Why care about software quality?

- Software failures can cause real harm: lost money, reputation, or even lives.
- Clean, understandable code today = fewer bugs and surprises tomorrow.

> 📝 **Pro Tip:** The cleaner your code, the less you'll fear future changes.

---

### 📏 Key standards & structural factors

- **ISO/IEC 5055:2021**: Focuses on Security, Reliability, Performance Efficiency, and Maintainability.
- **CISQ**: Adds Adequate Size (healthy code-to-functionality ratio).

---

### 🏆 Software quality factors (ISO/IEC 25010)

| Factor              | Description                                                   |
| ------------------- | ------------------------------------------------------------- |
| **Usability**       | Helps users perform tasks safely, effectively, and enjoyably. |
| **Reliability**     | Works without failure in a given time/environment.            |
| **Efficiency**      | Delivers performance with optimal resource use.               |
| **Reusability**     | Code/components can be reused in new apps.                    |
| **Maintainability** | Easy to understand, fix, and improve.                         |
| **Portability**     | Runs on different platforms/OSes with minimal changes.        |
| **Testability**     | Easy to test systematically and efficiently.                  |

> 📝 **Dev Hint:** "Can I test it?" is a fundamental design question.

---

### 🧠 Shneiderman's 8 Golden Rules for UI Design

1. **Strive for consistency**
2. **Seek universal usability**
3. **Offer informative feedback**
4. **Design dialogues for closure**
5. **Offer simple error handling**
6. **Permit easy reversal of actions**
7. **Support internal locus of control**
8. **Reduce short-term memory load**

> 💡 **Example:** Confirmation before delete + undo = golden rule combo.

---

### 🧪 Static vs Dynamic Quality Assessment

- **Static analysis:** Examines code without running it (linters, SonarQube). Finds bugs, style issues, vulnerabilities early.
- **Dynamic analysis:** Tests software while running (unit, integration, system tests). Finds runtime bugs, performance issues.

| Category      | Static Analysis            | Dynamic Analysis             |
| ------------- | -------------------------- | ---------------------------- |
| Code required | Source code only           | Executable version needed    |
| Focus         | Structure, standards, bugs | Behavior, runtime conditions |
| Tools         | Linters, SonarQube         | Selenium, profilers, JMeter  |
| Coverage      | Full theoretical paths     | Based on test coverage       |
| Cost          | Lower                      | Higher                       |

---

### 🧪 Testing taxonomy

- **By nature:**
  - Functional (features work as specified)
  - Non-functional (speed, security, usability)
- **By level:**
  - Unit → Integration → System → Acceptance
- **By strategy:**
  - Incremental (build → test → extend)
  - Non-incremental (test all at once)

| Test Type         | Purpose                                  |
| ----------------- | ---------------------------------------- |
| **Performance**   | Speed under expected load                |
| **Usability**     | User experience, intuitiveness           |
| **Compatibility** | Runs across platforms, browsers, devices |
| **Load**          | Stability under expected usage volume    |
| **Stress**        | Behavior beyond normal capacity          |
| **Scalability**   | Growth in users/data                     |
| **Stability**     | Long-term reliability under normal use   |

> 📝 **Dev Hint:** Reliability depends on real-world testing, not just code!

---

### 📊 Key metrics & tools

- **Cyclomatic complexity:** Measures number of decision paths in code. High = harder to test/maintain.
- **SonarQube:** Analyzes code for maintainability (code smells), reliability (bugs), security (vulnerabilities), and risk-prone logic (security hotspots).

---

### 🛡️ Vulnerabilities & technical debt

- **Vulnerabilities:** Flaws that attackers can exploit (bad design, coding mistakes).
- **Technical debt:** The cost of quick-and-dirty code that needs refactoring later. Like financial debt, it accrues "interest"—the longer you wait, the harder it is to fix.

> 📝 **Dev Hint:** Sometimes technical debt is OK—if you document it and pay it off later.

---

### ✅ Key takeaways

- Quality is not just "it works"—it's about safety, scalability, performance, and user happiness.
- Testing is not a phase—it's a mindset.
- Use standards, metrics, and tools to build better software from day one.

---

## 📏 Standards

Project management standards and methodologies provide a shared language, clear expectations, and proven practices for project success. They help teams avoid chaos, ensure quality, and scale up efficiently.

---

### 🏗️ What are project management standards?

> **Definition:** Structured frameworks that guide how projects are started, planned, executed, monitored, and closed.

**Why use them?**

- **Consistency:** No need to reinvent the wheel for every project.
- **Efficiency:** Reduces miscommunication and wasted effort.
- **Accountability:** Defines clear roles, responsibilities, and deliverables.
- **Scalability:** Makes it easier to manage projects of any size.

---

### 🔍 Methodologies at a glance

| Methodology   | Approach/Focus          | When to use it                        |
| ------------- | ----------------------- | ------------------------------------- |
| **Métrica 3** | Public sector, process  | IT projects in Spain's public sector  |
| **PRINCE2**   | Control, governance     | Regulated or complex projects         |
| **Scrum**     | Iterative, agile        | Fast-changing, feature-driven teams   |
| **XP**        | Engineering practices   | High technical quality, rapid release |
| **Lean**      | Waste elimination       | Continuous improvement, efficiency    |
| **Kanban**    | Visual flow, WIP limits | Support, DevOps, maintenance          |
| **PMBOK**     | Best practices, process | Large projects, portfolios, PMOs      |

---

### 🏛️ Métrica 3

- **Purpose:** Planning, developing, and maintaining information systems (esp. Spain's public sector)
- **Key:** Phase-based, strong documentation, legal/traceability focus
- **When:** Public IT projects, or where legal compliance is strict

---

### 🏰 PRINCE2

- **Purpose:** Structured project management with clear roles and stage boundaries
- **Key:** Business case focus, stage reviews, adaptable to traditional/agile
- **When:** Projects needing formal control, documentation, and governance

---

### 🚀 Scrum

- **Purpose:** Agile framework for iterative, incremental product development
- **Key:** Sprints, Product Owner, Scrum Master, team roles, backlogs, burndown charts
- **When:** Fast-changing environments, startups, or teams needing adaptability

---

### 💻 Extreme Programming (XP)

- **Purpose:** Agile methodology focused on engineering excellence
- **Key:** Test-driven development, pair programming, continuous integration
- **When:** Teams prioritizing technical quality and rapid feedback

---

### 🏭 Lean Software Development

- **Purpose:** Minimize waste, maximize value
- **Key:** Eliminate waste, empower teams, deliver fast, build quality in
- **When:** Projects seeking efficiency, rapid delivery, and continuous improvement

---

### 🗂️ Kanban

- **Purpose:** Visual workflow management, optimize flow, limit work in progress
- **Key:** Visual boards, WIP limits, evolutionary change
- **When:** Maintenance, support, DevOps, or teams seeking incremental improvement

---

### 📚 PMBOK (Project Management Body of Knowledge)

- **Purpose:** Comprehensive framework for all aspects of project management
- **Key:** Process groups (Initiating, Planning, Executing, Monitoring & Controlling, Closing), 10 knowledge areas, RACI matrices
- **When:** Large, complex projects or portfolios needing structured processes and best practices

---

### 🧭 How to choose?

- **Métrica 3:** Public sector IT in Spain
- **Scrum/XP:** Fast-paced, product-focused teams
- **PRINCE2:** Projects needing control and documentation
- **Lean/Kanban:** Continuous delivery, maintenance, or process improvement
- **PMBOK:** Comprehensive oversight for large or complex initiatives
- **Pro Tip:** Tailor your approach—combine elements as needed for your project's context!

---

## ✨ Créditos

- Universidad de Las Palmas de Gran Canaria – Grado en Ingeniería Informática
- Asignatura: Proyectos de Ingeniería y Gestión de Software
- Repositorio mantenido por: [Francisco J.](https://github.com/gitfrandu4) 💻

---

¿Te ha servido? ¡Mejora continua activada! 💪 Si tienes sugerencias o quieres aportar, ¡bienvenido!
