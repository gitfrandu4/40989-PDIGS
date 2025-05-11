# Risk Management

- [Risk Management](#risk-management)
  - [D9. Exposure, taxonomy and discovery](#d9-exposure-taxonomy-and-discovery)
    - [What Is a Risk?](#what-is-a-risk)
    - [Risk vs. Crisis Management](#risk-vs-crisis-management)
    - [Risk Transition](#risk-transition)
    - [📊 Risk Exposure](#-risk-exposure)
    - [🔥 Showstopper Risks](#-showstopper-risks)
    - [🎯 Why Risk Management?](#-why-risk-management)
    - [🧭 Risk Taxonomy](#-risk-taxonomy)
    - [⚠️ Risk Categories](#️-risk-categories)
      - [1. Technical Risks (Product)](#1-technical-risks-product)
      - [2. Management Risks (Project)](#2-management-risks-project)
      - [3. Organizational Risks (Business)](#3-organizational-risks-business)
      - [4. External Risks](#4-external-risks)
    - [🧠 Risk Discovery](#-risk-discovery)
      - [Key Strategy: **Postmortem Mining**](#key-strategy-postmortem-mining)
      - [Key Strategy: **6-3-5 Brainwriting**](#key-strategy-6-3-5-brainwriting)
    - [Risks You Can Ignore](#risks-you-can-ignore)
    - [Key Takeaways](#key-takeaways)
    - [🧠 Deep Dive – D9 References \& Tools](#-deepdive--d9-references--tools)
  - [D10. Uncertainty, mitigation and contingency](#d10-uncertainty-mitigation-and-contingency)
    - [🌫️ Understanding Uncertainty](#️-understanding-uncertainty)
    - [📐 Quantifying Uncertainty](#-quantifying-uncertainty)
      - [🎯 Schedule Uncertainty](#-schedule-uncertainty)
      - [🧩 Functional Uncertainty](#-functional-uncertainty)
    - [🛠️ Risk Response Strategies](#️-risk-response-strategies)
    - [🔁 Mitigation vs Contingency](#-mitigation-vs-contingency)
    - [💰 Risk Reserve](#-risk-reserve)
    - [🧭 Transition Indicators](#-transition-indicators)
    - [💡 Real-World Examples of Risk Mitigation](#-real-world-examples-of-risk-mitigation)
      - [1. **Estimation \& Scheduling**](#1-estimation--scheduling)
      - [2. **Requirements Inflation**](#2-requirements-inflation)
      - [3. **Employee Turnover**](#3-employee-turnover)
      - [4. **Specification Breakdown**](#4-specification-breakdown)
      - [5. **Poor Productivity**](#5-poor-productivity)
      - [6. **Budget Overrun**](#6-budget-overrun)
      - [7. **Knowledge Silos**](#7-knowledge-silos)
    - [🧨 Common Procedural Risks](#-common-procedural-risks)
    - [✅ Key Takeaways](#-key-takeaways)
    - [🧠 Deep Dive – D10 References \& Techniques](#-deepdive--d10-references--techniques)
  - [Bibliography](#bibliography)

## D9. Exposure, taxonomy and discovery

Effective risk management begins with understanding what risk is, how to measure its impact, and how to classify and identify it within a project environment. This section introduces foundational concepts, practical classification systems (taxonomy), and structured strategies for risk discovery.

---

### What Is a Risk?

- **Risk (PMBOK 7):** an _uncertain event or condition_ that, **if it occurs, has a positive (“opportunity”) or negative (“threat”) effect** on one or more project objectives – scope, schedule, cost, or quality.

  🔍 **Ejemplo:** Un fallo de integración con la API de pagos (amenaza) o una librería OSS que reduce el tiempo de desarrollo (oportunidad).

- **Problem / Issue:** a risk that **has already materialized** — the uncertainty is gone and the impact is real.

- Risks are defined by two key properties:
  - **Uncertainty** – the event may or may not happen.
  - **Potential loss** – if it does happen, it will have negative consequences.

💻 Dev‑Note: No descuides los **riesgos positivos**. Si descubres una API que reduce en 30 % la complejidad, planifica cómo explotar esa oportunidad.

---

### Risk vs. Crisis Management

- **Risk Management** involves identifying and mitigating risks _before_ they happen. Is the process of thinking out corrective actions before a problem occurs, while it's still an abstraction.
- **Crisis Management** is reactive, dealing with consequences _after_ a risk becomes a problem.

> **Metaphor:** Risk management is like installing smoke detectors and fire sprinklers. Crisis management is calling the fire department once the building is already burning.

---

### Risk Transition

A **risk transition** is when a potential risk becomes a **real problem**. When something that used to be a risk suddenly becomes a problem. This is the point at which the risk is said to **_materialize_**.

- **Transition indicators** are early warning signs that a risk may materialize.
- It’s acceptable to have **false positives** — better safe than sorry.

> Bob Charette: It’s the risks that you take that speed up the stairs for everyone else. Not taking them just assures that your world will come to be shaped and dominated by someone else.

---

### 📊 Risk Exposure

**Probability and Cost**

**Definition (EMV):** *Risk Exposure* = **Expected Monetary Value (EMV)** – the average cost (or time) you “buy” when you accept the risk.

$$
\text{Risk Exposure} = \text{Probability} \times \text{Cost}
$$

<img src="assets/2025-05-11-16-05-34.png" alt="Risk Exposure" width="300">

```
risk_exposure = probability * cost

Cost can be expressed in money or time:

  - If you identify a risk that is 20% likely to happen, and it will cost you a million dollars if it does, then the risk exposure is 200k.

  - If a risk is 20% likely to occur and will cost you five months if it does, then the risk exposure is 1 month of delay.
```

🧠 Deep Dive (PMBOK 7 / ISO 31000)

- _EMV_ is the foundation for **Quantitative Risk Analysis**, including **Monte Carlo simulations** that generate an S‑curve for schedule or cost.
- ISO 31000 recommends evaluating both **likelihood** and **consequence**; EMV merges them into a single metric.
  💻 Dev‑Note: Herramientas como **RiskyProject** o un simple notebook de Python con `numpy` pueden correr 10 000 iteraciones para ver la dispersión de tu fecha de release.

📝 Nota (ES): _Risk Exposure_ se traduce comúnmente como **“exposición al riesgo”**.  
💻 Dev‑Note: en un sprint planning, puedes estimar la _exposición al riesgo_ de un nuevo micro‑servicio multiplicando la probabilidad de fallo de despliegue (por ej. 15 %) por el tiempo de rollback (por ej. 4 h) ≈ 0,6 h de colchón que deberías reflejar en la story.

- **Cost** can be expressed in money, time, or other measurable impacts.
- Helps prioritize which risks are worth managing actively.

**Example:**

> A risk has a 20% chance of occurring and would cost €1,000,000 if it does.
>
> Risk Exposure = 0.2 × 1,000,000 = €200,000

Using quantitative values:

| Risk                                                                     | Probability (%) | Cost | Exposure |
| ------------------------------------------------------------------------ | --------------- | ---- | -------- |
| Add new marketing features                                               | 35              | 8    | 2.8      |
| Schedule is too optimistic for the implementation of the sales subsystem | 50              | 5    | 2.5      |
| Inappropriate design                                                     | 15              | 15   | 2.2      |
| The new toolkit does not provide the expected processing speed           | 30              | 5    | 1.5      |
| New requirements related to the automatic update from the server         | 5               | 20   | 1.0      |
| Unstable interface for plotting graphs                                   | 25              | 4    | 1.0      |
| Delay in the delivery of the tracking subsystem                          | 20              | 4    | 0.8      |

---

### 🔥 Showstopper Risks

- **High-impact risks** that, if they occur, would force cancellation or complete redesign of a project.
- They cannot be effectively mitigated and must be managed through **project assumptions** (e.g., "assume this won’t happen").
- Still tracked, but not actively managed.

- Are difficult to price because they cost everything. They will force you either to completely rethink the product or to cancel the entire project.
- Can only be managed by what we call project assumptions. In order for you to continue your work, you must assume that the showstoppers will not occur.
- Still belongs on your risk list (since you still need to watch it), but it should be explicitly noted as a project assumption. That means it’s not going to be managed by you.

---

### 🎯 Why Risk Management?

- Bounds uncertainty
- Makes risk-taking strategic, not reckless
- Prevents blame games by making risk visible
- Ensures attention goes where it matters most
- Encourages team growth through ownership

---

### 🧭 Risk Taxonomy

Categorizing risks helps structure discovery and responsibility. PMBOK and industry practice define **four broad risk families**, each with subtypes:

| Category           | Examples                                                      |
| ------------------ | ------------------------------------------------------------- |
| **Technical**      | Requirements volatility, integration issues, high complexity  |
| **Management**     | Poor estimation, communication breakdowns, unclear priorities |
| **Organizational** | Budget shortfalls, lack of staff, policy conflicts            |
| **External**       | Supplier failures, regulatory changes, market instability     |

> **Tip:** Use the taxonomy to build a checklist or brainstorming guide.

<img src="assets/2025-05-11-16-32-38.png" alt="Risk Taxonomy" width="300">

💻 Dev‑Note: Puedes convertir cada categoría en etiquetas de tu issue tracker (Jira, GitHub Projects, etc.) para filtrar rápidamente _bugs_ con alto componente técnico frente a riesgos externos como proveedores de CDN.

---

### ⚠️ Risk Categories

#### 1. Technical Risks (Product)

Technical risks refer to anything that could **go wrong with your software, hardware**, or any manuals or other process documents related to your project.

- Consider whether you have experts on your staff to resolve any software glitches that may arise or if you have access to external vendors who could help.
- Ask if the project is feasible with the material resources you have available.
- Review whether you’ve created user-friendly reference guides for your project’s implementation.

Examples:

- Changing requirements.
- Ambiguous specification.
- Technical uncertainty.
- Advanced technology not available.
- Complexity of design or implementation.
- Difficult integration of modules.
- Difficulties with the interfaces.
- High performance, reliability or quality requirements.
- Obsolescence.
- Maintenance.

#### 2. Management Risks (Project)

Project management risks involve **how the team** directly working on your project **operates** and what internal aspects of your team could impact your project’s success.

- Take a look at the culture and morale of your team and whether interpersonal issues could impact results.
- Review whether you have clear communication channels established between team members and if people know whom to turn to for specific issues.
- Consider whether you have included everyone you need to in the planning phase of your project or if there are other voices you need to consult.

Related to estimation and planning:

- Inaccurate time estimation.
- Insufficient resource allocation.
- Complex functionalities which were not identified and require more than expected.
- Expansion of the scope.

Related to team coordination and operation:

- Undefined responsibilities.
- Wrong prioritization.
- Bad communication.
- Lack of control.
- Lack of training.

#### 3. Organizational Risks (Business)

Organizational risks refer to aspects of your company’s overall resources and culture which could impact your project’s implementation.

- See if you have enough staff available to cover the time and effort it will take to complete your project.
- Review whether your financial processes are functioning well enough to pay subcontractors in a timely fashion.
- Ask whether you have the budget available to implement your project as intended.
- Consider whether you have policies in place to know who will make decisions on critical project issues.

Examples:

- Budget problems.
- Financial problems.
- Inaccurate cost estimation.
- Unexpected expenses.
- Expansion of the project’s scope.
- Staff problems.
- Lack of resources.
- Project dependencies.

#### 4. External Risks

External risks are things that could impact your project that are outside of your organization’s direct control.

- Analyze the current state of your market.
- Consider what problems might occur with your subcontractors or suppliers.
- Review related local, state, and federal regulations that impact your company’s field.
- Ask if your customers might change over time and how that would affect your project.

Examples:

- Unfavorable market development.
- Changes in the client’s strategy or priorities.
- Changes in the rules or legislation.
- Problems with suppliers.
- Natural disasters.

---

### 🧠 Risk Discovery

Common obstacles that prevent teams from identifying risks:

- **Fear of being seen as negative**
- **Belief that raising a risk implies owning the solution**
- Hesitation without absolute proof

#### Key Strategy: **Postmortem Mining**

- _Yesterday's problem is today's risk_
- Run a few postmortems of projects good and bad and look for ways in which they deviated from their initial expectations. 
- Trace each deviation back to its cause and call that cause a risk. 
- Use of the output of the postmortem process as input to the risk management process. 

<img src="assets/2025-05-11-17-49-32.png" alt="Postmortem Mining" width="300">

- Analyze past projects (successful and failed)
- Identify unexpected deviations
- Trace them to their root causes
- Reframe those causes as _future risks_ for upcoming projects

#### Key Strategy: **6-3-5 Brainwriting**

- 6 people, 3 ideas each, passed on 5 times
- Generates 108 risk ideas in ~30 minutes

---

### Risks You Can Ignore

Not all risks are worth managing:

- Extremely low probability or minimal impact
- If they occur, the project becomes irrelevant
- They belong to external parties (e.g., client, regulator)

Still, document these in a _risk backlog_ with clear justification.

---

### Key Takeaways

- Risks are future problems: manage them proactively
- Quantify exposure to prioritize mitigation
- Use taxonomies to systematically uncover risk areas
- Don’t ignore the human side—fear and ambiguity block discovery
- Use structured strategies (e.g., postmortems, brainwriting) to ensure completeness

---

### 🧠 Deep Dive – D9 References & Tools

- **PMBOK 7**: Principles 3 & 4 (Stakeholders, Value) frame risk as a value‑protection exercise.
- **ISO 31000:2018**: Section 6 (Risk Assessment) outlines a generic process adaptable to any SDLC.
- **Practical Tools**:
  - **OWASP Risk Rating** for security‑centric projects.
  - **Chaos Engineering (Gremlin, Litmus)** to surface hidden technical risks in microservices.
  - **Observability (OpenTelemetry + Grafana)** as an early transition indicator.

---

## D10. Uncertainty, mitigation and contingency

Risk management is incomplete without understanding _uncertainty_—its origins, implications, and strategies to reduce or absorb its impact. This section covers sources of uncertainty, techniques for quantifying it, and two essential risk response strategies: **mitigation** and **contingency**.

---

### 🌫️ Understanding Uncertainty

**Uncertainty** is the absence of complete certainty about future events or conditions that could impact a project. Unlike risk, which is quantifiable, uncertainty may not yet be fully understood or measurable.

**Common Sources of Uncertainty:**

- **Requirements**: Incomplete or evolving expectations
- **Human-System Interaction**: Unknowns in usability and operational integration
- **Changing Environment**: Shifting goals during the development timeline
- **Resource Availability**: Unpredictability in staffing and skills
- **Management Performance**: Team cohesion, coordination, and morale
- **Supply Chain**: Dependability of external partners
- **Politics**: Government or corporate decisions influencing scope or feasibility
- **Conflict**: Misalignment among stakeholder goals
- **Innovation**: New or experimental technologies
- **Scaling**: Risks introduced when moving beyond known operational scope

---

### 📐 Quantifying Uncertainty

**Challenge**: Project managers often forecast tasks that _must_ be done, but not tasks that _might_ be needed.

#### 🎯 Schedule Uncertainty

Release dates often fall within a **probability window**. Organizations with inconsistent processes have wider windows.

**Heuristic for software projects:**

- Best-case = N
- Realistic delivery = between N and the goal
- Published schedule = outer limit

#### 🧩 Functional Uncertainty

Sometimes, the **delivery date is fixed**, but what gets delivered is flexible—functionality becomes the uncertain factor.

---

### 🛠️ Risk Response Strategies

| Strategy     | Description                                                                 |
| ------------ | --------------------------------------------------------------------------- |
| **Avoid**    | Don’t do the task that entails the risk. You lose potential benefits.       |
| **Contain**  | Set aside buffer (time, money) to absorb the impact if the risk happens.    |
| **Mitigate** | Take actions beforehand to reduce either the probability or cost of a risk. |
| **Evade**    | Let the risk expire or resolve itself without incurring cost.               |

---

### 🔁 Mitigation vs Contingency

| Aspect                 | **Mitigation Plan** (First‑line Defense)            | **Contingency Plan** (Fallback)                         |
| ---------------------- | --------------------------------------------------- | ------------------------------------------------------- |
| **When you act**       | _Before_ the risk happens                           | _Only if_ warning signs appear or the risk materializes |
| **Primary objective**  | Reduce **probability and/or impact**                | **Control remaining impact** once the risk is imminent  |
| **Investment pattern** | Up‑front cost (time, money, tooling)                | Reserve cost (buffer) held in escrow                    |
| **Typical artefacts**  | Spike, prototype, automated tests, pair programming | Runbook, hot‑fix branch, extra cloud capacity           |
| **Effect on reserves** | Lowers required risk reserve                        | Consumes part of reserve                                |

> **Tip:** Mitigation is your first line of defense. Contingency is your fallback plan.

📝 Nota (ES):

- **Mitigación** = “prevenir o reducir impacto/probabilidad” (trabajo _up‑front_).
- **Contingencia** = “plan B” listo para activarse si la cosa se complica.

💻 Dev‑Note: piensa en **tests automatizados** (mitigación) vs. **feature‑flag para rollback rápido** (contingencia).

---

### 💰 Risk Reserve

A **risk reserve** is a buffer of time and money **set aside** to contain materialized risks.

**Best practice (PMBOK 7):**

1. **Identify** threats & opportunities.
2. **Quantify** exposure (EMV) and choose a confidence level (e.g., 80 %).
3. Create a **Contingency Reserve** for known‑unknowns (usually tied to WBS work packages).
4. Add a **Management Reserve** for unknown‑unknowns (controlled at portfolio/steering level).
5. Review reserves at each major baseline change.

> More defensive = allocate more than expected exposure  
> Less defensive = allocate less than expected exposure

**Mitigation reduces required reserves, but introduces fixed upfront costs.**

🔍 **Ejemplo:** Tu equipo guarda 3 días de buffer en el sprint. Tras añadir tests de contrato (mitigación) el buffer se reduce a 1 día, pero ya no necesitas tantas horas de soporte durante el release.

🧠 Deep Dive

- **Schedule Reserve** ≈ buffer in days/weeks; **Budget Reserve** ≈ monetary buffer.
- Agile teams often track reserve as **“Velocity × Buffer %”** inside the release burndown.

---

### 🧭 Transition Indicators

For each managed risk:

- Choose **early warning signals**
- Accept **some false positives**
- Balance **cost of early action vs. cost of delay**

---

### 💡 Real-World Examples of Risk Mitigation

#### 1. **Estimation & Scheduling**

- Involve team in estimation
- Work in short iterations to improve velocity transparency
- Monitor and apply lessons from current projects

#### 2. **Requirements Inflation**

- Involve customers early
- Use iterative reprioritization instead of blocking changes

#### 3. **Employee Turnover**

- Apply pair programming, shared code ownership, team rituals
- Create a culture that retains talent

#### 4. **Specification Breakdown**

- Use a product manager or proxy
- Run JAD (Joint Application Design) sessions to enhance specifications

#### 5. **Poor Productivity**

- Time-box with short sprints
- Stick to realistic schedules
- Use small, focused teams

#### 6. **Budget Overrun**

- Use rolling-wave planning to avoid front-loading decisions
- Expect and manage pivots during product evolution

#### 7. **Knowledge Silos**

- Use squad-based development
- Encourage documentation, shared ownership, and mentoring

---

### 🧨 Common Procedural Risks

- **Design shortcuts**: Skipping detailed design wastes time later
- **Gold plating**: Adding unneeded features burns budget
- **Reduced functionality**: Trimming scope to meet deadlines can hurt quality
- **Operational misalignment**: Poor process clarity or conflicting roles slow execution

---

### ✅ Key Takeaways

- Uncertainty is inevitable—don’t ignore it, plan for it
- Use both mitigation (prevention) and contingency (response)
- Keep risk reserves proportional to project size and risk profile
- Transition indicators should trigger risk responses early
- Address root causes in estimation, knowledge sharing, and requirements clarity

---

### 🧠 Deep Dive – D10 References & Techniques

- **Schedule Risk Analysis** (PERT β‑distribution, Monte Carlo) to model release‑date windows.
- **Continuous Delivery** reduces containment cost by making rollback cheap and fast.
- **Feature Flags & Canary Releases**: real‑time mitigation + built‑in contingency.
- **SRE Error Budgets**: quantify acceptable uncertainty in reliability vs. change velocity.

---

## Bibliography

- **Waltzing with Bears: Managing Risk on Software Projects**  
  *by Tom Demarco, Timothy Lister*  
  Addison Wesley Professional, 2013
