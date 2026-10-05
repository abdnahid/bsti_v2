# Session 1 — Initial analysis of OrangeBD's BSTI 2.0 proposal

**Date:** 5 October 2026
**Inputs reviewed:** all five files in this folder (history note sheet, forwarding letter, Financial Proposal V4, BSTI 2.0.pptx, BSTI 2.0 SRS)
**Status:** first-pass analysis delivered; detailed discussion to follow.

## User's brief (summary)

- BSTI has tried to digitalize since the Digital Bangladesh / Vision 2021 drive, but without a plan, leaving five disconnected systems:
  1. QR code software (certificates / test reports for CM licence, metrology PCR, tank lorry calibration, chemical and physical lab reports); no stakeholder access.
  2. BSTI billing software; one-stop service staff only; clients still fill forms manually.
  3. Inventory management (internal).
  4. Standards sale.
  5. Alo attendance.
- **Vision:** one fully automated ERP. Clients apply from home; BSTI processes internally through every wing and desk; clients download certificates from home. It also covers inventory, accounts, HR, attendance, salary and so on.
- **v1 story:** BTF (USAID-funded) collected requirements and flow charts and hired OrangeBD (~91 lakh). BSTI had no direct link to the vendor.
  - Standards selling went first (`ec.eservice.bsti.gov.bd`).
  - CM quality licence was then rushed so the outgoing DG could inaugurate it.
  - The result is a disconnected standards purchase, online CM application on `eservice.bsti.gov.bd`, staff on `admin.` and `workflow.eservice.bsti.gov.bd` with email/password logins.
  - The testing wing writes reports manually and uploads them. CM then issues the certificate.
  - It runs at head office only; divisional and regional offices weren't considered.
  - Patching failed, so a full restructure is needed.

## Findings

### 1. History note sheet (v1)

| Date | Event |
|---|---|
| 14 & 22 Apr 2024 | BTF Senior Advisor (Land O'Lakes Venture37) emails. Meeting with DG; BTF offers IT logistics, awareness and training. The note says the BSTI–USAID BTF MOU covers 7 areas but **does not explicitly include the automation system**. A three-party meeting (BSTI, BTF and the IT firm) is requested. |
| 7 May 2024 | Meeting with ICT section and wing representatives to list incomplete "1st phase" automation work. The DG directs that the gaps be identified. Programmer Shaheen Sultana is tasked. |
| 26 May 2024 | Three-party meeting on "e-Application Management System at BSTI": BSTI, BTF and **Business Automation Ltd** (not OrangeBD). |
| 3–10 Jun 2024 | Requirement sessions, **one half-day per wing**: Chemical 3 Jun, Physical 4 Jun, CM 5 Jun, MSC and Admin 9 Jun, Metrology and Standards 10 Jun. |
| Aug–Sep 2024 | Validation workshops: CM 1 Aug, Chemical/Physical 4 Sep, MSC/Admin 15 Sep, Metrology 26 Sep. |
| 2 Jan 2025 | Kick-off with OrangeBD (contract start 12 Jan 2025 per the letter). |
| ~Aug 2025 | OrangeBD's SRS arrives through Land O'Lakes Venture37 and goes to the wings for comment. |
| May–Sep 2025 | Wing feedback (details below). |

Wing feedback on the v1 SRS:

- **MSC:** certificate suspension, cancellation and surveillance audit not specified.
- **CM:** errors found; raised in joint reviews.
- **Metrology:** two important services missing (verification of weights and measuring instruments; import clearance and verification). BTF's IT specialist acknowledged this.
- **Physical:** "SRS does not reflect the physical wing's requirements." A private-sample prototype was shown on 21 May 2025; observations were to be "resolved later"; sample receiving and in-lab flow were also deferred.
- **Chemical:** prototype validation on 4 Jun 2025; observations were to be "resolved later".
- **Standards:** e-commerce was wrongly placed under the Admin wing. Approval workflow to be revised. Comment: *"System on air না হলে সমস্যা চিহ্নিত করা দুষ্কর"* ("problems are hard to identify until the system is live").

**Root cause:** BSTI never owned the contract, requirements or architecture. Requirements were thin, the vendor wrote the SRS after development had started, and gaps were deferred.

### 2. Forwarding letter (21 Sep 2026)

The project ran under BTF from 12 Jan 2025 to 31 Jul 2026, with the contract amended on 13 Jun 2025. Five services were launched. From 1 Aug 2026 OrangeBD "reviewed" needs and now proposes a **managed-service** contract directly with BSTI, addressed to the BSTI Project Director.

### 3. Financial proposal (verified)

| Period | Live services | Rate per service per month | Payment (BDT) |
|---|---|---|---|
| Aug–Dec 2026 | 5 | 65,000 | 1,625,000 (lump sum) |
| 2027 (quarters) | 5 → 8 → 11 → 14 | 180,000 | 20,520,000 |
| 2028 | 17 → 20 → 23 → 26 | 155,000 | 39,990,000 |
| 2029 | 29 → 32 → 33 → 33 | 130,000 | 49,530,000 |
| **Rollout total** | | | **111,665,000** |
| 2030–2031 | 33 | 95,000 (3,135,000/month) | 75,240,000 |
| **Grand total** | | | **186,905,000 + VAT/taxes** |

- The "staff-remuneration benchmark" is BDT 235,530,000, giving a claimed 20.6% saving. The arithmetic is correct.

Problems identified:

1. **The benchmark is the vendor's own hypothetical team, not a market price.** Examples: a finance consultant at ৳3 lakh/month (above the PM's ৳2.5 lakh), 6 helpdesk plus 6 support engineers for 36 months, and 4 trainers during maintenance.
2. **The rate converges to the full team cost.** In 2029, 33 × 130k = ৳42.9 lakh/month against the "staff equivalent" of ৳43.8 lakh. Maintenance at ৳31.35 lakh/month "saves" only 3.3%.
3. **Billing for services already built.** Payment starts Aug 2026, backdated, for the 5 BTF-funded services, then ৳1.8 lakh each per month from 2027.
4. **Missing terms:** source code and IP ownership, a definition of "live" (acceptance), SLAs and penalties, hosting and infrastructure cost, change-request rates, exit and transition, anything after 2031.
5. **Timeline mismatch:** the rollout spans 41 months but the benchmark is costed for 36.
6. **The vendor's own benchmark slide undercuts the offer:** myGov ৳12 crore over 52 months; RDCD platform ৳11.44 crore over 3 years (both OrangeBD projects). Both are cheaper than BSTI's ৳18.69 crore.
7. **Scale:** about 20× the v1 cost (~91 lakh).

