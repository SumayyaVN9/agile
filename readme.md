# Module I: Agile Basics & Software Product Lifecycle

## Table of Contents
- [Software Product Lifecycle](#software-product-lifecycle)
- [Traditional Software Development](#traditional-software-development)
- [Agile Software Development](#agile-software-development)
- [Agile Manifesto](#agile-manifesto)
- [Agile Frameworks](#agile-frameworks)
- [Lean Software Development](#lean-software-development)
- [Iterative & Incremental Development](#iterative--incremental-development)
- [Agile vs Waterfall](#agile-vs-waterfall)
- [Exam Preparation](#exam-preparation)

---

## Software Product Lifecycle

The **Software Product Lifecycle** describes the stages a software product goes through from conception to retirement.

### Key Stages

1. **Concept / Need Identification** – Recognizing a problem or requirement
2. **Requirements Gathering** – Understanding what the user wants
3. **Design** – Creating architecture, UI, system structure
4. **Development** – Writing and building the software
5. **Testing** – Ensuring the software works correctly
6. **Deployment** – Delivering/releasing the software to users
7. **Maintenance / Updates** – Fixing bugs, improving features
8. **Retirement** – End-of-life when the product is no longer useful

### Example: Instagram
New feature idea → Design → Develop → Release → Update regularly → Old features retired

---

## Traditional Software Development

Traditional methods focus on **planning everything upfront**.

### Waterfall Model

A **linear, step-by-step methodology** where each phase must finish before the next begins.

```
Requirements → Design → Development → Testing → Deployment → Maintenance
```

#### Advantages
- Simple and structured approach
- Works well for stable, clear requirements
- High predictability for scope, schedule, and budget
- Strong documentation helps with maintenance

#### Disadvantages ⚠️
- **Not flexible** – hard to accommodate requirement changes
- Late testing means issues found very late
- User feedback comes only after completion
- Changes during later phases are difficult and costly
- Less frequent client involvement during development

#### When to Use Waterfall
- Requirements are clear, fixed, and unlikely to change
- Well-known domain with low risk of change
- Strong documentation is required (regulatory systems, auditing)

> **Key Takeaway:** Waterfall is not suitable for fast-changing environments.

---

## Agile Software Development

Agile is a **flexible, iterative** approach where software is delivered **in small parts** and **improved continuously** with customer feedback.

### Key Characteristics
- Short development cycles called **iterations** or **sprints**
- Continuous user feedback
- Frequent releases
- Strong team collaboration
- Cross-functional, self-organizing teams
- Adaptability to change

### Core Philosophy
> *Deliver small working software quickly, improve based on feedback.*

### When to Use Agile
- Requirements are unclear or likely to change
- Dynamic environment (startups, web/mobile apps)
- Need to deliver value quickly and iterate based on real-user feedback
- Team can collaborate closely and adapt rapidly

---

## Agile Manifesto

The **Agile Manifesto** (created in 2001 by 17 software developers) expresses the core **values** of agile development.

### The 4 Core Values

<p align="center">
  <img src="Module-1-images/4-Values-of-Agile-Manifesto-for-Software-Development.jpg" alt="Agile Manifesto Values" width="700"/>
</p>

| Agile Values (Priority) | Over (Secondary Focus) |
|------------------------|------------------------|
| **Individuals and interactions** | Processes and tools |
| **Working software** | Comprehensive documentation |
| **Customer collaboration** | Contract negotiation |
| **Responding to change** | Following a fixed plan |

> **Note:** These values mean we prioritize the items on the left MORE than the items on the right. The items on the right still have value.

### Understanding Each Value

#### 1. Individuals and Interactions > Processes and Tools
- **Priority:** People, communication, collaboration, and problem-solving abilities
- **Rationale:** People can adapt, innovate, and solve unexpected problems in real-time
- **Secondary:** Processes and tools support the team but shouldn't control them

#### 2. Working Software > Comprehensive Documentation
- **Priority:** Delivering functional software as the primary measure of progress
- **Rationale:** Build in short cycles, gather feedback, improve continuously
- **Secondary:** Documentation is helpful but shouldn't delay development

#### 3. Customer Collaboration > Contract Negotiation
- **Priority:** Ongoing working relationship with customers as active collaborators
- **Rationale:** Show progress frequently, get feedback, adjust to evolving needs
- **Secondary:** Contracts set basic expectations but can't predict every detail

#### 4. Responding to Change > Following a Plan
- **Priority:** Embracing new requirements or feedback, even late in the project
- **Rationale:** Markets shift, new ideas emerge, assumptions change – adapt quickly
- **Secondary:** Plans are helpful roadmaps but should be dynamic, not unchangeable

> ✅ **Exam Alert:** This is one of the most repeated exam questions!

---

## Agile Frameworks

Agile is a mindset with multiple **frameworks** to implement it:

| Framework | Focus | Key Feature |
|-----------|-------|-------------|
| **Scrum** | Project management | Sprints, roles, ceremonies |
| **Kanban** | Workflow optimization | Visual board, WIP limits |
| **XP (Extreme Programming)** | High-quality code | Pair programming, TDD |

---

## Lean Software Development

Lean Software Development (LSD) originates from **Toyota manufacturing** principles and focuses on **optimizing efficiency and minimizing waste**.

### What is LSD?
An approach aimed at:
- **Preventing defects** through integrated quality assurance
- **Eliminating waste** by focusing on value-adding activities
- **Fast delivery** with reduced cycle times
- **Delaying decisions** until facts are available

### The 7 Lean Principles

<p align="center">
  <img src="Module-1-images/7-Principles-of-Lean-Software-Development.jpg" alt="7 Principles of Lean Software Development" width="700"/>
</p>

#### 1. Eliminate Waste
- **Focus:** Remove anything that doesn't add customer value
- **Examples:** Unnecessary code, long delays, unclear communication, extra work
- **Practice:** Regular meetings to identify issues and suggest improvements
- **Example:** Removing unused features, automating repetitive tasks

#### 2. Build Quality In
- **Focus:** Check quality from the beginning, not just at the end
- **Practice:** Test-Driven Development (TDD), automated testing
- **Benefit:** Identify and fix problems early, reduce rework
- **Example:** Run automated tests with every code change

#### 3. Amplify Learning
- **Focus:** Keep learning throughout the project
- **Practice:** Code reviews, meetings, pair programming, knowledge sharing
- **Benefit:** Knowledge distributed across the team
- **Example:** Two developers working together on a task

#### 4. Deliver Fast
- **Focus:** Build and release Minimum Viable Product (MVP) quickly
- **Practice:** Short cycles, early releases, gather feedback
- **Benefit:** Learn and improve faster
- **Example:** Launch simple app version, collect feedback, add features

#### 5. Empower the Team
- **Focus:** Trust and support self-organizing teams
- **Practice:** Respect, motivation, decision-making authority
- **Benefit:** Increased creativity and motivation
- **Example:** Team members make decisions about their own work

#### 6. Optimize the Whole
- **Focus:** View project holistically, not just individual tasks
- **Practice:** Break big problems into smaller parts, cross-functional collaboration
- **Benefit:** Better teamwork, unity, overall performance
- **Example:** Developers, testers, designers working together from the start

#### 7. Defer Commitment
- **Focus:** Wait for sufficient information before big decisions
- **Practice:** Flexible architecture, delay decisions until facts are clear
- **Benefit:** Avoid mistakes and wasted effort
- **Example:** Wait to choose database system until performance needs are known

> ⚠️ **Exam Alert:** "Explain any two Lean Software Development Principles" is a common 2-mark question.

---

## Iterative & Incremental Development

In Agile, **Iterative** and **Incremental** approaches work together for continuous improvement and faster delivery.

<p align="center">
  <img src="Module-1-images/incremental-vs-iterative.png" alt="Iterative vs Incremental Development" width="650"/>
</p>

### 🌀 Iterative Development

**Definition:** Project developed through **repeated cycles (iterations)**

**Process:** Each iteration involves planning, designing, coding, testing, and reviewing

**Goal:** **Refine and improve** the product step by step based on feedback

**Focus:** Improving the same part repeatedly until it's perfect

**Example:** Gmail Interface Evolution
- Started with basic email features (2004)
- Iterated by adding:
  - Conversation view (threaded emails)
  - Redesigned UI for better navigation
  - Dark mode, smart reply, AI suggestions
- Each version improved the core system based on user feedback

### 🧩 Incremental Development

**Definition:** Project built **piece by piece (in increments)**

**Process:** Each increment adds a **new functional feature**

**Goal:** Deliver **usable parts** early and expand functionality over time

**Focus:** Adding new features step by step until complete

**Example:** Spotify's Feature Evolution
1. Music playback and search
2. Playlist creation
3. Offline mode
4. Social sharing and collaborative playlists
5. Podcasts and video support

### Combined Approach in Agile

| Approach | What It Does | Example |
|----------|--------------|---------|
| **Iterative** | Improves existing parts repeatedly | Redesign login UI over 3 sprints |
| **Incremental** | Adds new parts step by step | Add login → profile → chat feature |
| **Combined (Agile)** | Build and improve features continuously | Deliver working app early, enhance every sprint |

> 🚀 **Key Insight:** Agile develops **incrementally** (adding features) and **iteratively** (refining them).

---

## Agile vs Waterfall

<p align="center">
  <img src="Module-1-images/waterfall-vs-agile.webp" alt="Waterfall vs Agile Comparison" width="750"/>
</p>

### Side-by-Side Comparison

| Feature | Waterfall | Agile |
|---------|-----------|-------|
| **Process Structure** | Linear, phase-by-phase | Iterative, incremental cycles |
| **Requirements** | Fixed early, changes difficult | Evolving; change expected |
| **Customer Involvement** | Mostly at start and end | Continuous involvement |
| **Delivery** | Big release at the end | Frequent small releases |
| **Team Approach** | Hierarchical, specialized roles | Cross-functional, self-organizing |
| **Documentation** | Heavy documentation upfront | Lighter documentation, more working software |
| **Predictability** | High (when stable) | Lower (changes likely) |
| **Flexibility** | Poor – hard to accommodate changes | Very flexible – changes at many points |
| **Feedback** | Late feedback | Fast, continuous feedback |
| **Best For** | Stable requirements & predictable context | Dynamic contexts & evolving needs |

### When to Choose Which?

**Choose Waterfall when:**
- Requirements are clear, fixed, and stable
- Well-known domain with low change risk
- Strong documentation required (regulatory, safety)
- Predictable budget and timeline are critical

**Choose Agile when:**
- Requirements unclear or likely to change
- Dynamic environment (startups, web/mobile apps)
- Need quick value delivery with user feedback
- Team can collaborate closely and adapt rapidly

---

## Exam Preparation

### Quick Last-Minute Notes

- **Traditional:** Fixed plan, slow feedback
- **Agile:** Flexible, customer-focused, iterative
- **Agile Manifesto:** 4 core value pairs (must memorize)
- **Lean:** Eliminate waste + continuous improvement

### Expected Exam Questions

| Question | Marks |
|----------|-------|
| Explain Agile Manifesto values | 5 |
| Discuss Iterative & Incremental development | 2/5 |
| What is Lean Software Development? Explain any two principles | 2/5 |
| Compare Agile and Waterfall | 5 |
| Explain the Software Product Lifecycle | 5 |
| Advantages and disadvantages of Waterfall model | 5 |

### Key Topics to Focus On

1. ✅ **Agile Manifesto 4 Values** – Most repeated exam question
2. ✅ **Lean Principles** – Especially "any two principles" questions
3. ✅ **Waterfall Disadvantages** – Very important to understand
4. ✅ **Iterative vs Incremental** – Know the difference with examples
5. ✅ **Agile vs Waterfall Comparison** – Understand when to use each

---


# Module 2 - Kanban Principles & Practices

| No.   | Question                                                                                          | Why Important / Exam Trend                                                      |
| ----- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **1** | **Explain the Kanban board with a neat diagram. Describe the workflow.**                          | **Repeated every year**, scoring question — draw 3-column board for full marks. |
| **2** | **What are WIP limits? Explain their importance in Kanban.**                                      | Short + Long repeated question. Easy scoring.                                   |
| **3** | **Differentiate between Lead Time and Cycle Time with examples.**                                 | Very frequently asked as 2 marks / 5 marks.                                     |
| **4** | **Explain Cumulative Flow Diagram (CFD) and how it helps in identifying bottlenecks.**            | High scoring 5-mark question.                                                   |
| **5** | **Explain the principles of Kanban.**                                                             | Direct theory question, often asked.                                            |
| **6** | **Discuss 'Continuous Improvement (Kaizen)' in Kanban.**                                          | Common 5-mark conceptual question.                                              |
| **7** | **Compare Scrum and Kanban.**                                                                     | Frequently asked in Part B (5 marks).                                           |
| **8** | **Illustrate a Kanban workflow model for a support / food delivery / student management system.** | **Case-based question** → Can come in Part C (10 marks).                        |


10 or 5 mark questions 

1) Kanban Board + Diagram + Workflow
2) WIP Limits (Definition + Purpose + Example)
3) Lead Time vs Cycle Time + CFDs
4) Case Study: Draw a Kanban board for any real-life system


🎯 Short Notes That Also Come Frequently (2 Marks)

Define Kanban

Pull system vs Push system

Kaizen

Throughput


---

## 🧭 What is Kanban?

**Kanban** is an **Agile methodology** used to manage and improve workflow efficiently.
It helps teams **visualize their work**, **limit tasks in progress**, and **focus on continuous delivery** rather than big releases.

In short:

> **Kanban = Visual + Continuous + Flow-based project management**

---

## 🧩 Origin

Kanban was originally developed by **Toyota** in the 1940s for **manufacturing** — to track car parts in production.
Later, it was adapted for **software development** and **project management**.

---

## 🪧 The Kanban Board
![Kanban - Board](Module-2-Images/Kanban-board-1.png)
At the heart of Kanban is the **Kanban Board**, which visually represents the progress of work.
It’s divided into columns, usually like this:

| To Do              | In Progress           | Testing            | Done            |
| :----------------- | :-------------------- | :----------------- | :-------------- |
| Tasks yet to start | Tasks being worked on | Tasks under review | Completed tasks |

Each task is represented by a **card** (physical sticky note or digital card like in Trello/Jira).

---

## ⚙️ How Kanban Works

1. **Visualize Work**
   Every task is placed on a Kanban board as a card.
   → Example: “Design homepage,” “Fix login bug,” “Write API documentation.”

2. **Limit Work in Progress (WIP)**
   You set a limit for how many tasks can be in progress at once.
   → Example: “Only 3 tasks can be ‘In Progress’ at a time.”
   This prevents overloading and ensures focus.

3. **Manage Flow**
   As tasks move from left to right (To Do → In Progress → Done), the team tracks progress and removes bottlenecks.
   → Example: If “Testing” always has many stuck tasks, the issue might be with QA capacity.

4. **Make Process Policies Explicit**
   The team agrees on clear rules.
   → Example: “A task can move to ‘Testing’ only after code review.”

5. **Implement Feedback Loops**
   Daily stand-ups or review meetings are used to discuss issues and improve flow.

6. **Continuous Improvement (Kaizen)**
   The team regularly reviews the board and process to improve efficiency and delivery speed.

---

## 🧠 Example — Simple Software Team

Imagine a small app development team working on a weather app.

| To Do                | In Progress                   | Testing            | Done                |
| -------------------- | ----------------------------- | ------------------ | ------------------- |
| Create login screen  | Build API for weather data    | Fix search bar bug | Set up project repo |
| Add location feature | Design UI for forecast screen |                    |                     |

**Workflow:**

* When “Build API for weather data” is done, it moves to “Testing”.
* “Design UI for forecast screen” can’t start until there’s a free slot in “In Progress” (WIP limit = 2).
* Once testing is passed, tasks go to “Done”.

This keeps the workflow smooth and balanced.

---

## 💡 Key Principles of Kanban

1. **Visualize your workflow** — use a board.
2. **Limit work in progress (WIP)** — prevent overload.
3. **Focus on flow** — ensure tasks move smoothly.
4. **Continuous improvement** — review, adapt, improve.

---

## 🧰 Tools for Kanban

* **Trello**
* **Jira**
* **Asana (with Kanban view)**
* **GitHub Projects**

---

## ✅ Advantages of Kanban

* Simple and visual — easy to understand.
* Flexible — no strict roles or sprints.
* Great for continuous delivery projects.
* Encourages teamwork and transparency.

---

## ⚠️ Limitations

* Hard to predict timelines (since it’s flow-based).
* Needs disciplined team members to update cards regularly.

---

### 🔍 In Short

| Aspect      | Kanban Summary                                  |
| ----------- | ----------------------------------------------- |
| Focus       | Continuous delivery and workflow management     |
| Board       | Visual tool with columns for stages             |
| Planning    | No fixed iterations (unlike Scrum)              |
| Flexibility | Very high                                       |
| Best For    | Support, DevOps, or teams with frequent changes |

---

### 💬 Real-Life Example

Let’s say your **college project** involves three teammates:

* One designs UI
* One codes backend
* One tests features

Using a Kanban board, you can track who’s doing what, see what’s pending, and easily spot delays — like “Testing is stuck because backend isn’t ready.”

---


