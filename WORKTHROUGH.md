## Part 1: Chapters 1–7 Comprehensive Review

Since Chapters 1–7 are tested via **Multiple Choice Questions (MCQ)** and **Integration Questions**, your goal is sharp conceptual recognition, identifying common traps, and mastering the core logic.

### Chapter 1: Introduction to Project Management

* **Project vs. Operations:** Projects are temporary, unique, and have definite start/end dates. Operations are ongoing and repetitive.
* **The Triple Constraint:** Scope, Time, and Cost. (Quality is often placed in the center, affected by changes to any of the three).
* **Program vs. Portfolio:**
* *Program:* A group of *related* projects managed together to achieve synergies/benefits you wouldn't get managing them individually.
* *Portfolio:* A collection of projects, programs, and operations grouped together to achieve *strategic business goals* (they do not have to be directly related).



### Chapter 2: The IT Context & Organizational Frames

* **Systems View:** Looking at the big picture. Composed of systems philosophy, systems analysis, and systems management.
* **The 4 Organizational Frames:**
* *Structural:* Roles, responsibilities, charts, and coordination.
* *Human Resources:* Meeting the needs of people and balancing stakeholder goals.
* *Political:* Coalitions, conflicts, power struggles, and resource allocation.
* *Symbolic:* Culture, traditions, rituals, meaning, and dress codes.


* **Organizational Structures:**
* *Functional:* Standard corporate ladder (Silos). Functional managers hold all the power. PMs have little to no authority.
* *Project-Oriented (Projectized):* Staff belong to projects. PMs have total independence and power. "No home" for staff when the project ends.
* *Matrix (Weak, Balanced, Strong):* Personnel report to both a functional manager and a PM. In a **Strong Matrix**, the PM holds the power. In a **Weak Matrix**, the functional manager holds the power (PM acts as a coordinator).



### Chapter 3 & 4: Process Groups & Project Integration Management

* **The 5 Process Groups:** Initiating $\rightarrow$ Planning $\rightarrow$ Executing $\rightarrow$ Monitoring & Controlling $\rightarrow$ Closing. (Note: These are *not* sequential project phases; they overlap throughout the project lifecycle).
* **Project Charter:** Formally authorizes the project and gives the PM authority to use organizational resources. **Signed by the Sponsor**, not the PM.
* **Integrated Change Control:** Managing changes across the entire project lifecycle.
* **Change Control Board (CCB):** A formal group responsible for approving or rejecting changes.
* > **MCQ Trap:** A PM can *never* just approve a major baseline change on their own. It must go through a formal change request and be evaluated for its impact on all constraints (Scope, Time, Cost, Quality) before heading to the CCB.





### Chapter 5: Project Scope Management

* **Work Breakdown Structure (WBS):** A deliverable-oriented decomposition of the total scope of work.
* **The 100% Rule:** The WBS must represent 100% of the work required by the project scope statement, and *only* the required work. No more, no less.
* **Work Package:** The lowest level of the WBS where cost and schedule can be reliably estimated.


* **Scope Creep vs. Gold Plating:**
* *Scope Creep:* Uncontrolled expansion of scope without adjustments to time, cost, or resources.
* *Gold Plating:* Giving the client extra features or higher quality *intentionally* without approval (highly discouraged in PM).



### Chapter 6: Project Schedule Management

* **Precedence Diagramming Method (PDM) / Activity-On-Node (AON):**
* *Finish-to-Start (FS):* Task B can't start until Task A finishes (Most common).
* *Start-to-Start (SS):* Task B can't start until Task A starts.
* *Finish-to-Finish (FF):* Task B can't finish until Task A finishes.


* **Critical Path Method (CPM):** The longest sequence of dependent tasks that determines the shortest possible project duration.
* **Float/Slack:** The amount of time a task can be delayed without delaying the project finish date. Tasks on the critical path have **zero float**.


* **Schedule Compression Techniques:**
* *Crashing:* Adding resources to tasks to shorten duration. **Increases Cost.**
* *Fast-Tracking:* Performing phases or tasks in parallel that would normally be done sequentially. **Increases Risk.**



### Chapter 7: Project Cost Management

