
# 🛵 BDAT Case Study: **FoodieFast** — A Food Delivery Platform

**Business Objective:**
Expand FoodieFast’s reach with faster delivery, customer personalization, and scalable operations.

---

## 🏢 1. **Business Architecture Case Study**

### 📘 Scenario:

FoodieFast wants to offer **"15-minute express delivery"** and expand to new cities.

### 🧩 What’s Defined:

| Element                   | Example                                                       |
| ------------------------- | ------------------------------------------------------------- |
| **Business Capabilities** | Delivery Management, Vendor Onboarding, Customer Service      |
| **Business Processes**    | Order Placement, Rider Assignment, Complaint Handling         |
| **Value Streams**         | "Customer Order to Delivery", "Partner Restaurant Onboarding" |
| **Information Concepts**  | Customer, Order, Rider, Menu, Delivery Zone                   |
| **Organization Units**    | Customer Operations, Logistics, Tech, Partner Management      |

### 🎯 Outcome:

Business goals like “reduce delivery time” and “expand market share” are formally mapped to business capabilities and processes. This becomes the **driver** for Data, Application, and Technology design.

---

## 📊 2. **Data Architecture Case Study**

### 📘 Scenario:

To support express delivery, FoodieFast needs **real-time tracking and predictive order allocation**.

### 🧩 What’s Defined:

| Element                 | Example                                                            |
| ----------------------- | ------------------------------------------------------------------ |
| **Information Objects** | `Order`, `Delivery Time`, `Rider Location`, `Customer Profile`     |
| **Data Objects**        | Tables: `orders`, `users`, `locations`, `restaurant_avg_prep_time` |
| **Data Management**     | Data Quality Checks, GDPR Compliance, Retention Policies           |
| **Data Resources**      | Data Lake, PostgreSQL DB, Snowflake for analytics                  |

### 🎯 Outcome:

Well-structured, integrated data enables **AI-based delivery routing**, **customer personalization**, and **compliance with data regulations**.

---

## 🧩 3. **Application Architecture Case Study**

### 📘 Scenario:

FoodieFast is rolling out a **new loyalty program** and must integrate it across web, mobile, and partner portals.

### 🧩 What’s Defined:

| Element                    | Example                                                            |
| -------------------------- | ------------------------------------------------------------------ |
| **Applications**           | `Customer App`, `Restaurant App`, `Delivery App`, `Loyalty Engine` |
| **Application Interfaces** | REST APIs for loyalty, GraphQL for order data                      |
| **Application Functions**  | Order Creation, Loyalty Point Accrual, Menu Update                 |
| **Application Domains**    | Customer Experience, Logistics, Partner Management                 |
| **Application Services**   | `GetLoyaltyPoints()`, `TrackOrder()`, `UpdateMenu()`               |

### 🎯 Outcome:

Clear application boundaries and interfaces allow for **faster rollout**, **cleaner integration**, and **reuse of services** across platforms.

---

## 🖥️ 4. **Technology Architecture Case Study**

### 📘 Scenario:

As traffic grows, FoodieFast needs to move to **cloud-native infrastructure** and improve uptime.

### 🧩 What’s Defined:

| Element                  | Example                                               |
| ------------------------ | ----------------------------------------------------- |
| **IT Infrastructure**    | AWS Cloud (EC2, RDS), Kubernetes, CDN, Load Balancers |
| **Middleware**           | Kafka for real-time messaging, Redis for caching      |
| **Network Elements**     | Cloud VPC, Private APIs, Secure VPNs                  |
| **Technology Platforms** | Linux, Node.js, Python, PostgreSQL                    |
| **Runtime Environments** | Docker containers, Serverless (Lambda)                |
| **Cloud Services**       | AWS Lambda, S3, CloudFront, DynamoDB                  |

### 🎯 Outcome:

High scalability, **99.9% uptime**, and the ability to roll out to **new regions in days, not weeks**.

---

## ✅ Summary Table – BDAT in Practice

| Domain                       | What’s Defined in FoodieFast Use Case                                 |
| ---------------------------- | --------------------------------------------------------------------- |
| **Business Architecture**    | Capabilities like Delivery Ops, processes like Rider Assignment       |
| **Data Architecture**        | Real-time data for orders, customer profiles, data quality governance |
| **Application Architecture** | Modular apps (Customer, Restaurant, Loyalty), APIs, services          |
| **Technology Architecture**  | Cloud infra (AWS), containers, middleware, tech platforms             |

---

