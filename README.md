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
  - [✅ Software quality](#-software-quality)
  - [📏 Standards](#-standards)
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

Risk management focuses on identifying potential risks, analyzing their impact, and developing mitigation strategies. This ongoing process includes risk identification, assessment, response planning, and continuous monitoring throughout the project lifecycle.

> ⚡ **Tip:** ¡No ignores los riesgos pequeños! A menudo, los problemas más grandes empiezan con detalles que nadie vigiló.

---

## ✅ Software quality

Software quality management ensures that project deliverables meet defined standards and user requirements. It involves quality planning, quality assurance, and quality control processes that maintain the integrity of software products.

> 🧪 **Pro Tip:** Automatiza pruebas siempre que puedas. La calidad no es negociable, ¡pero sí escalable!

---

## 📏 Standards

Modern project management relies on established standards and methodologies to ensure consistency, quality, and successful outcomes. Below is a summary of key standards and when to use each:

Comparativa de marcos de trabajo y cuándo aplicarlos:

| Metodología   | Enfoque                    | Cuándo usarla                             |
| ------------- | -------------------------- | ----------------------------------------- |
| **Métrica 3** | Procesos públicos          | IT sector público español                 |
| **PRINCE2**   | Control y gobernanza       | Proyectos regulados o complejos           |
| **Scrum**     | Iterativo e incremental    | Productos con cambios rápidos             |
| **XP**        | Prácticas de ingeniería    | Alta calidad técnica, entregas frecuentes |
| **Lean**      | Eliminación de desperdicio | Mejora continua, eficiencia operativa     |
| **Kanban**    | Flujo visual y WIP         | Soporte, DevOps, mantenimiento            |
| **PMBOK**     | Buenas prácticas           | Portafolios, PMOs, proyectos grandes      |

**1. Métrica 3**

- **Purpose:** Methodology for planning, developing, and maintaining information systems, especially in Spain's public sector.
- **When to use:** Public IT projects in Spain or where legal/traceability requirements are strict.
- **Key features:** Phase-based, strong documentation, quality gates, based on ISO/IEC standards.

**2. PRINCE2**

- **Purpose:** Structured project management method emphasizing control, roles, and stage boundaries.
- **When to use:** Projects needing formal control, documentation, and clear governance (e.g., government, large organizations).
- **Key features:** Business case focus, stage reviews, adaptable to traditional and agile projects.

**3. Scrum**

- **Purpose:** Agile framework for iterative, incremental product development.
- **When to use:** Fast-changing environments, startups, or feature-driven teams needing adaptability.
- **Key features:** Sprints, roles (Product Owner, Scrum Master, Team), artifacts (backlogs, burndown charts), regular reviews.

**4. Extreme Programming (XP)**

- **Purpose:** Agile methodology focused on engineering practices for high-quality code.
- **When to use:** Teams prioritizing technical excellence, rapid feedback, and frequent releases.
- **Key features:** Test-driven development, pair programming, continuous integration.

**5. Lean Software Development**

- **Purpose:** Minimize waste and maximize value in software delivery.
- **When to use:** Projects seeking efficiency, rapid delivery, and continuous improvement.
- **Key features:** Eliminate waste, empower teams, deliver fast, build quality in.

**6. Kanban**

- **Purpose:** Visual workflow management to optimize flow and limit work in progress.
- **When to use:** Maintenance, support, DevOps, or teams seeking incremental process improvement.
- **Key features:** Visual boards, WIP limits, evolutionary change.

**7. PMBOK (Project Management Body of Knowledge)**

- **Purpose:** Comprehensive framework covering all aspects of project management.
- **When to use:** Large, complex projects or portfolios needing structured processes and best practices.
- **Key features:** Process groups (Initiating, Planning, Executing, Monitoring & Controlling, Closing), 10 knowledge areas (scope, time, cost, quality, etc.), RACI matrices.

**Choosing a Methodology:**

- Consider project size, complexity, regulatory needs, and stakeholder involvement.
- Métrica 3: Public sector IT in Spain.
- Scrum/XP: Fast-paced, product-focused teams.
- PRINCE2: Projects needing control and documentation.
- Lean/Kanban: Continuous delivery, maintenance, or process improvement.
- PMBOK: Comprehensive oversight for large or complex initiatives.
- Tailor your approach—combine elements as needed for your project's context.

---

## ✨ Créditos

- Universidad de Las Palmas de Gran Canaria – Grado en Ingeniería Informática
- Asignatura: Proyectos de Ingeniería y Gestión de Software
- Repositorio mantenido por: [Francisco J.](https://github.com/gitfrandu4) 💻

---

¿Te ha servido? ¡Mejora continua activada! 💪 Si tienes sugerencias o quieres aportar, ¡bienvenido!