### 4. The 33 services, and how many are really distinct

The 33 listed services: HRM & Leave, Payroll, Finance & Accounts, Case Management, CM Mandatory (New / Renewal / Brand Inclusion), CM Scope (New / Renewal / Brand), Halal (New / Renewal / Brand), Chemical Testing, Physical Testing, Energy Meter, MSC Certification, MSC Re-certification, PCR (New / Renewal / Brand), Importer/Exporter (New / Renewal), Metrology Licence (Issue / Renewal), Tank Lorry Calibration, LPG/Fuel station (Registration / Renewal), Building/Establishment Measurement, Storage Tank Calibration, Industrial & Scientific Calibration, Verification, Mobile Court & Surveillance.

The PPTX counts 440 modules and 2,168 features.

Text similarity between paired SRS sections (difflib word-level ratio):

| Pair | Similarity |
|---|---|
| CM Mandatory New vs Renewal | 0.981 |
| CM Mandatory New vs Brand Inclusion | 0.917 |
| CM Scope New vs Renewal | 0.983 |
| Halal New vs Renewal | 0.988 |
| PCR New vs Renewal | 0.854 |
| Metrology Licence vs Renewal | 0.938 |
| LPG Registration vs Renewal | 0.942 |
| Importer/Exporter New vs Renewal | 0.901 |

- This leaves **about 21 distinct workflow families**. Roughly 12 "services" are variants priced as full services; their maintenance alone is about 12 × 95k × 24 ≈ ৳2.7 crore.
- Most of the families share one skeleton: application → shortfall → inspection → AD/DD/Director → certificate. A configurable workflow engine would make them configuration, not development.
- PPTX copy-paste errors: the CM Scope Renewal subtitle reads "Human Resource Administration • Employee Lifecycle"; the Halal slide lists "Leave Management" and "Employee Administration"; Mobile Court lists "Employee Modification".

### 5. SRS quality (303 pages)

What the SRS contains:

- A feature catalogue: each feature is a one-line description.
- A solution architecture diagram (p.17).

What it lacks (keyword counts across the full text):

| Topic | Count |
|---|---|
| "non-functional" | 0 |
| Data migration from existing systems | 0 (one GPF opening-balance mention) |
| NID / eKYC, NBR / customs, NSW / BIDA, a-challan integration | 0 |
| Sonali Bank | 1 one-line feature |
| Inventory | 0 |
| Attendance | 0 |
| Standards sale / e-commerce | 0 (outside the diagram caption) |
| Training, standards formulation | 0 |
| Backup / DR | 1 line |
| Surveillance audit, import clearance | 0 |

Also missing throughout: forms and fields, fee rules, desk-by-desk roles and SLAs, acceptance criteria per feature.

The architecture diagram shows components that **aren't in the 33-service scope or the text**: Inventory, E-commerce platform (marketplace, order and invoice management), LIMS, NID verification, mobile app, Import Clearance.

### 6. v1 failures repeated in v2

- **CM Mandatory (services 5–7) has zero mentions of sample, laboratory or testing.** The CM-to-lab gap that broke v1 is still there. Chemical Testing (14) is standalone. Only CM Scope and Halal mention a lab testing module.
- **Regional offices:** "Regional Office Workflow" is 3 one-line features (Head Office workflow, Regional Office workflow, Wing-head processing), and only in Chemical and the PCR services. Nothing for CM, MSC or Halal.
- **Gaps flagged in 2025 are still absent:** MSC suspension, cancellation and surveillance audit; Metrology import clearance.
- **Standards purchase is still not linked** to the CM application.

## Recommendations given

1. Don't accept as-is; treat it as OrangeBD's opening position.
2. BSTI owns v2: its own SRS (or an independent review), source code, data and hosting (BCC / National Data Center).
3. Build a **platform, not 33 apps**:
   - single portal and SSO for clients and staff
   - configurable workflow/BPM engine, with office (HQ / divisional / regional) built in from day one
   - shared LIMS called by every certification flow
   - one fee and payment engine
   - one certificate and QR engine

   Then price per platform plus per workflow family.
4. Contract essentials:
   - "live" means UAT sign-off plus real transactions
   - SLAs with penalties
   - source code handover or escrow
   - exit and transition plan
   - total cost cap
   - change-request rates
5. Check procurement compliance (PPA/PPR) now that this would be a direct BSTI contract of ~৳18.7 crore without BTF.

## Open questions for the user

- Which 5 services are live now?
- Who holds the source code and the servers today?
- Annual application volumes and number of offices that need access?
- Budget source (revenue vs ADP project)?

## Next steps

- Detailed discussion (user to lead), likely covering target architecture, a BSTI-owned requirements approach, and a negotiation and counter-proposal position.
