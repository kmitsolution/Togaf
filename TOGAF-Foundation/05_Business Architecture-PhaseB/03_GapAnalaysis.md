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

If you like, I can make an **even more visual version** with colors for **Included, New, Eliminated**, so gaps really stand out. This is often how TOGAF deliverables are presented.

Do you want me to make that colorful version?

