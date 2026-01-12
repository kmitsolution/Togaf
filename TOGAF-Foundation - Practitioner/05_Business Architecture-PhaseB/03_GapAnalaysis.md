Here’s a clear, structured explanation of **TOGAF ADM Phase B – Business Architecture – Gap Analysis** based on what you provided:

---

### **Purpose of Gap Analysis**

Gap Analysis is performed to identify what must change in the enterprise to move from the **Baseline Architecture** (current state) to the **Target Architecture** (desired future state).

* **Definition of a Gap:** A shortfall between the Baseline and Target Architectures, including items that are:

  * Deliberately omitted
  * Accidentally left out
  * Not yet defined

* **Primary Source of Gaps:** Ignored or unaddressed stakeholder concerns.

* **Scope:** Gaps can exist in **any architecture domain** – business, data, application, or technology.

---

### **Gap Analysis Technique**

1. **Create a Gap Matrix**

   * Place **Target Architecture Building Blocks (ABBs)** on the horizontal axis.
   * Place **Baseline Architecture ABBs** on the vertical axis.
   * Add an extra **row labeled “New”** and an extra **column labeled “Eliminated.”**

2. **Populate the Matrix**

   **For each ABB in the Baseline Architecture:**

   * Check if it exists in the Target Architecture:

     * **Yes:** Record **“Included”** at the intersection.
     * **No:** Record **“Intentionally eliminated”** or **“Unintentionally eliminated.”**

   **For each ABB in the Target Architecture:**

   * Check if it exists in the Baseline Architecture:

     * **Yes:** Intersection already marked as **“Included.”**
     * **No:** Record the ABB in the **row “New.”**

3. **Identify Gaps**

   * Any entry in the **row “New”** or **column “Eliminated”** represents a gap between the Baseline and Target Architectures.

---

### **Summary**

* Gap Analysis helps **highlight missing or redundant components** and shows the steps required to **achieve the Target Architecture**.
* It ensures **stakeholder concerns are addressed** and provides a structured approach to **transition planning**.

---

 Let’s create a **sample Gap Analysis Matrix** for a Business Architecture scenario. I’ll use simple placeholders for **Architecture Building Blocks (ABBs)** to illustrate the concept.

---

### **Step 1: Define ABBs**

**Baseline Architecture ABBs (Current State):**

* B1: Customer Management
* B2: Order Processing
* B3: Billing

**Target Architecture ABBs (Future State):**

* T1: Customer Management
* T2: Order Processing
* T3: Online Payments
* T4: Billing

---

### **Step 2: Create Gap Matrix**

| Baseline \ Target       | T1: Customer Management | T2: Order Processing | T3: Online Payments | T4: Billing | Eliminated |
| ----------------------- | ----------------------- | -------------------- | ------------------- | ----------- | ---------- |
| B1: Customer Management | Included                |                      |                     |             |            |
| B2: Order Processing    |                         | Included             |                     |             |            |
| B3: Billing             |                         |                      |                     | Included    |            |
| **New**                 |                         |                      | Online Payments     |             |            |

---

### **Step 3: Interpret Gaps**

* **New ABBs (row “New”)**:

  * Online Payments → gap that needs to be implemented.

* **Eliminated ABBs (column “Eliminated”)**:

  * None in this example, so no gaps from elimination.

* **Included ABBs**:

  * Customer Management, Order Processing, Billing → already exist, no gap.

---

✅ **Key Takeaways**:

* Anything in the **“New” row** or **“Eliminated” column** is a gap.
* This matrix helps stakeholders clearly see which ABBs need **addition, removal, or transformation**.

---

Got it! Let’s break this down into a **structured TOGAF ADM approach for Gap Analysis across all domains** and how the results feed into different phases. I’ll provide it in a step-by-step, organized way so you can see the workflow clearly.

---

## **1. Gap Analysis Across Architecture Domains**

### **A. Business Architecture**

* **Input:** Baseline Business Architecture & Target Business Architecture
* **Action:**

  1. Compare Baseline ABBs (Business Functions, Processes, Capabilities) against Target ABBs.
  2. Identify:

     * **Included** → ABB exists in both
     * **New** → ABB exists in Target but not Baseline
     * **Eliminated** → ABB exists in Baseline but not Target
* **Output:** Business Gaps (missing, redundant, or transformed capabilities)

---

### **B. Information Systems Architectures (Application & Data)**

* **Input:** Baseline Information Systems Architecture & Target Information Systems Architecture
* **Action:**

  1. For each **Application Component**, compare Baseline vs Target

     * Identify **New**, **Included**, or **Eliminated** applications
  2. For **Data Architecture**, compare entities, data stores, and flows

     * Identify gaps in data availability, quality, or usage
* **Output:** Information Systems Gaps → helps determine what applications/data need to be added, modified, or retired

---

### **C. Technology Architecture**

* **Input:** Baseline Technology Architecture & Target Technology Architecture
* **Action:**

  1. Compare technology services, platforms, networks, and infrastructure
  2. Identify gaps:

     * New technologies required
     * Obsolete technologies to eliminate
     * Existing technologies that need enhancement
* **Output:** Technology Gaps → informs technology transition planning

---

## **2. Gap Analysis for Enterprise Architecture & Solution Framework**

* **Input:** Enterprise-wide Architecture & Solution Architecture/Operations
* **Action:**

  1. Compare Baseline vs Target for:

     * Enterprise Architecture domains (Business, Data, Application, Technology)
     * Solution Architectures (specific project-level architectures)
     * Operations/IT services supporting business processes
  2. Identify gaps at the **enterprise and solution level**
* **Output:** Consolidated gaps across all layers → helps align project solutions with enterprise strategy

---

## **3. Review & Consolidate Gap Analysis Results**

* **Step 1:** Collect all gaps from Business, IS, Technology, Enterprise & Solution levels
* **Step 2:** Remove duplicates and reconcile overlaps
* **Step 3:** Prioritize gaps based on:

  * Business impact
  * Cost & effort to address
  * Urgency & risk
* **Step 4:** Document in a **Gap Analysis Report** for use in subsequent ADM phases

---

## **4. Use of Gap Analysis in ADM Phases**

| ADM Phase                                      | Use of Gap Analysis Results                                                        |
| ---------------------------------------------- | ---------------------------------------------------------------------------------- |
| **Phase B: Business Architecture**             | Identify gaps in business capabilities and processes; define roadmap initiatives.  |
| **Phase C: Information Systems Architectures** | Define application & data architecture changes; identify solution projects.        |
| **Phase D: Technology Architecture**           | Define infrastructure and platform improvements; highlight technology transitions. |
| **Phase E: Opportunities & Solutions**         | Use gaps to prioritize projects, solution options, and transition architectures.   |
| **Phase F: Migration Planning**                | Plan work packages and sequencing to close gaps efficiently.                       |
| **Phase G: Implementation Governance**         | Ensure gap closure is monitored and validated during implementation.               |
| **Phase H: Architecture Change Management**    | Track new gaps as enterprise evolves and update roadmaps.                          |

---

✅ **Key Takeaways:**

1. Gap Analysis is **iterative across all architecture domains**.
2. It **feeds the ADM phases** by informing roadmap planning, solution design, and implementation priorities.
3. Consolidation ensures that all stakeholders have a **clear, unified view of what must change** to achieve the Target Architecture.

---




Do you want me to make that colorful version?

