
---

## **📘 MODULE I – Agile Basics & Software Product Lifecycle**

---

### **1. Introduction to Software Product Lifecycle**

The **Software Product Lifecycle** describes the **stages a software product goes through** from idea to end-of-life.

**Stages:**

1. **Concept / Need Identification** – Recognizing a problem or requirement.
2. **Requirements Gathering** – Understanding what the user wants.
3. **Design** – Creating architecture, UI, system structure.
4. **Development** – Writing and building the software.
5. **Testing** – Ensuring the software works correctly.
6. **Deployment** – Delivering / releasing the software to users.
7. **Maintenance / Updates** – Fixing bugs, improving features.
8. **Retirement** – When the product is no longer useful, it is closed.

**Example:** Instagram

* New feature idea → Design → Develop → Release → Update regularly → Old features retired.

---

### **2. Traditional Approaches to Software Development**

Traditional methods focus on **planning everything upfront**.

#### **Waterfall Model**

* Linear, step-by-step method.
* Each phase must finish before the next starts.

```
Requirements → Design → Development → Testing → Deployment → Maintenance
```

**Advantages:**

* Simple and structured
* Works well for stable, clear requirements

**Disadvantages (very important):**

* **Not flexible** — hard to change requirements
* Late testing → Issues found very late
* User feedback comes only after completion

➡️ **Waterfall is not suitable for fast-changing environments.**

---

### **3. Overview of Agile Software Development**

Agile is a **flexible, iterative** approach where software is delivered **in small parts** and **improved continuously** with customer feedback.

**Key Characteristics:**

* Short development cycles called **iterations** / **sprints**
* Continuous user feedback
* Frequent releases
* Team collaboration

**Core Idea:**
👉 *Deliver small working software quickly, improve based on feedback.*

---

### **4. Agile Manifesto**

The **Agile Manifesto** expresses the **values** of agile development.

#### **4 Values:**

| Agile Prefers                    | Over                        |
| -------------------------------- | --------------------------- |
| **Individuals and interactions** | Processes and tools         |
| **Working software**             | Comprehensive documentation |
| **Customer collaboration**       | Contract negotiation        |
| **Responding to change**         | Following a fixed plan      |

✅ This is **one of the most repeated exam questions**.

---

### **5. Agile Development Frameworks**

Agile is a mindset — there are multiple **frameworks** to apply it:

| Framework                    | Focus                 | Key Feature                |
| ---------------------------- | --------------------- | -------------------------- |
| **Scrum**                    | Project management    | Sprints, roles, ceremonies |
| **Kanban**                   | Workflow optimization | Visual board, WIP limits   |
| **XP (Extreme Programming)** | High-quality code     | Pair programming, TDD      |

You don’t memorize details now—just know names & focus areas.

---

### **6. Lean Software Development (LSD)**

Lean originates from **Toyota manufacturing** and focuses on **reducing waste**.

#### **LSD Principles (VERY IMPORTANT)**:

1. **Eliminate Waste** – Remove anything not adding value.
2. **Build Quality In** – Continuous testing, code reviews.
3. **Amplify Learning** – Frequent feedback, adapt quickly.
4. **Deliver Fast** – Short cycles.
5. **Empower the Team** – Self-organizing teams.
6. **Optimize the Whole** – Improve end-to-end flow.
7. **Defer Commitment** – Make decisions when information is clear.

**Typical 2-mark Question:**
*Explain any two Lean Software Development Principles.*

---

## ✅ **Quick Last-Minute Notes**

* Traditional → fixed plan, slow feedback.
* Agile → flexible, customer-focused, iterative.
* Agile Manifesto → **4 core value pairs** (must memorize).
* Lean → **Eliminate waste + continuous improvement**.

---

## 📝 Expected Exam Questions (From Previous Patterns)

| Question                                                       | Marks |
| -------------------------------------------------------------- | ----- |
| Explain Agile Manifesto values.                                | 5     |
| Discuss Iterative & Incremental development.                   | 2 / 5 |
| What is Lean Software Development? Explain any two principles. | 2 / 5 |
| Compare Agile and Waterfall.                                   | 5     |

## Agile-manifesto Values

The Agile Manifesto, created in 2001 by 17 software developers, outlines four core values that prioritize adaptability, collaboration, and the delivery of value to the customer over rigid, traditional methods. The values are expressed as priorities: "we value the items on the left more than the items on the right".
 ![alt text](Module-1/4-Values-of-Agile-Manifesto-for-Software-Development.jpg)
The four values are:
1. Individuals and Interactions over Processes and Tools 
This value emphasizes that the people on a team and their ability to communicate and collaborate effectively are more important than the specific processes they follow or the tools they use. While processes and tools can provide structure, they are ineffective without motivated individuals who can communicate fluidly to respond to business needs and solve problems. 
Individuals and Interactions (The Priority): The focus is on the people involved in the project—developers, customers, and team members. Open communication, mutual respect, good collaboration, and the ability to talk through problems are the keys to success. People can adapt, innovate, and solve unexpected problems in real-time.
Processes and Tools (The Secondary Focus): While processes (like specific step-by-step guides) and tools (like project management software) are helpful for guidance and organization, they should not dictate how people work to the point of rigidity. They are there to support the team, not control them.