* **Types of Cost Estimates:**
* *Rough Order of Magnitude (ROM):* Done very early (Initiating). Accuracy: -50% to +100%.
* *Budgetary:* Used to allocate money into plans (Planning). Accuracy: -10% to +25%.
* *Definitive:* Done right before execution. Accuracy: -5% to +10%.



#### Earned Value Management (EVM) Cheat Sheet

You will almost certainly see standard calculations here for MCQs.

| Metric | Formula | What It Tells You |
| --- | --- | --- |
| **Cost Variance (CV)** | $$CV = EV - AC$$

 | Negative is bad (over budget), Positive is good. |
| **Schedule Variance (SV)** | $$SV = EV - PV$$

 | Negative is bad (behind schedule), Positive is good. |
| **Cost Performance Index (CPI)** | $$CPI = \frac{EV}{AC}$$

 | Below 1.0 is bad ($0.85 means getting 85 cents of value per dollar spent). |
| **Schedule Performance Index (SPI)** | $$SPI = \frac{EV}{PV}$$

 | Below 1.0 is bad (behind schedule). |
| **Estimate at Completion (EAC)** | $$EAC = \frac{BAC}{CPI}$$

 | What the project will ultimately cost based on current performance. |

---

## Part 2 Strategy: The `llms.txt` Context Structure

To make sure your AI provides blisteringly fast, highly accurate answers for Part 2 without hallucinating, use an `llms.txt` prompt block. Copy and paste the structural prompt layout below directly into your AI assistant at the start of your session:

```markdown
# llms.txt - IT Project Management Exam Assistant Profile
## System Context & Parameters
- Framework Textbook: Schwalbe (Information Technology Project Management)
- Grading Persona: Academic, strict PM discipline, IT-focused application
- Scope: Chapters 8-12 + Scrum Essentials

## Core Rules & Constraints to Enforce
1. Chapter 8 (Quality): Enforce the strict Cost of Quality framework. Formula: (Prevention + Appraisal) ÷ (Internal Failure + External Failure). Categorize expenditures cleanly.
2. Chapter 9 (HR & Motivation): Enforce Tuckman stages (Forming, Storming, Norming, Performing). Explicitly watch for regression patterns to Storming. RACI matrices MUST have exactly ONE 'A' (Accountable) per activity and at least one 'R' (Responsible). Salary must ALWAYS be categorized as a Herzberg Hygiene factor, never a Motivator.
3. Chapter 10 (Communications): Calculate channels using n(n-1)/2. Apply to expanded groups accurately. Map stakeholders to 2x2 Power/Interest matrix strategies: Manage Closely, Keep Satisfied, Keep Informed, Monitor.
4. Chapter 11 (Risk): Maintain distinct strategies for Negative Risks (Avoid, Mitigate, Transfer, Accept) and Positive Risks (Exploit, Enhance, Share, Accept).
5. Chapter 12 (Procurement): Align FFP contracts to low buyer risk/high scope definition, T&M to staff-augmentation/hourly, and CR to high-risk R&D.
6. Scrum Essentials: Protect the distinct responsibilities of the Product Owner, Scrum Master, and Dev Team. Rely on the 3 Pillars (Transparency, Inspection, Adaptation) and Definition of Done (DoD).

## Response Formatting Style
- Start answers with a direct, unambiguous response or matrix mapping.
- Provide step-by-step mathematical calculations where formulas apply.
- Use bullet points for structural, scannable breakdowns.

```

---

## Free, No-Login AI Tool Suggestion

For maximum speed, accuracy, and Zero-Friction (no login or registration constraints), use **DuckDuckGo AI Chat** at **[duck.ai](https://duck.ai)**.

### Why it fits your exam constraints:

* **Completely Free & No Login:** You don't have to waste time logging in or worrying about sessions logging out mid-exam.
* **Frontier Light Models:** It lets you toggle between top-tier models like **GPT-4o mini** and **Claude 4.5 Haiku** completely free.
* **Speed:** Because it serves lightweight variations of mainstream engines, responses return with incredibly low latency.
* **Privacy:** It strips your metadata and queries the backend engines anonymously, meaning it won't store your prompt history on a public profile.
