

The most important discovery is that **NiyamStack Source is specifically a Vendor & Quotation Management Portal**, not a general document-management product.

## Section 1 — Understand the Business

### 1. What is NiyamStack Source?

**NiyamStack Source** is a structured **Vendor and Quotation Management Portal** designed to manage vendors, quotations, approvals, purchasing, contracts, and vendor performance through one organised process.

The brochure positions it for organisations such as:

* Companies
* NGOs
* Hotels
* Schools
* Hospitals
* Procurement teams
* Event organisations

The core objective is to **improve transparency, control and speed in procurement decisions**.

### 2. What problem does it solve?

The broader NiyamStack platform addresses problems caused by disconnected operations, including:

* Data scattered across Excel, paper and WhatsApp
* Manual follow-ups
* Repeated data entry
* Poor visibility of operations
* Difficult approvals
* Communication gaps
* Missed tasks
* Weak reporting
* Unreliable data
* No central document management
* High dependency on individual employees
* Difficulty scaling operations

For **Source specifically**, the problem is the lack of a structured process for managing vendors and procurement information.

Instead of managing vendor documents, quotations, comparisons, approvals and purchase information separately, Source brings them into an organised workflow.

### 3. Who are the users/stakeholders?

Based directly on the brochure, the primary organisational users are:

**External / business stakeholders**

* Vendors
* Suppliers

**Internal stakeholders**

* Procurement teams
* Management/approvers
* Employees involved in purchasing
* Administrators

The exact individual roles within a procurement team are **not specified in the brochure**, so we should not invent roles such as "Procurement Manager" or "Finance Manager" as confirmed requirements yet.

However, the existence of **role-based access, custom roles and approval workflows** indicates that different users will have different permissions.

### 4. What is the current workflow?

The brochure doesn't document an existing "As-Is" workflow for a customer, so we should distinguish this from the proposed NiyamStack workflow.

From the Source modules, the intended process can be understood as:

```text
Vendor Onboarding
       ↓
Vendor Documents
       ↓
Request for Quotation
       ↓
Quotation Submission
       ↓
Comparison Sheets
       ↓
Approval Workflow
       ↓
Purchase Records
       ↓
Contracts
       ↓
Renewal Reminders
       ↓
Vendor Performance
       ↓
Reports & Analytics
```

Notifications operate across the workflow.

This is one of the most important parts of the project because **Source isn't merely storing vendor information; it is structuring the procurement lifecycle.**

### 5. What documents/data are managed?

The brochure explicitly identifies several information categories:

| Data / Document     | Purpose                               |
| ------------------- | ------------------------------------- |
| Vendor information  | Manage vendors                        |
| Vendor documents    | Maintain vendor-related documentation |
| RFQs                | Request quotations                    |
| Quotations          | Collect vendor quotations             |
| Comparison sheets   | Compare quotations                    |
| Approval records    | Manage approval workflow              |
| Purchase records    | Track purchases                       |
| Contracts           | Manage vendor contracts               |
| Renewal information | Track contract renewals               |
| Vendor performance  | Evaluate vendors                      |
| Reports & analytics | Analyse procurement operations        |
| Notifications       | Keep users informed                   |

The broader NiyamStack platform also identifies **document management, data export, audit logs/activity history and backup/recovery** as shared capabilities.

### 6. What are the major modules?

The brochure gives us a very clear Source module list:

```text
NiyamStack Source
│
├── Vendor Onboarding
├── Vendor Documents
├── Request for Quotation
├── Quotation Submission
├── Comparison Sheets
├── Approval Workflow
├── Purchase Records
├── Contracts
├── Renewal Reminders
├── Vendor Performance
├── Reports & Analytics
└── Notifications
```

These should form the initial functional backbone of the project.

### 7. What are the platform capabilities?

NiyamStack describes a shared foundation across its product portfolio. For Source, these capabilities are particularly relevant:

* Role-based access
* Secure access
* Mobile-responsive interface
* Dashboards and analytics
* Reports and data export
* Document management
* Payment tracking
* Approval workflows
* Notification engine
* Audit logs and activity history
* Multi-location support
* Custom roles
* Search and filters
* Backup and recovery
* API / third-party integrations
* Multi-tenant or dedicated deployment

These are **platform capabilities**, so we should distinguish them from Source-specific modules. 

### 8. What is the core value proposition?

The brochure's clearest statement for Source is:

> **Improve transparency, control and speed in procurement decisions.**

That gives us three primary product goals:

**Transparency**
→ Know which vendor submitted what, when, and how it compares.

**Control**
→ Control access, approvals, documents and procurement records.

**Speed**
→ Reduce manual coordination and make quotation/approval processes faster.

### 9. Competitors

The brochure **does not name any competitors**.

Therefore, competitor analysis should be a separate research activity rather than something we claim is derived from the brochure.

For the next phase, we can investigate products in categories such as:

* Vendor management
* Procurement management
* RFQ/quotation management
* Purchase management
* Supplier management

Then compare them against NiyamStack Source.

### 10. Business understanding — one-line model

The whole product can be reduced to:

```text
Vendors
   ↓
Vendor Information & Documents
   ↓
RFQ
   ↓
Quotations
   ↓
Comparison
   ↓
Approval
   ↓
Purchase
   ↓
Contract
   ↓
Renewal
   ↓
Performance
```

And around this lifecycle:

```text
        ┌─────────────────────────┐
        │   NiyamStack Source     │
        │                         │
        │ Search & Filters        │
        │ Notifications           │
        │ Role-based Access       │
        │ Audit History           │
        │ Reports & Analytics     │
        │ Document Management     │
        └─────────────────────────┘
```

## What we should do next

I suggest we **don't jump to UI design yet**.

The project should progress in this order:

**Section 1 — Business Understanding**
↓
**Section 2 — Stakeholder & User Analysis**
↓
**Section 3 — Procurement Workflow / User Flows**
↓
**Section 4 — Functional Requirements**
↓
**Section 5 — Information Architecture**
↓
**Section 6 — Competitor Analysis**
↓
**Section 7 — UX/UI**
↓
**Section 8 — Technical Architecture**

The **next most valuable step is Section 2: Stakeholder & User Analysis**, where we identify exactly **who interacts with Source, what each person does, what they need to see, and what permissions they should have**.