2. Working Software over Comprehensive Documentation
The Agile approach prioritizes the delivery of functional software to the customer as the primary measure of progress. Instead of spending excessive time creating extensive, detailed documentation before development begins (which can cause delays), Agile teams focus on producing working software in short cycles (iterations) and gathering feedback for continuous improvement. 
3. Customer Collaboration over Contract Negotiation 
This value highlights the importance of continuous engagement and communication with the customer throughout the development lifecycle. Rather than rigid contract negotiations at the beginning of a project, which can lead to mismatched expectations, Agile teams involve the customer as an active collaborator. This ensures the product truly meets their evolving needs and allows for changes to be incorporated easily. 
Customer Collaboration (The Priority): The focus is on an ongoing, working relationship where the customer is part of the team. You show them what you are building frequently, get their feedback, and make adjustments as you go. This ensures the final product is exactly what they need, even if their needs change over time.
Contract Negotiation (The Secondary Focus): A contract is important to set basic expectations and terms, but it can't predict every single detail or future change. If you stick only to the initial contract without talking to the customer, you might build exactly what the contract says, but it might be the wrong product by the time you finish.

4. Responding to Change over Following a Plan
Agile processes are designed to be flexible and adapt to changing requirements, even late in development, which is seen as a source of competitive advantage for the customer. Traditional methods viewed change as an expense to be avoided, but Agile embraces it. Plans and roadmaps are considered dynamic strategies that can be adjusted based on new information, rather than static, unchangeable documents
Responding to Change (The Priority): The focus is on embracing new requirements or feedback, even late in the project. Agile recognizes that things change: the market shifts, new ideas emerge, or initial assumptions prove incorrect. Being able to adapt quickly is a key advantage.
Following a Plan (The Secondary Focus): A plan is a helpful starting point and roadmap, but it shouldn't be treated as an unchangeable law. If new information suggests the original plan is no longer the best path, the team should update the plan rather than blindly following it off a cliff.


## Discuss Iterative & Incremental development.

In **Agile development**, the **Iterative** and **Incremental** approaches are two key concepts that work together to ensure continuous improvement and faster delivery. Let’s break them down clearly 👇

---
![Incremental vs iterative](Module-1/incremental-vs-iterative.png)
### 🌀 **Iterative Development**

* **Meaning:**
  The project is developed through **repeated cycles (iterations)**.
  Each iteration involves **planning, designing, coding, testing, and reviewing**.
* **Goal:**
  To **refine and improve** the product step by step based on **feedback** from users or stakeholders.
* **Example:**
  Suppose you’re building a **mobile app**.
  In the first iteration, you make a **basic version** of the login page.
  In the next iteration, you **improve its design**, add **error handling**, and so on.

✅ **Focus:** Improving the same part of the product repeatedly until it’s perfect.

---

### 🧩 **Incremental Development**

* **Meaning:**
  The project is built **piece by piece (in increments)**.
  Each increment adds a **new functional feature** to the system.
* **Goal:**
  To deliver **usable parts** of the software early and expand functionality over time.
* **Example:**
  First increment → login system
  Second increment → user profile
  Third increment → messaging feature

✅ **Focus:** Adding **new features** step by step until the full product is ready.

---

### 🚀 **How They Work Together in Agile**

Agile combines both:

* **Iterative:** Each feature is improved through multiple iterations.
* **Incremental:** New features are added in increments.

So, development happens **incrementally (adding features)** and **iteratively (refining them)**.

---

### 🧠 **Simple Summary**

| Approach         | What It Does                            | Example                                               |
| ---------------- | --------------------------------------- | ----------------------------------------------------- |
| Iterative        | Improves existing parts repeatedly      | Redesign login UI over 3 sprints                      |
| Incremental      | Adds new parts step by step             | Add login → profile → chat feature                    |
| Combined (Agile) | Build and improve features continuously | Deliver working app early and enhance it every sprint |

🌀 1. Iterative Development Example – Gmail’s Interface

When Google first launched Gmail (2004), it had only basic features — composing, sending, and receiving emails.
Over time, Google iterated on the same product by refining its design and performance.

Iterations included:

Adding conversation view (grouping emails in threads).

Redesigning the UI for better navigation.

Introducing dark mode, smart reply, and AI-based suggestions.

👉 Each new version was an improvement of the same core system, based on user feedback and testing.
This is iterative development — enhancing an existing feature through multiple cycles.

🧩 2. Incremental Development Example – Spotify’s Features

When Spotify was first released, it started with just music streaming.
Then, with each increment, new features were added:

Increment	Feature Added
1	Music playback and search
2	Playlist creation
3	Offline mode
4	Social sharing and collaborative playlists
5	Podcasts and video support

👉 Each new release added functional chunks that made the app more powerful and complete.
That’s incremental development — adding new features over time.


