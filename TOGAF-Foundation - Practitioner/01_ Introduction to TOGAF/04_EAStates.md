## 🧱 TOGAF® Architecture States (Complete Overview)

TOGAF recognizes multiple **Architecture States** to help Enterprise Architects manage **current, evolving, and future** views of the enterprise. These states are used across the **Architecture Development Method (ADM)** to define, govern, and transition architectures.

---

### 📘 Complete List of Architecture States

| **State**                      | **Description**                                                                                                                                       |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🟦 **Baseline Architecture**   | The **current state** (“as-is”) of the enterprise. Used as a **starting point** for planning change.                                                  |
| 🟨 **Resting Architecture**    | A **stable, value-generating state** of the enterprise where change is **paused** or complete. It could be the Baseline or a Transition architecture. |
| 🟧 **Candidate Architecture**  | A **proposed future state**, not yet formally reviewed or approved by stakeholders. Still exploratory.                                                |
| 🟩 **Transition Architecture** | A **planned intermediate future state** that delivers **partial capabilities** on the path to the Target Architecture.                                |
| 🟪 **Target Architecture**     | The **approved future state**, representing the long-term vision aligned with strategy and stakeholder agreement.                                     |

---

### 🔁 Architecture State Progression Diagram

```text
                 [Baseline Architecture]
                          │
                          ▼
                 [Candidate Architecture]
                          ▼
               [Transition Architecture(s)]
                   │             │
                   ▼             ▼
         [Resting Architecture] (optional)
                          ▼
                 [Target Architecture]
```

---

### 🟨 What is **Resting Architecture**?

> A **Resting Architecture** is any **approved and deployed architecture** (baseline or transition) that **delivers business value** and can be **sustained without active change**.

📝 **TOGAF Usage**:

* It's often used in **multi-phase transformations** (e.g., each Transition Architecture becomes a temporary "resting" state).
* Represents a state where the enterprise **pauses** major architecture evolution but still functions effectively.

**Example:**

> After Phase 1 of a transformation (e.g., moving to microservices), the organization pauses further changes. This **deployed transition architecture** becomes a **Resting Architecture** until Phase 2 begins.

---

### 🧾 Summary Table with Resting Architecture

| **Architecture State** | **TOGAF Role**                                              | **Approved?** | **Purpose**                                  |
| ---------------------- | ----------------------------------------------------------- | ------------- | -------------------------------------------- |
| **Baseline**           | Current “as-is” state                                       | ✅             | Starting point for change                    |
| **Resting**            | Temporarily paused or sustained future state                | ✅             | Stable value delivery without ongoing change |
| **Candidate**          | Proposed future state, under review                         | ❌             | Option or draft for future decision          |
| **Transition**         | In-progress state that delivers partial target capabilities | ✅             | Planned step in change journey               |
| **Target**             | Final agreed-upon “to-be” architecture                      | ✅             | Strategic end goal for transformation        |

---

## ✅ Use in TOGAF ADM Phases

| ADM Phase | Common Architecture States Used                            |
| --------- | ---------------------------------------------------------- |
| Phase A   | Baseline, Candidate                                        |
| Phase B–D | Candidate, Transition, Target                              |
| Phase E–F | Transition, Target, Resting (as implementation milestones) |
| Phase G–H | Resting (architecture governance and operations)           |

---

### 💡 Quick Analogy

| State          | Analogy: Building a Smart City                            |
| -------------- | --------------------------------------------------------- |
| **Baseline**   | The current city map                                      |
| **Candidate**  | Sketch of a future smart district                         |
| **Transition** | Smart traffic system deployed in one area                 |
| **Resting**    | City operates well with current systems before next phase |
| **Target**     | Full smart city with all systems integrated and deployed  |

---


