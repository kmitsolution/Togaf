 **BDAT Architecture Domains** in Enterprise Architecture — aligning with the **TOGAF® Standard (10th Edition)** and commonly used in real-world EA practice.

---

## 🧱 TOGAF® Architecture Domains – BDAT Model

The **BDAT model** refers to the **four key architecture domains** used in TOGAF to describe different aspects of an enterprise. These domains are typically addressed across the **Architecture Development Method (ADM)** phases.

> 📘 **BDAT** = **Business, Data, Application, Technology**

Each domain answers **a different "what and how"** in the context of aligning business goals with IT systems and infrastructure.

---

### 1️⃣ **Business Architecture**

* **Purpose:**
  Defines the **business strategy**, **governance**, **organization**, and **key business processes** of the enterprise.

* **Key Focus Areas:**

  * Business goals and objectives
  * Business capabilities and functions
  * Organizational structure and roles
  * Business processes and workflows
  * Business services offered to customers or internally

> ✅ Business Architecture sets the **direction and requirements** that drive the other architecture domains.

---

### 2️⃣ **Data Architecture**

* **Purpose:**
  Describes the structure of an organization's **data assets**, including their **conceptual**, **logical**, and **physical representations**, as well as the data management resources required to manage them.

* **Key Focus Areas:**

  * Data models (conceptual, logical, physical)
  * Data entities and relationships
  * Data governance and stewardship
  * Metadata and master data management
  * Data quality, security, and compliance

> 📊 Data Architecture ensures the **right data is available**, **well-structured**, and **properly managed** to support business and applications.

---

### 3️⃣ **Application Architecture**

* **Purpose:**
  Provides a **blueprint for individual applications** to be deployed, their **interactions**, and their **relationships to core business processes**.

* **Key Focus Areas:**

  * Application portfolio and lifecycle
  * Application integration and interfaces (APIs, services)
  * Functional roles of applications
  * How applications support business capabilities
  * Interoperability and reuse

> 🧩 Application Architecture ensures that systems are **aligned with business needs**, **modular**, and **integrated** for agility and efficiency.

---

### 4️⃣ **Technology Architecture** (also called **Infrastructure Architecture**)

* **Purpose:**
  Describes the **digital architecture** and the **logical software and hardware infrastructure** required to support the deployment of **business**, **data**, and **application** services.

* **Key Focus Areas:**

  * Servers, networks, storage, and cloud infrastructure
  * Technology standards and platforms
  * Middleware, operating systems, runtime environments
  * Virtualization, containerization, and hosting models
  * Infrastructure security and performance

> 🖥️ Technology Architecture defines the **technical capabilities and standards** that enable all other domains to function efficiently.

---

## 📌 Summary Table: BDAT Architecture Domains

| Domain                       | Description                                                                                         | Key Concern Areas                      |
| ---------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------- |
| **Business Architecture**    | Defines strategy, organization, processes, and business services                                    | Goals, capabilities, processes, org    |
| **Data Architecture**        | Structures and governs data assets and resources                                                    | Data models, governance, quality       |
| **Application Architecture** | Blueprint of applications and their roles in supporting business                                    | Applications, interfaces, integration  |
| **Technology Architecture**  | Describes the infrastructure (hardware/software) needed to support business, data, and applications | Servers, platforms, standards, hosting |

---

## 🧠 Tip for TOGAF® Certification Prep:

> In the **TOGAF® ADM**, these four architecture domains are **developed iteratively** through **Phases B (Business)**, **C (Information Systems = Data + Application)**, and **D (Technology)**.

---

Great! Below are both:

---

## ✅ **BDAT Architecture Domains Diagram (Flashcard Style)**

Here’s a **clean visual representation** of the **BDAT domains** in a simple stack layout — often used in TOGAF® training to show the relationship between architecture domains.

---

### 🧱 **BDAT Model – Architecture Domains**

```
+------------------------------------------------------+
|                 🏢 Business Architecture             |
|  Defines business strategy, organization,            |
|  governance, capabilities, and processes             |
+------------------------------------------------------+
|                   📊 Data Architecture               |
|  Describes conceptual, logical, and physical data    |
|  models and data governance                          |
+------------------------------------------------------+
|                🧩 Application Architecture           |
|  Blueprint of applications, interactions,            |
|  and alignment with business processes               |
+------------------------------------------------------+
|                🖥️ Technology Architecture             |
|  Infrastructure capabilities: platforms, networks,   |
|  hosting, hardware/software standards                |
+------------------------------------------------------+
```

Each domain supports the one above it.

---
---

# 🧠 TOGAF® BDAT Architecture Domains — What Each Domain Defines

The **BDAT model** (Business, Data, Application, Technology) breaks down Enterprise Architecture into **four core domains**. Each domain defines different elements that collectively help align IT with business strategy.

---

### 🏢 **1. Business Architecture**

> **Focus:** *What the business does*

Defines the key business structures, capabilities, and strategy of the organization.

**Includes:**

