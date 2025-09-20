In TOGAF (The Open Group Architecture Framework), the ADM (Architecture Development Method) provides a structured process for developing, maintaining, and managing an enterprise architecture. It uses a combination of **Artifacts** and **Deliverables** to document and communicate various aspects of the enterprise architecture. Understanding how these elements relate to each other and how they evolve over time is key to managing architecture in a controlled and effective way.

### **Artifacts in TOGAF ADM**

Artifacts are architectural work products that describe specific aspects of the architecture. They can be categorized into three main types:

<img width="846" height="380" alt="image" src="https://github.com/user-attachments/assets/bdfdec50-53d1-4222-90a9-53a5e4606802" />

1. **Catalogs**: Lists or inventories of items related to the architecture.

   * **Example**: A **Business Capability Catalog** lists all the business capabilities in the organization. It could include capabilities such as "Customer Relationship Management," "Supply Chain Management," etc.

2. **Diagrams**: Visual representations of the architecture.

   * **Example**: An **Organization Map** diagram visually represents the structure of an organization, showing how different teams or departments are arranged.

3. **Matrices**: Represent the relationships between different things in the architecture.

   * **Example**: A **Capability/Organization Matrix** shows the relationship between business capabilities (listed in the Business Capability Catalog) and the organizational units responsible for them. It would map capabilities to teams, divisions, or functions.

### **Deliverables in TOGAF ADM**

A **Deliverable** is the output or product of the ADM process that is formally reviewed and approved. These deliverables are typically documents or collections of information that represent the architecture at various points in the ADM cycle.

1. **Formally Reviewed and Approved**: A deliverable goes through a formal review and approval process by relevant stakeholders before it can be considered final.

2. **Documents**: A deliverable is usually a formal document such as the **Architecture Definition Document (ADD)**, which describes the architecture in detail.

3. **Represents Project Output**: A deliverable may also represent the output of a project or a milestone in the ADM cycle. For example, after a phase of the ADM cycle is completed, a deliverable could be the result of that phase's analysis and decisions.

4. **Transition to Repository**: Once a deliverable is complete, it may be archived into an **Architecture Repository**, such as a **Reference Model** or a **Standard**, where it can be reused or referenced in the future.

#### **Example of Deliverable: Architecture Definition Document (ADD)**

* The **ADD** includes multiple artifacts like:

  * **Business Capability Map (Artifact)**: A catalog listing the capabilities.
  * **Process Flow Diagram (Artifact)**: A diagram illustrating the flow of processes.
  * **Use-Case Diagram (Artifact)**: A diagram showing how users interact with the system.

### **ADM Relationship between Artifacts and Deliverables**

* **Artifacts Contained in Deliverables**: Artifacts are the components of the deliverables. For example, the **Architecture Definition Document (ADD)** might contain a **Business Capability Map** (artifact), a **Process Flow Diagram** (artifact), and a **Use-Case Diagram** (artifact). These artifacts are used to build the final deliverable (ADD) but are not deliverables in themselves.

* **Versioning and Change Control**: Both artifacts and deliverables are subject to version control. Each time a deliverable is updated or modified, the version number is incremented to track changes. Similarly, the artifacts inside the deliverable are also versioned and maintained to ensure consistency and traceability throughout the ADM process.

### **Draft and Approved Documents**

1. **Draft Definition Documents**: These are documents that are still under development and have not yet gone through the formal review and approval process. They may still be incomplete or subject to changes.

   * **Example**: A **Draft Architecture Definition Document** might include preliminary versions of the business capability catalog, process flows, and use-case diagrams. These drafts are evolving and may not yet represent the final architecture.

2. **Approved Definition Documents**: Once reviewed, validated, and signed off by stakeholders, these documents are considered **approved**. However, approval does not mean the document is "finalized."

   * **Example**: An **Approved Architecture Definition Document** has passed review by all relevant stakeholders, but it may still evolve as the ADM process progresses.

3. **Approved ≠ Finalized**: Approved documents may still change throughout subsequent ADM phases. An architecture document can be approved at one stage but undergo updates and revisions later. These changes are managed through formal **change control** and **governance processes**.

   * **Example**: In Phase B (Business Architecture), a document may be approved. However, during Phase C (Information Systems Architectures), it might require updates due to new insights or changes in business requirements.

### **Change Control and Governance**

* **Change Control**: After a document or artifact is approved, any further changes are strictly controlled through a formal process. This ensures that updates or modifications are necessary, justified, and documented.

  * **Example**: If a **Business Capability Map** needs to be updated to reflect new capabilities or changes in business strategy, the changes are first reviewed, then approved before the map is updated.

* **Governance Process**: The governance process ensures that all changes comply with the architectural vision, principles, and standards defined for the organization. This guarantees that modifications to approved documents do not disrupt the overall architecture strategy.

#### **Example Workflow with Artifacts, Deliverables, and Change Control**

1. **Phase A (Architecture Vision)**:

   * A draft of the **Architecture Definition Document (ADD)** is created.
   * Artifacts like **Business Capability Map** (catalog) and **Organization Map** (diagram) are part of the draft.

2. **Phase B (Business Architecture)**:

   * The **ADD** is updated based on new information.
   * New diagrams like a **Process Flow Diagram** are added.
   * A formal review takes place, and the document gets **approved** (though not yet finalized).

3. **Phase C (Information Systems Architectures)**:

   * Further changes may be made to the **ADD** as technology requirements evolve.
   * The **ADD** is **updated** and potentially re-approved.

4. **Governance**:

   * Changes to the **Business Capability Map** or other artifacts undergo change control before being incorporated into the **ADD**.
   * The **ADD** is reviewed periodically to ensure alignment with the organization’s overall architecture.

### **Summary**

* **Artifacts**: Can be catalogs, matrices, or diagrams—used to represent different elements of the architecture.
* **Deliverables**: Finalized outputs of the ADM phases that contain multiple artifacts, subject to review, approval, and formal change control.
* **Approved Documents**: Not final, they evolve as new phases progress or new information is discovered, requiring careful version management and governance.
