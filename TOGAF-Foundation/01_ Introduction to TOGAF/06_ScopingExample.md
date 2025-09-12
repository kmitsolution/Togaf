Absolutely! Here's a detailed **case study** on **Scoping Architectures** using a **Foodie Delivery Application** example, illustrating the four key scoping dimensions from TOGAF: Enterprise Scope, Level of Detail, Architecture Domains, and Time Period.

---

# 🍔 Case Study: Scoping Architecture for "FoodieGo" Delivery App

---

## 🎯 Background

FoodieGo is a startup aiming to disrupt the food delivery market by offering fast, personalized, and AI-driven meal delivery services. The company plans to develop an integrated architecture to support rapid growth and scale efficiently.

The Enterprise Architecture (EA) team is tasked with scoping the architecture effort before beginning detailed design and development.

---

## 1. **Enterprise Scope (Breadth)**

**Question:** What part of FoodieGo will this architecture effort cover?

| Option           | Decision for FoodieGo                                                             |
| ---------------- | --------------------------------------------------------------------------------- |
| Whole Enterprise | FoodieGo's entire business, including delivery, marketing, and customer service.  |
| Business Unit    | Focus only on the **Delivery Operations Unit** responsible for order fulfillment. |
| Department       | Zoom in on the **Order Processing Department**.                                   |
| Processes        | Only the **Order Tracking and Delivery Scheduling** processes.                    |

**Chosen Scope:**
The architecture effort will cover the **Delivery Operations Unit**, including order processing, courier management, and delivery tracking. This allows focused but broad enough scope to improve the core value delivery function.

---

## 2. **Level of Detail (Depth)**

**Question:** How detailed should the architecture be?

| Level               | Application to FoodieGo                                                                        |
| ------------------- | ---------------------------------------------------------------------------------------------- |
| High-Level Strategy | Define key business capabilities and major systems like Order Management, Delivery Scheduling. |
| Medium Detail       | Define application interfaces, data flow between Order Management and Courier apps.            |
| Detailed Design     | Define specific API specs, data schema, and deployment environments.                           |

**Chosen Level:**
**Medium Detail** — enough to design major applications and integrations while leaving detailed system design for later phases.

---

## 3. **Architecture Domains**

**Question:** Which domains will be addressed?

| Domain                   | FoodieGo’s Inclusion Reason                               |
| ------------------------ | --------------------------------------------------------- |
| Business Architecture    | Yes, to model delivery processes and roles.               |
| Data Architecture        | Partial, focusing on delivery-related data only.          |
| Application Architecture | Yes, for the delivery app, courier app, backend services. |
| Technology Architecture  | Yes, cloud infrastructure, mobile platforms, APIs.        |

**Chosen Domains:**
All four domains, but Data Architecture scope limited to delivery data only.

---

## 4. **Time Period (Planning Horizon)**

**Question:** What is the timeframe of this architecture effort?

| Timeframe             | FoodieGo Considerations                          |
| --------------------- | ------------------------------------------------ |
| Short-Term (1 Year)   | Rapid MVP development and launch                 |
| Medium-Term (3 Years) | Scale operations, improve AI routing             |
| Long-Term (5+ Years)  | Expand into new cities, add full CRM integration |

**Chosen Time Period:**
**Medium-Term (3 years)** to allow phased rollout of capabilities and future scalability.

---

## Summary Table for FoodieGo Architecture Scope

| Dimension            | Scope Definition                                   |
| -------------------- | -------------------------------------------------- |
| Enterprise Scope     | Delivery Operations Unit                           |
| Level of Detail      | Medium Detail (application interfaces, data flows) |
| Architecture Domains | Business, Data (limited), Application, Technology  |
| Time Period          | 3 years (medium-term roadmap)                      |

---

## 📊 Visual Diagram for FoodieGo Architecture Scope

```plaintext
+-------------------------------------------------------------+
|                     FoodieGo Architecture Scope             |
|-------------------------------------------------------------|
| Enterprise Scope: Delivery Operations Unit                   |
|-------------------------------------------------------------|
| Level of Detail: Medium (Apps & Integration Focus)           |
|-------------------------------------------------------------|
| Architecture Domains: Business | Data (limited) | Application | Technology |
|-------------------------------------------------------------|
| Time Period: Medium-Term (3 Years)                           |
+-------------------------------------------------------------+
```

---

## 🚀 How This Scope Drives Architecture Work

* **Business Architecture:** Map delivery workflows, courier roles, order tracking processes.
* **Data Architecture:** Define delivery-related data models (orders, locations, courier status).
* **Application Architecture:** Design delivery management app, courier mobile app, and backend services.
* **Technology Architecture:** Specify cloud infrastructure, APIs, mobile platforms, and network services.

---

## 🎯 Outcome

With a clearly scoped architecture:

* The team can **prioritize resources** on key business units.
* Avoid **over-engineering** by limiting detail to what’s needed now.
* Align stakeholders with a **common vision** for what will be covered.
* Plan a **3-year phased roadmap** with clear transition states.

---

