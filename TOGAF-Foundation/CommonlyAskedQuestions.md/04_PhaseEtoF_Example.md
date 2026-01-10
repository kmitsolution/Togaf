# **📘 Real-World Example: Phase E → Phase F Mapping**

## **Scenario**

A **retail company** wants to move from:

* Legacy on-premise systems
  to
* A **cloud-based digital commerce platform**

They have already completed **Phases B, C, and D** and identified gaps.

---

## **🔹 Phase E – Opportunities & Solutions (WHAT to do)**

### **1️⃣ Identify Solution Options**

**Problem:** Legacy ERP, siloed CRM, slow deployments

**Options considered:**

* Build custom ERP ❌
* Buy SaaS ERP ✅
* Reuse existing CRM ✅
* Introduce cloud infrastructure ✅

👉 **Artifact:** *Solution Options Analysis*

---

### **2️⃣ Define Solution Building Blocks (SBBs)**

Chosen SBBs:

* SaaS ERP
* Cloud CRM
* API Integration Layer
* Cloud Infrastructure

👉 **Artifact:** *Solution Building Blocks list*

---

### **3️⃣ Group Changes into Work Packages**

Work Packages created:

* WP1: ERP implementation
* WP2: CRM integration
* WP3: Data migration
* WP4: Legacy system retirement

👉 **Artifact:** *Work Package Definitions*

---

### **4️⃣ Define High-Level Transition Architecture**

Transition State:

* Legacy ERP + New SaaS ERP running in parallel
* Data synchronized temporarily

👉 **Artifact:** *Transition Architecture (High-level)*

---

### **5️⃣ Initial Architecture Roadmap**

* No dates yet
* Only logical grouping of work

👉 **Artifact:** *Initial Architecture Roadmap*

---

📌 **At the end of Phase E**
✔ We know **WHAT** solutions exist
❌ We do NOT know exact timelines or sequence

---

## **🔹 Phase F – Migration Planning (WHEN & ORDER)**

### **6️⃣ Prioritize Work Packages**

Evaluation criteria:

* Business value
* Risk
* Cost
* Dependencies

| Work Package    | Value  | Risk   | Priority |
| --------------- | ------ | ------ | -------- |
| ERP             | High   | Medium | 1        |
| Data Migration  | Medium | High   | 2        |
| CRM Integration | Medium | Low    | 3        |

👉 **Artifact:** *Business Value Assessment Matrix*

---

### **7️⃣ Sequence Work Packages**

Dependencies:

* ERP must finish before Data Migration
* Data Migration before Legacy Retirement

👉 **Artifact:** *Work Package Dependency Matrix*

---

### **8️⃣ Refine Transition Architectures**

Now time-based:

* Month 0–6: Hybrid ERP
* Month 6–12: Cloud-only ERP

👉 **Artifact:** *Refined Transition Architecture*

---

### **9️⃣ Create Detailed Architecture Roadmap**

| Timeline | Activity        |
| -------- | --------------- |
| Q1–Q2    | ERP rollout     |
| Q3       | Data migration  |
| Q4       | Legacy shutdown |

👉 **Artifact:** *Detailed Architecture Roadmap*

---

### **🔟 Implementation & Migration Plan**

Includes:

* Schedule
* Resources
* Risks
* Cost estimates

👉 **Artifact:** *Implementation & Migration Plan*

---

## **📌 End-to-End Mapping Summary**

```
Phase E (WHAT)                    Phase F (WHEN & ORDER)
---------------------------------------------------------
Solution Options   ─────────▶  Prioritization
SBBs               ─────────▶  Sequencing
Work Packages      ─────────▶  Scheduling
Transition Ideas   ─────────▶  Time-based Transitions
High-level Roadmap ─────────▶  Detailed Roadmap
```

---

## **🧠 Practitioner One-Line Explanation**

> **Phase E decides what solutions and work packages are needed; Phase F converts them into a realistic, time-based migration plan.**

---

## **Exam Tip**

If the question mentions:

* *Options, work packages, transition ideas* → **Phase E**
* *Timeline, sequencing, roadmap, migration plan* → **Phase F**

---

