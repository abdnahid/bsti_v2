# SRS diagrams: content that exists only as images

`kb/fulltext/orangebd-srs-bsti-2.0.md` holds the SRS text layer. The diagram pages carry little or no text there. This file describes what those images contain. Pages were rendered from `BSTI 2.0 SRS .pdf` on 01 Nov 2026.

**What the image-only pages are**
- **p17**, printed page 16: the solution architecture, described in full below.
- **One diagram page per service.** For example, p20 is "HRM & Leave Management System Diagram". These show the modules and their feature bullets around a hub, plus an actors panel, a benefits panel and a key-outcomes strip. The module and feature names repeat the module headings and feature descriptions that follow in the text layer, so nothing material is lost. p20 was checked against the text.
  - **Pages:** 20, 31, 42, 51, 57, 65, 73, 81, 90, 99, 108, 117, 126, 135, 145, 154, 164, 184, 195, 203, 211, 219, 226, 233, 241, 249, 256, 263, 270, 277, 284, 289.
  - **Actors in the HRM diagram (p20):** System Admin, HR/Admin Officer, Manager/Approver, Employee, Director General.
  - **Benefits in the HRM diagram:** centralised and integrated platform, workflow efficiency, transparency, data accuracy and security, better decisions, paperless.
- **p292**, Service-32 Verification, and **p299**, Service-33 Mobile Court & Surveillance: full-page workflow images. The text layer has only the page number. Both are described below.

---

## p17: "Fig: Solution Architecture of BSTI"

Caption above the figure: *"This is the BSTI ERP Solution Architecture which shows all the ADmin, E-service and Ecommerce parts and their integration with each other."*

The figure has these layers, from top to bottom.

1. **BSTI Business Lifecycle (SDLC / Business Process):**
   1. Requirement Analysis
   2. Service Design
   3. Development
   4. Verification & Inspection
   5. Testing & Certification
   6. Approval
   7. Service Delivery
   8. Renewal
   9. Audit & Improvement
2. **Stakeholders** ("Stack Holders"):
   - Applicant
   - Laboratory Officer
   - Technical Officer/Employees
   - Mobile Court officer
   - Case officer
   - HR Department
   - Finance Department
   - Accounts Department
   - Inventory officer
   - Director
   - DG, BSTI
3. **Access channels:** Web Portal, Mobile App, Internal users/Employees, Info Desk, API/Third party.
4. **SSO/IDP (Authentication):** single sign-on, identity management and role-based access.
5. **Integration Layer (ESB / API Gateway):**
   - API Gateway
   - Workflow Engine
   - Notification Engine
   - Document Management
   - Payment Gateway
   - SMS/Email
   - Audit Log
   - Monitoring & Logging
6. **Application block,** in four parts:
   - **ADMIN ERP:**
     - HRM & Leave Management
     - Payroll Management
     - Loan Management
     - Accounts Management
     - GPF Module
     - Inventory Management
     - Case Management
   - **E-Service Platform,** a 5×6 grid of tiles:
     - CM Non-Scope Products; CM Non-Scope Product Renewal; Mandatory Brand Inclusion; CM Scope Product; CM Scope Product Renewal
     - Scope Brand Inclusion; Halal Certificate; Halal Certificate Renewal; Halal Brand Inclusion; PCR Registration
     - PCR Registration Renewal; PCR Registration Brand Inclusion; Chemical Testing; Physical Testing; Physical Testing Electrical (Energy Meter)
     - MSC Certification; MSC Recertification; Import Clearance; Import Registration; Metrology License
     - Tank Lorry Calibration; Metrology Registration; Storage Tank Calibration; I&S Metrology Calibration; Verification
     - A few tiles in the middle column were cropped in the render, so the grid may hold 1–2 more tiles.
   - **E-Commerce Platform:**
     - BSTI Marketplace
     - Product Catalog
     - Online Payment
     - Certificate verification
     - Order Management
     - Invoice Management
   - **Integrated Laboratory & Testing Platform:**
     - Chemical Lab
     - Physical Lab
     - Electrical Lab (Energy Meter)
     - Metrology Lab
     - Sample Management
     - **LIMS**
7. **External Systems & Integrations:** NID Verification, Payment Gateway, SMS Gateway, Email Gateway.
8. **Central BSTI Database:**
   - Master Database
   - HR/Employee Database
   - Service/Application Database
   - Laboratory & Test Database
   - Master Database (shown twice)
   - Certificate Database
   - Document Database
9. **Infrastructure & Platform:**
   - Cloud Server
   - Load balancer
   - Container platform
   - Storage
   - Backup & Recovery
   - Disaster Recovery
   - Network Security
   - Monitoring
10. **Security & Governance (across all layers):**
    - Data Encryption
    - RBAC
    - SSO/IDP Integration
    - API Security
    - Audit Trail & logging
    - Compliance Management
    - Backup & DR
    - Business Continuity Management
    - Security Monitoring
    - Policy & Procedure Management