* ✅ **Business Capabilities** – What the business must be able to do
* 🔁 **Business Processes** – Workflows and procedures
* 📈 **Value Streams** – How value is delivered to stakeholders
* 📘 **Information Concepts** – Key business terms and definitions
* 🏛️ **Organization Units** – Departments, teams, or roles

---

### 📊 **2. Data Architecture**

> **Focus:** *What data is needed and how it is managed*

Describes the organization’s data structures, relationships, and management practices.

**Includes:**

* 📂 **Information Objects** – Business-relevant data entities
* 🧱 **Data Objects** – Structured data models (conceptual/logical/physical)
* 🔐 **Data Management** – Governance, quality, access policies
* 🧑‍💼 **Data Resources** – Who owns, manages, or uses data

---

### 🧩 **3. Application Architecture**

> **Focus:** *How applications support business and interact*

Defines the software applications, their components, and interactions with business processes and each other.

**Includes:**

* 🧠 **Application Functions** – What each application does
* 🔗 **Application Interfaces** – How applications connect (e.g., APIs)
* 🗂️ **Application Domains** – Groupings by function or business area
* 🧾 **Application Services** – Functional services provided by apps

---

### 🖥️ **4. Technology Architecture**

> **Focus:** *What infrastructure supports the applications and data*

Describes the foundational hardware and software infrastructure supporting the enterprise.

**Includes:**

* 🖧 **IT Infrastructure** – Servers, storage, compute, networks
* 🧩 **Middleware** – Messaging, integration layers, API gateways
* 🌐 **Network Elements** – Routers, switches, firewalls, etc.
* ☁️ **Technology Platforms** – OS, databases, cloud environments
* ⚙️ **Runtime Environments** – Containers, VMs, orchestration (e.g., Kubernetes)

---

## 📘 Summary Table

| Domain                       | Defines                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------- |
| **Business Architecture**    | Business capabilities, processes, value streams, information concepts, org units        |
| **Data Architecture**        | Information objects, data objects, data management, data resources                      |
| **Application Architecture** | Applications, interfaces, domains, functions, services                                  |
| **Technology Architecture**  | IT infrastructure, middleware, network, platforms, cloud services, runtime environments |

---



# 📊 **BDAT Matrix Examples (TOGAF)**

BDAT = **Business, Data, Application, Technology**
Matrices help show **relationships, dependencies, and gaps**.

---

## 1️⃣ **Business Capability ↔ Application Matrix**

👉 *Very common in Phase B & Phase C*

### **Purpose**

* Shows which **applications support which business capabilities**
* Helps identify **gaps, redundancies, or overlaps**

### **Example**

| Business Capability | CRM App | ERP App | Portal App |
| ------------------- | ------- | ------- | ---------- |
| Customer Management | ✔       | ❌       | ✔          |
| Order Processing    | ❌       | ✔       | ✔          |
| Billing             | ❌       | ✔       | ❌          |
| Reporting           | ✔       | ✔       | ❌          |

📌 **Insights**

* CRM and ERP both support reporting → possible overlap
* Billing depends only on ERP → risk if ERP changes

---

## 2️⃣ **Business Process ↔ Data Entity Matrix**

👉 *Phase B & Phase C (Data Architecture)*

### **Purpose**

* Shows **which data is used/created by which business processes**
* Helps in **data governance and ownership**

### **Example**

| Business Process  | Customer Data | Order Data | Payment Data |
| ----------------- | ------------- | ---------- | ------------ |
| Register Customer | C             | ❌          | ❌            |
| Place Order       | R             | C          | ❌            |
| Process Payment   | R             | R          | C            |
| Generate Invoice  | R             | R          | R            |

Legend:

* **C** = Create
* **R** = Read

📌 **Insights**

* Payment data is created only in one process
* Clear ownership of data entities

---

## 3️⃣ **Application ↔ Data Matrix**

👉 *Core Phase C artifact*

### **Purpose**

* Shows which **applications create or use data**
* Identifies **master data systems**

### **Example**

| Application     | Customer Data | Order Data | Payment Data |
| --------------- | ------------- | ---------- | ------------ |
| CRM             | C             | R          | ❌            |
| ERP             | R             | C          | C            |
| Payment Gateway | ❌             | ❌          | C            |
| BI Tool         | R             | R          | R            |

📌 **Insights**

* ERP is system of record for Order & Payment
* CRM owns Customer data

---

## 4️⃣ **Application ↔ Technology Matrix**

👉 *Phase D – Technology Architecture*

### **Purpose**

* Shows **technology stack used by applications**
* Helps with **standardization and risk analysis**

### **Example**

| Application | OS      | Database   | Cloud Platform |
| ----------- | ------- | ---------- | -------------- |
| CRM         | Linux   | MySQL      | AWS            |
| ERP         | Linux   | Oracle     | On-Prem        |
| Portal      | Windows | PostgreSQL | Azure          |

📌 **Insights**

* Multiple databases → complexity
* Hybrid cloud environment

