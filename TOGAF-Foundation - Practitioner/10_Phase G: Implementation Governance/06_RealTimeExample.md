# **📘 Phase G – Real-Time Example (Implementation Governance)**

## **Scenario**

A **bank** is implementing a **new Digital Banking Platform** as part of its transformation program.

* Architecture Vision, Business, Application, and Technology Architectures are **already approved**
* Migration Plan and Roadmap were finalized in **Phase F**
* Now multiple project teams are executing the work

👉 This is where **Phase G starts**.

---

## **What Happens in Phase G (Real Life)**

### **1️⃣ Architecture Contract is Issued**

The **Enterprise Architecture team** creates an **Architecture Contract** with the delivery teams.

The contract states:

* Approved cloud platform (e.g., Azure)
* Security standards (encryption, IAM, logging)
* Integration approach (API-based)
* Compliance with architecture principles
* Review checkpoints

📌 **Real-world meaning:**
Delivery teams now know **what they must follow**.

---

### **2️⃣ Delivery Teams Implement the Solution**

Implementation is done by:

* Solution Architects
* Developers
* DevOps teams
* Vendors

They:

* Build mobile banking app
* Configure cloud infrastructure
* Integrate core banking APIs
* Deploy CI/CD pipelines

📌 **Important:**
Architecture team is **NOT coding or deploying**.

---

### **3️⃣ Architecture Compliance Reviews**

At key milestones (design complete, build complete, pre-production):

The architecture team reviews:

* Application design vs approved architecture
* Technology stack vs standards
* Security controls vs principles

📌 **Example Review Finding**

* Team used an **unapproved database technology**

---

### **4️⃣ Handling Non-Compliance**

The delivery team raises an **Architecture Change Request**.

The **Architecture Board**:

* Reviews justification
* Assesses risk and impact

Possible outcomes:

* ✅ Approve a **waiver** (temporary exception)
* ❌ Reject and ask for correction
* 🔁 Send back to architecture update (Phase H if major)

---

### **5️⃣ Continuous Governance**

Throughout implementation:

* Architecture guidance is provided
* Compliance reports are updated
* Architecture repository is kept current

📌 **Result:**
Implementation stays aligned with business strategy and architecture vision.

---

## **Simple Flow (Real Life)**

```
Phase F Plan Approved
        ↓
Architecture Contract Issued
        ↓
Delivery Teams Implement
        ↓
Architecture Reviews
        ↓
Compliant? ──► Continue
   │
   └──► Change Request / Waiver
```

---

## **🧠 One-Line Practitioner Answer**

**In Phase G, delivery teams implement the solution while enterprise architects govern compliance through contracts, reviews, and change control.**

---

## **Very Important Exam Clarification**

* ✅ Implementation **does happen** in Phase G
* ❌ Architecture team **does not implement**
* ✅ Architecture team **governs and approves**

---