11. **Key outcomes:**
    - One Integrated ERP
    - Single Sign On
    - Single Source of Truth
    - Paperless Process & Eservice
    - Integrated Lab & Testing
    - Financial Transparency
    - Online Payment & Ecommerce
    - Faster Service Delivery
    - Realtime Dashboard & Analytics
    - Data Security & Compliance

**Observations for BSTI 2.0**
- **Missing tiles and integrations:**
  - No tile for Importer/Exporter registration (Services 22/23), even though Import Registration and Import Clearance are shown.
  - No tile for Mobile Court/Surveillance in the E-service grid.
  - BSW, NBR, BIDA and RJSC are not shown as external integrations. The 2022 Business Automation contract required NID, NBR, BIDA, City Corporation and DoE.
- **Things that appear here but have no SRS service:**
  - LIMS and Inventory are in the diagram, but neither is one of the 33 SRS services.
  - "Import Clearance" is a tile but not an SRS service.
- **Infrastructure:** the diagram shows "Cloud Server / Container platform", while hosting is at BCC.

---

## p292: "Service-32: Verification Service — Detailed End-to-End Certification Workflow"

- **Roles:** Applicant, Director, DD, AD, Inspector, System.
- **Modules, numbered in the image:**
  1. **Application Submission:** online application (General / Event / Bazar / Association / Mobile); document upload; fee payment; tracking.
  2. **Application Review & Assignment:** director review; forwarding/assignment (DD/AD/Inspector); role-based assignment; workflow remarks.
  3. **Shortfall Management:** review; identification; notification; customer correction; resubmission.
  4. **Calibration Scheduling:** scheduling; rescheduling; multi-level approval (AD, DD, Director); schedule notification.
  5. **Calibration Management:** calibration execution; report preparation; findings recording.
  6. **Calibration Report Verification:** AD verification, then DD verification, then Director final approval; approval history.
  7. **Calibration Certificate & Sticker:** online certificate and sticker issuance; download; recent certificate management.
  8. **Re-inspection / Re-calibration:** request; rescheduling; repeat workflow; updated results.
  9. **Rejection:** decision; rejection letter; customer notification.
  10. **Notification highlights:** shortfall, payment request, calibration schedule, instrument submission, certificate issued, rejection.
  11. **Workflow & Task:** multi-level workflow; role-based task assignment; status tracking; remarks; audit trail.
  12. **Document Management:** application documents; calibration reports; licence repository; rejection letters.
- **Centralized data repositories:** applications, documents, calibration reports, certificates & stickers, rejection letters, audit trail.
- **End state:** "VERIFICATION COMPLETE — Certificate & Sticker Issued Successfully".

---

## p299: "Mobile Court & Surveillance e-Service Workflow" (Service-33)

- **Roles:**
  - System User (external): creates and manages operations
  - Mobile Court Team (internal)
  - Surveillance Team (internal)
  - Laboratory Team (internal): receives samples, conducts tests
  - Approving Authority (internal)
  - System (automated)
- **Flow:**
  1. Authorized user login.
  2. Create new operation.
  3. Choose the operation type.
- **3.x Mobile Court branch:**
  1. Enter mobile court details
  2. Select court type
  3. Select product type (CM/Metrology)
  4. Select product category
  5. Select product(s)
  6. Enter company information
  7. Enter offence details
  8. Enter fine amount
  9. Record DCR information
  10. Record number of cases
  11. Record imprisonment (if any)
  12. Save the mobile court record
  13. Generate the mobile court tracking ID
- **3.x Surveillance branch:**
  1. Create surveillance entry
  2. Select surveillance type
  3. Select product type (CM/Metrology)
  4. Select product category
  5. Select product(s)
  6. Enter memo information
  7. Add team members
  8. Record product observations
  9. Record DCR information
  10. Record number of cases
  11. Save the surveillance record
  12. Generate the surveillance tracking ID
- **Step 4: "Sample collected?"**
  - **Yes:**
    1. Capture sample information
    2. Enter brand name
    3. Enter batch/serial number
    4. Enter quantity
    5. Add sample remarks
    6. Send sample to laboratory
    7. Upload test report
    8. Record BDS result
    9. Update CA information
  - **No:** update operation status (5.1), then track activity (5.2).
- **Step 5.3: "Approval workflow enabled?"**
  - **Yes:** submit for approval, then the reviewer verifies the record.
  - **Step 5.6, approved?** If yes, approve the operation. If no, return it for correction and update the information.
- **Finish:**
  1. Generate reports (6.1).
  2. Update the dashboard (6.2).
  3. Archive the record.
  4. End.
- **System functions (automated):** auto-generated operation ID, status tracking, notifications, audit trail, reports.

**Notes**
- The text on p296 lists module 8, "Workflow Management", as a **future phase**. The approval branch (5.3–5.6) is therefore optional and not in scope now.
- Mobile Court and Surveillance are one combined service here. The 01 Nov 2026 minutes ask for **separate modules**.
